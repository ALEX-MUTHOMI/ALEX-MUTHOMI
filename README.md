<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0d1117&height=170&section=header&text=Alex%20Muthomi&fontSize=66&fontAlignY=34&fontColor=70d1f4&desc=Backend%20Engineer%20%7C%20Founder%20of%20BackToFront%20Development&descAlignY=68&descAlign=50&animation=fadeIn" />
</div>

<p align="center">
  <a href="https://www.linkedin.com/in/alex-mputhia"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:muthomialex64@gmail.com?subject=Backend%20Engineering%20Opportunity"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://github.com/ALEX-MUTHOMI"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-111827?style=flat-square&logo=python" />
  <img src="https://img.shields.io/badge/Django-111827?style=flat-square&logo=django" />
  <img src="https://img.shields.io/badge/DRF-111827?style=flat-square" />
  <img src="https://img.shields.io/badge/PostgreSQL-111827?style=flat-square&logo=postgresql" />
  <img src="https://img.shields.io/badge/Redis-111827?style=flat-square&logo=redis" />
  <img src="https://img.shields.io/badge/Docker-111827?style=flat-square&logo=docker" />
  <img src="https://img.shields.io/badge/Terraform-111827?style=flat-square&logo=terraform" />
</p>

---

## Backend Systems Profile

I build backend systems where API design, data integrity, infrastructure, and security have to hold together under real product constraints.

My core work is Django service architecture, multi-tenant access models, asynchronous processing, secure file workflows, event-driven foundations, and deployment automation. Through **BackToFront Development**, I translate business requirements into maintainable web systems with strong backend and infrastructure foundations.

**Primary direction:** backend engineering, API engineering, cloud backend systems, platform foundations, and Python/Django roles where project evidence matters.

## Systems Engineering Scope

- **Service architecture:** Django REST Framework APIs with authentication, authorization, permissions, selectors/services/policies layers, validation boundaries, and maintainable domain structure.
- **Workflow architecture:** Celery, Redis, idempotent webhooks, event contracts, retry/backoff logic, direct-to-storage upload paths, and background processing.
- **Data integrity:** PostgreSQL-backed workflows, tenant-aware access controls, quota enforcement, row-locking patterns, replay protection, and race-condition handling.
- **Platform delivery:** Docker-first runtime, Docker Compose service isolation, Linux, Nginx, Terraform, CI/CD checks, Make targets, and AWS-oriented deployment patterns.
- **Security and resilience:** upload validation, signed delivery, HMAC verification, replay windows, PII-safe payloads, red-team security tests, toxiproxy/chaos checks, and reproducible diagnostics.

## Production Portfolio

### [PhotoBox-API](https://github.com/ALEX-MUTHOMI/PhotoBox-API)

Multi-tenant photography SaaS backend focused on secure media ingestion, object-storage delivery, quota integrity, and asynchronous processing.

- Splits media ingestion into fast-lane processing for files up to 5 MB and heavy-lane presigned direct-to-R2 uploads for larger files, keeping heavy binary traffic out of the Django application path.
- Uses Cloudflare R2 as the object-storage vault while Django coordinates tenant state, quota reservations, signed delivery, gallery permissions, and webhook integrity.
- Enforces storage accounting with row-locking patterns, quota race protection, idempotent webhook handling, payload-hash replay defense, and failure paths that preserve auditability.
- Includes security and resilience coverage for cross-tenant access, decompression bombs, MIME/path validation, SSRF-style risks, HMAC verification, replay windows, signed URL TTLs, and R2 outage behavior.
- Ships with implementation docs, API documentation, production verification notes, red-team matrices, CI scripts, smoke/integration/security gates, and toxiproxy-based resilience checks.

### [DARASA-API](https://github.com/ALEX-MUTHOMI/DARASA-API)

Academic ERP backend foundation built around schema tenancy, deterministic runtime, event contracts, curriculum governance, grading workflows, and reporting readiness.

- Uses a Docker-first Django runtime with PostgreSQL, Redis, Celery worker/beat, Poetry-managed dependencies, service containers, diagnostic Make targets, and explicit developer environment documentation.
- Models a school ERP as tenant-aware domains: tenant provisioning, academics, curriculum, events, grading, portals, core identity, selectors, services, and policies.
- Includes event-system work around event contracts, payload validators, producer authorization, idempotency keys, retry policy, dead-letter classification, priority ordering, partition keys, and audit hashing.
- Goes beyond CRUD with deterministic algorithms for curriculum impact analysis, regulatory notice classification, grading compilation, report readiness, role analytics, PII-safe correction payloads, and report snapshot integrity.
- Emphasizes production posture through security models, testing strategy, phase boundaries, CI/security gates, opt-in chaos tests, toxiproxy config, and reproducible runtime checks.

### [RECIPE-APP-API](https://github.com/ALEX-MUTHOMI/RECIPE-APP-API)

Backend API and deployment automation project under the BackToFront Development brand.

- Implements authenticated recipe, tag, ingredient, image-upload, and user-management APIs with Django REST Framework and PostgreSQL.
- Uses Docker and Compose for local/deploy workflows, a wait-for-database command, Nginx proxy configuration, and production-oriented deployment files.
- Demonstrates backend fundamentals: user-scoped querysets, nested serializer workflows, filtering by tags/ingredients, image upload handling, and API test coverage.
- Serves as the deployment baseline in the portfolio, connecting application code with containerized service delivery and infrastructure automation.

## Technical Depth

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,django,postgres,redis,docker,aws,terraform,linux,nginx,githubactions" height="42" />
</p>

**Backend:** Python, Django, Django REST Framework, Celery  
**Data:** PostgreSQL, Redis  
**Infrastructure:** Docker, Docker Compose, Linux, Nginx, Terraform, AWS-oriented deployment  
**Practices:** REST API design, authentication, authorization, CI/CD, security checks, test automation, red-team review, technical documentation

## Engineering Methodology

Backend engineering practice centered on runtime predictability, strict domain boundaries, data integrity, deployment repeatability, resilience testing, and clear technical documentation.

The work is driven by independent research, architecture tradeoff analysis, and building systems that move beyond local demos into runtime, deployment, security, maintainability, and operational failure-mode concerns.

## GitHub Activity

<div align="center">
  <img src="https://streak-stats.demolab.com?user=ALEX-MUTHOMI&locale=en&mode=weekly&theme=tokyonight&hide_border=true&border_radius=5" width="92%" alt="GitHub streak graph" />
  <br/><br/>
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=ALEX-MUTHOMI&bg_color=0d1117&color=70d1f4&line=70d1f4&point=FFFFFF&hide_border=true" width="92%" alt="GitHub activity graph" />
</div>

<br/>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0d1117&height=90&section=footer" />
</div>
