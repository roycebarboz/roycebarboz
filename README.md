# Hello there, welcome to Royce Barboz's GitHub

I enjoy building scalable systems with built-in observability and a focus on production reliability.

## Contact Info:
**Email:** roycebarboz@gmail.com.
**LinkedIn:** https://www.linkedin.com/in/royce-barboz/

### Experience

#### [Coursedog Internal Events Notes generator](https://github.com/roycebarboz/coursedog-internal_notes_generator)
*Automation tool developed while working as a Student Technology Support Assistant at Stevens Institute of Technology.*

- Built a full-stack automation tool using Claude Code, parsing Coursedog CSV exports, applying 15+ scheduling logic cases, and submitting formatted event notes via authenticated REST API, streamlining workflows and cutting a multi-hour weekly process to minutes.
- Architected end-to-end pipeline (CSV --> parse --> group --> API fetch --> generate --> review --> submit) with Next.js App Router, session-based state, and 200+ venue code mapping; developed with Claude Code, stateless architecture
-	Wrote PowerShell scripts automating workspace initialization — launching directories, tools, and 10+ preconfigured browser sessions, reducing setup time by ~80%

#### [React/Vite + Firebase web app](https://github.com/IGSCF/IGSCF_website)
*Website for IGSCF Non-Profit Organization.*

-	Developed and delivered a production React/Vite web app from scratch for a nonprofit, gathering stakeholder input and translating it into shipped features, resulting in 20% increase in user engagement using Claude Code.
-	Integrated Firebase Auth + Firestore with RBAC and security rules (public reads, authenticated writes), owning full auth architecture end-to-end
-	Created comprehensive documentation for all developed tools and scripts, ensuring maintainability and knowledge transfer across the team.
-	Shipped CI/CD via Git/GitHub Actions with asset optimization, including automated testing and deployment workflows; met Lighthouse performance targets pre-launch.


### Projects

#### [Financial RAG Analyst](https://github.com/sarthakk-3107/rag_analyst)
*A Multi-Agent System for financial risk and compliance.*
- Engineered a multi-agent workflow increasing task accuracy by **40%**.
- Optimized embedding pipelines using **OpenAI text-embedding-3-small**, reducing infrastructure costs.
- Implemented caching to lower query latency from **30s to <2s**.

#### [Inspectify - NYC Health Dashboard](https://github.com/roycebarboz/NYC-Restaurant-Health-Inspector-Dashboard)
*Scalable ETL pipeline and dashboard for restaurant health inspections.*
- Processed **289K+ records** using a robust Node.js ETL pipeline.
- Improved query performance by **60%** through optimized MongoDB indexing.
- Designed a modular data layer for seamless API integration.

#### [F1 Telemetry Dashboard](https://github.com/backdoor-boys/f1-vision-dashboard)
*Real-time observability platform for F1 race data.*
- Containerized full-stack telemetry dashboard (React/TypeScript frontend, Python API backend) using Docker and deployed services on AWS ECS (Fargate) behind an Application Load Balancer.
- Integrated observability with Datadog and CloudWatch for metrics, logs, and alerts, enabling runtime performance monitoring and failure diagnosis.
