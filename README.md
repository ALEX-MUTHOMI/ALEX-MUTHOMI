<div align="center">

# Alex Muthomi

**Backend Engineer and Founder of BackToFront Development**  
Python | Django REST Framework | Cloud Backend Architecture | Infrastructure Automation

[LinkedIn](https://www.linkedin.com/in/alex-mputhia) | [Email](mailto:muthomialex64@gmail.com) | [GitHub](https://github.com/ALEX-MUTHOMI)

</div>

---

Architecture and development of backend platforms where API boundaries, data integrity, infrastructure, and security converge. Specialized in Django service design, multi-tenant access models, asynchronous task processing, secure file workflows, and deployment automation.

Through **BackToFront Development**, business requirements are translated into maintainable web systems with a primary emphasis on backend reliability, API design, and deployment discipline.

## Core Technical Domain

| Domain | Practical Scope |
| --- | --- |
| **API Architecture** | Django REST Framework, authentication, authorization, permissions, domain boundaries, and service-level validation |
| **Distributed Workflows** | Celery, Redis, asynchronous jobs, idempotent webhooks, direct-to-storage upload flows, and background processing |
| **Data Reliability** | PostgreSQL, transactional workflows, quota enforcement, row-locking patterns, and tenant-aware access control |
| **Cloud Delivery** | Docker, Docker Compose, Linux, Nginx, AWS-oriented deployment, Terraform, and CI/CD workflows |
| **Security Posture** | Upload validation, replay protection, authorization boundaries, signed file delivery, and defensive API design |

## Production Portfolio

### [PhotoBox-API](https://github.com/ALEX-MUTHOMI/PhotoBox-API)

Multi-tenant photography SaaS backend designed to decouple heavy media workflows from the Django application layer.

- **Architecture focus:** Django REST Framework coordinates tenant state, quota reservations, billing/webhook integrity, and secure delivery while Cloudflare R2 handles object storage and Celery workers process asynchronous upload paths.
- **Engineering constraints:** fast-lane processing for uploads of 5 MB or smaller; heavy-lane uploads above 5 MB through presigned direct-to-storage tickets; 60-second signed download URLs; idempotent webhook processing; quota updates protected against race conditions.
- **Engineering value:** tenant isolation, storage architecture, secure file boundaries, asynchronous processing, and data consistency under concurrent user activity.

### [DARASA-API](https://github.com/ALEX-MUTHOMI/DARASA-API)

Academic ERP backend foundation for schools, built with a deterministic Docker-first runtime and production-oriented quality gates.

- **Architecture focus:** multi-tenant-ready Django project layout, PostgreSQL, Redis, Celery worker/beat, Poetry-managed dependencies, CI diagnostics, security checks, and service-boundary scaffolding for future ERP modules.
- **Engineering constraints:** reproducible local runtime, isolated service containers, explicit app/runtime layout, diagnostic Make targets, opt-in chaos tests, and separation between academic ERP boundaries and unrelated commercial workflows.
- **Engineering value:** long-term platform structure, maintainable runtime boundaries, and domain growth beyond a single feature demo.

### [RECIPE-APP-API](https://github.com/ALEX-MUTHOMI/RECIPE-APP-API)

Backend API and deployment automation project under the BackToFront Development brand.

- **Architecture focus:** Dockerized API delivery, Terraform, AWS-oriented deployment design, infrastructure automation, and repeatable backend deployment patterns.
- **Engineering value:** backend implementation connected to operational ownership, service deployment, and infrastructure automation.

## Engineering Methodology

Backend engineering practice centered on runtime predictability, strict domain boundaries, data integrity, deployment repeatability, and clear technical documentation.

Execution is driven by independent research, architecture tradeoff analysis, and building systems that move beyond local demos into runtime, deployment, security, and maintainability concerns.

## Technical Stack

| Area | Tools and Practices |
| --- | --- |
| **Primary language** | Python |
| **Backend frameworks** | Django, Django REST Framework, Celery |
| **Data and cache** | PostgreSQL, Redis |
| **Infrastructure** | Docker, Docker Compose, Linux, Nginx, AWS-oriented deployment, Terraform |
| **Engineering practices** | REST API design, authentication, authorization, CI/CD, security checks, test automation, documentation, service-boundary design |

## BackToFront Development

Full-stack delivery and consulting for commercial clients, including portfolio websites, business web systems, and automation-focused builds. The delivery range is broad, but the core technical direction remains backend systems, API architecture, cloud backend work, and infrastructure automation.

## Role Alignment

Targeted toward backend engineering, API engineering, platform engineering, cloud backend, and Python/Django roles where autonomous system design and project evidence matter.

**Contact:** [muthomialex64@gmail.com](mailto:muthomialex64@gmail.com)
