<div align="center">

# Alex Muthomi

**Backend Engineer | Founder, BackToFront Development**  
Python | Django REST Framework | PostgreSQL | Redis | Docker | Cloud Backend Systems

[LinkedIn](https://www.linkedin.com/in/alex-mputhia) | [Email](mailto:muthomialex64@gmail.com) | [GitHub](https://github.com/ALEX-MUTHOMI)

</div>

---

I build backend systems where API design, data integrity, infrastructure, and security need to hold together under real product constraints.

My core work is in Django service architecture, multi-tenant access models, asynchronous processing, secure file workflows, and deployment automation. Through **BackToFront Development**, I translate business requirements into maintainable web systems with a strong backend and infrastructure foundation.

## Backend Focus

- API architecture with Django REST Framework, authentication, authorization, permissions, and service boundaries.
- Distributed workflows with Celery, Redis, idempotent webhooks, background jobs, and direct-to-storage upload paths.
- Data reliability with PostgreSQL, transactional workflows, quota enforcement, row-locking patterns, and tenant-aware access.
- Cloud delivery with Docker, Docker Compose, Linux, Nginx, Terraform, CI/CD, and AWS-oriented deployment patterns.
- Security-conscious backend design around upload validation, replay protection, signed delivery, and authorization boundaries.

## Production Portfolio

### [PhotoBox-API](https://github.com/ALEX-MUTHOMI/PhotoBox-API)

Multi-tenant photography SaaS backend focused on secure media workflows and asynchronous delivery.

- Splits uploads into fast-lane processing for files up to 5 MB and presigned direct-to-storage flows for larger files.
- Uses Cloudflare R2 for object storage while Django coordinates tenant state, quota reservations, signed delivery, and webhook integrity.
- Demonstrates tenant isolation, quota race protection, idempotent webhooks, secure file boundaries, and async processing with Celery.

### [DARASA-API](https://github.com/ALEX-MUTHOMI/DARASA-API)

Academic ERP backend foundation built around deterministic runtime, tenant-readiness, and production-oriented quality gates.

- Docker-first Django runtime with PostgreSQL, Redis, Celery worker/beat, Poetry-managed dependencies, and diagnostic Make targets.
- Structured for service-boundary growth across future ERP modules rather than a single endpoint demo.
- Emphasizes reproducible local execution, isolated service containers, security checks, CI diagnostics, and opt-in chaos tests.

### [RECIPE-APP-API](https://github.com/ALEX-MUTHOMI/RECIPE-APP-API)

Backend API and deployment automation project under the BackToFront Development brand.

- Connects API implementation with Dockerized delivery, Terraform, AWS-oriented deployment design, and infrastructure automation.
- Shows operational ownership beyond local development: configuration repeatability, service deployment, and maintainable backend delivery.

## Engineering Methodology

Backend engineering practice centered on runtime predictability, strict domain boundaries, data integrity, deployment repeatability, and clear technical documentation.

The work is driven by independent research, architecture tradeoff analysis, and building systems that move beyond local demos into runtime, deployment, security, and maintainability concerns.

## Technical Stack

**Backend:** Python, Django, Django REST Framework, Celery  
**Data:** PostgreSQL, Redis  
**Infrastructure:** Docker, Docker Compose, Linux, Nginx, Terraform, AWS-oriented deployment  
**Practices:** REST API design, authentication, authorization, CI/CD, security checks, test automation, documentation

## Role Fit

Backend engineering, API engineering, cloud backend, platform, and Python/Django roles where autonomous system design and project evidence matter.

**Contact:** [muthomialex64@gmail.com](mailto:muthomialex64@gmail.com)
