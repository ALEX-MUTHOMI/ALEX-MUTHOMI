# Alex Muthomi

**Backend Engineer and Founder of BackToFront Development**  
Python | Django REST Framework | Cloud Backend Architecture | Infrastructure Automation

I design and build backend platforms where API boundaries, data integrity, infrastructure, and security have to work together. My strongest work is in Django-based service architecture, multi-tenant systems, asynchronous processing, secure file workflows, deployment automation, and cloud-ready backend foundations.

Through **BackToFront Development**, I turn business requirements into working web systems, with a bias toward backend reliability, maintainable architecture, and deployment discipline.

[LinkedIn](https://www.linkedin.com/in/alex-mputhia) | [Email](mailto:muthomialex64@gmail.com) | [GitHub](https://github.com/ALEX-MUTHOMI)

## Backend Systems Are My Primary Operating Surface

- **API architecture:** Django REST Framework, authentication, authorization, permissions, domain boundaries, and service-level validation.
- **Distributed workflows:** Celery, Redis, asynchronous jobs, idempotent webhook handling, direct-to-storage upload flows, and background processing.
- **Data reliability:** PostgreSQL, transactional workflows, quota enforcement, row-locking patterns, and tenant-aware access control.
- **Cloud delivery:** Docker, Docker Compose, Linux, Nginx, AWS-oriented deployment, Terraform, and CI/CD workflows.
- **Security posture:** upload validation, replay protection, authorization boundaries, safer file delivery, and defensive backend design.

## Projects That Demonstrate Architecture, Not Just Syntax

### [PhotoBox-API](https://github.com/ALEX-MUTHOMI/PhotoBox-API)

Multi-tenant photography SaaS backend designed to decouple heavy media workflows from the Django application layer.

**Architecture focus:** Django REST Framework coordinates tenant state, quota reservations, billing/webhook integrity, and secure delivery while Cloudflare R2 handles binary storage and Celery workers process asynchronous upload paths.

**Engineering constraints represented in the design:** fast-lane uploads at 5 MB and below, heavy-lane uploads above 5 MB through presigned direct-to-storage tickets, 60-second signed download URLs, idempotent webhook processing, and quota updates protected against race conditions.

**Why this matters:** this is evidence of backend judgment beyond CRUD: tenant isolation, storage architecture, file-security boundaries, async processing, and data consistency under concurrent user activity.

### [DARASA-API](https://github.com/ALEX-MUTHOMI/DARASA-API)

Academic ERP backend foundation for schools, built with a deterministic Docker-first runtime and production-oriented quality gates.

**Architecture focus:** multi-tenant-ready Django project layout, PostgreSQL, Redis, Celery worker/beat, Poetry-managed dependencies, CI diagnostics, security checks, and service-boundary scaffolding for future ERP modules.

**Engineering constraints represented in the design:** reproducible local runtime, isolated service containers, explicit app/runtime layout, diagnostic Make targets, opt-in chaos tests, and separation between academic ERP boundaries and unrelated commercial workflows.

**Why this matters:** this shows platform thinking: the repository is shaped for long-term domain growth, not a single feature demo.

### [RECIPE-APP-API](https://github.com/ALEX-MUTHOMI/RECIPE-APP-API)

Backend API and deployment automation project under the BackToFront Development brand.

**Architecture focus:** Dockerized API delivery, Terraform, AWS deployment thinking, infrastructure automation, and maintainable backend deployment patterns.

**Why this matters:** this connects backend implementation with operational ownership, which is valuable on teams where engineers are expected to understand how services run beyond local development.

## Self-Taught Execution Is Part of the Signal

I built my engineering depth outside a traditional computer science degree path by shipping systems, studying architecture decisions, documenting tradeoffs, and repeatedly pushing projects past the tutorial stage into runtime, deployment, security, and maintainability concerns.

That background matters because it shows independent learning velocity, persistence through ambiguity, and the ability to convert unfamiliar technical problems into working systems without waiting for a formal path to define the next step.

## Technical Depth Recruiters Should Screen For

**Primary language:** Python  
**Backend:** Django, Django REST Framework, Celery  
**Data:** PostgreSQL, Redis  
**Infrastructure:** Docker, Docker Compose, Linux, Nginx, AWS-oriented deployment, Terraform  
**Engineering practices:** REST API design, authentication, authorization, CI/CD, security checks, test automation, documentation, service-boundary design

## Additional Delivery Context

I also build client-facing web systems through BackToFront Development, including portfolio and business websites. Those projects show delivery range, but my core engineering direction is backend systems, API architecture, cloud backend work, and infrastructure automation.

## Recruiter Signal

I am best matched for backend engineering, API engineering, cloud backend, platform, or Python/Django roles where project evidence matters. I bring founder-level ownership, strong independent learning discipline, and hands-on backend architecture experience across real portfolio systems.

Reach me at [muthomialex64@gmail.com](mailto:muthomialex64@gmail.com).
