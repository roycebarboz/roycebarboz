# Hello there, welcome to Royce Barboz's GitHub
I enjoy building scalable AI systems with built-in observability and a focus on production reliability.

## Contact Info:
**Email:** roycebarboz@gmail.com
**LinkedIn:** https://www.linkedin.com/in/royce-barboz/

---

### Experience

#### [Stevens Institute of Technology](https://github.com/roycebarboz/coursedog-internal_notes_generator) — Technology Support
*Hoboken, NJ, USA | May 2025 – Present*
- Built a full-stack automation tool using Claude Code that parsed Coursedog CSV exports, applied 15+ scheduling logic cases, and submitted formatted event notes via authenticated REST APIs in Python — cutting a multi-hour weekly process to minutes, with unit testing and peer review workflows.
- Automated workspace initialization by writing Python and PowerShell scripts that launched directories, tools, and 10+ preconfigured browser sessions, reducing setup time by ~80%.
- Collaborated with cross-functional teams in an Agile environment, participating in daily stand-ups, sprint planning, and retrospectives to deliver high-quality software.
- Created comprehensive documentation for all automation tools and scripts, reducing onboarding time for new team members by ~70%.

#### [IGSCF](https://github.com/IGSCF/IGSCF_website) — Full-Stack Developer (Freelance)
*Hoboken, NJ, USA | Feb 2026 – Present*
- Gathered stakeholder input and translated it into shipped features for a nonprofit, providing technical consulting on a production React/Vite web app — resulting in a 20% increase in user engagement using Claude Code.
- Integrated Firebase Auth + Firestore with RBAC and security rules (public reads, authenticated writes), owning full auth architecture end-to-end.
- Shipped CI/CD via Git/GitHub Actions with asset optimization, automated testing, and deployment workflows in JavaScript; met Lighthouse performance targets pre-launch with robust version control.

---

### Projects

#### [Verity](https://github.com/roycebarboz/Verity)
*Five-agent customer-support triage pipeline with hallucination and injection defenses | LangGraph, Pydantic, AWS ECS Fargate, DynamoDB, Terraform, Datadog, Python — May 2026*
- Designed a five-agent customer-support triage pipeline (Bouncer, Librarian, Drafter, Verifier, Dispatcher) using LangGraph with a typed Pydantic state machine; concentrated reasoning at the Verifier to block hallucinations via a conditional retry loop (up to 2 retries) with hard injection-attack exits routing directly to human escalation.
- Enforced multi-layer security: regex + LLM prompt-injection detection, citation-grounded Drafter constrained to retrieved chunks only, PII redaction before DynamoDB/log writes, and Verifier gating blocking uncited claims — with API keys in AWS Secrets Manager and a least-privilege Fargate task role.
- Deployed on AWS ECS Fargate + ALB via Terraform IaC; integrated Datadog LLM Observability (5 named spans/ticket, faithfulness + citation-coverage evals); validated with a 30-ticket offline eval suite (retrieval precision, injection detection, PII leakage) using pytest.

#### [ProcureIQ](https://github.com/roycebarboz/ProcureIQ)
*Multi-agent procurement risk copilot | LangGraph, FastAPI, Azure OpenAI (GPT-4o), Azure AI Search, Terraform, OpenTelemetry/Dynatrace, React/TypeScript — Jun 2026*
- Delivered cited, 1–10 scored Approve/Escalate/Reject risk briefs across 8 vendor scenarios by architecting a four-agent LangGraph pipeline (Market Scout → Policy Librarian → Risk Synthesizer → Human Review) on a typed state machine that routes dual hard-fails to human review via GPT-4o structured output.
- Eliminated fabricated risk scores across 12 partial-data test cases by engineering a graceful-degradation matrix — single Tavily retry with ERP-only fallback, blocking-vs-advisory policy classification, and confidence that decays algorithmically from missing sources, hard-capping incomplete assessments at ≤6.
- Streamed live node-completion events to a React/TypeScript dashboard over FastAPI SSE, and surfaced per-LLM-call token usage and derived cost in real time via OpenTelemetry GenAI spans exported to Dynatrace.
- Shipped to Azure Container Apps via a GitHub Actions pipeline (lint-test → build → push to ACR → terraform apply + rolling update) over Terraform-provisioned infra, validated by 93 automated tests (55 pytest, 38 Vitest).

#### [Inspectify - NYC Health Dashboard](https://github.com/roycebarboz/NYC-Restaurant-Health-Inspector-Dashboard)
*Scalable ETL pipeline and dashboard for restaurant health inspections | Node.js, MongoDB, Express.js — Dec 2025*
- Built a scalable ETL pipeline in Node.js to process 289K+ CSV rows into structured MongoDB documents, grouping inspection records by CAMIS and extracting latest health grades for NYC restaurant data.
- Developed a modular data layer separating parsing, grouping, and DB operations, enabling clean integration with Express API routes for the full-stack team and generating HTML reports for stakeholders.

---

### Education
**Stevens Institute of Technology** — M.S., Computer Science *(May 2026)*
Hoboken, NJ, USA

**St. Francis Institute of Technology** — B.E., Information Technology *(Jun 2024)*
Mumbai, MH, India

---

### Technical Skills
| Category | Skills |
|---|---|
| **Generative AI** | OpenAI, Claude Code, RAG, Embeddings, Multi-agent systems, n8n, LangGraph, Prompt Engineering |
| **Languages** | JavaScript, Python, TypeScript, SQL, Bash, Golang |
| **Frameworks & Libraries** | React.js, Node.js, Express.js, Next.js, FastAPI, REST APIs |
| **Cloud & DevOps** | AWS (EKS, ECS), Docker, GitHub Actions, Kubernetes, Azure, GCP |
| **Databases** | PostgreSQL, MySQL, MongoDB, Supabase |
| **Tools** | Git, Linux/SSH, Agile (Scrum, Kanban), Postman, Microsoft Office, Google Workspace |

---

### Certifications
- **Oracle Cloud Infrastructure Generative AI Professional** — Aug 2024
- **AWS Certified Solutions Architect – Associate (SAA-C03)** — *In Progress, Exam: July 2026*
