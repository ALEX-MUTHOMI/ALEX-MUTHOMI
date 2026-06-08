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

**Backend engineer building Django/DRF systems where API architecture, tenant-safe data models, async workflows, security, and runtime reliability have to hold together under real product constraints.**

- **What I build:** multi-tenant APIs, secure file-ingestion pipelines, Celery-backed workflows, webhook/event boundaries, quota ledgers, and deployment-ready backend services.
- **How I engineer:** explicit domain boundaries, permission-first access models, idempotent state transitions, failure-aware data integrity, reproducible runtime setup, and security-focused test coverage.
- **Business context:** through **BackToFront Development**, I translate product requirements into maintainable backend systems with clear architecture, operational constraints, and reviewable engineering evidence.

**Recruiter fit:** backend engineering, API engineering, Python/Django, cloud backend, platform-adjacent backend, and systems-oriented product engineering roles.

## Backend + Systems Positioning

I am best evaluated as a backend engineer with strong systems-engineering range: I design APIs, data models, async workflows, tenant boundaries, and runtime foundations with failure modes in mind.

- **Backend engineering:** Django REST Framework APIs, authentication, authorization, validation boundaries, domain services, selectors, and policy layers.
- **Distributed-system patterns:** Celery/Redis workers, event contracts, webhook ingestion, object-storage handoff, idempotency, replay protection, retry/backoff paths, and dead-letter handling.
- **DDD-style boundaries:** tenant, gallery, ingestion, billing, curriculum, grading, events, and identity are modeled as explicit domains rather than controller-heavy feature folders.
- **Production readiness:** Docker-first services, Compose isolation, Linux/Nginx patterns, CI/security gates, Make targets, Terraform, AWS-oriented deployment, and reproducible diagnostics.

## Production Portfolio

### [PhotoBox-API](https://github.com/ALEX-MUTHOMI/PhotoBox-API)

**Scope:** multi-tenant photography SaaS backend for secure media ingestion, object-storage delivery, quota integrity, signed access, billing events, and asynchronous processing.
- **Backend architecture:** DRF coordinates tenant state, gallery access, quota reservations, signed delivery, billing/webhook integrity, and Celery-backed post-processing.
- **Distributed-system patterns:** small uploads use API validation plus worker handoff; large uploads use presigned direct-to-R2 tickets so Django does not carry heavy binary traffic.
- **Data integrity:** storage accounting is handled as a quota ledger with row locking, race protection, idempotent transitions, payload-hash replay defense, and audit-friendly failure paths.
- **Security/reliability:** covers cross-tenant access, MIME/path validation, decompression-bomb checks, HMAC verification, replay windows, signed URL TTLs, webhook ghost keys, and R2 outage behavior.
- **Recruiter scan:** `gallery` | `ingestion` | `billing` | `webhooks` | Celery | Redis | Cloudflare R2 | security tests | API docs

---

### [DARASA-API](https://github.com/ALEX-MUTHOMI/DARASA-API)

**Scope:** academic ERP backend foundation for schema tenancy, curriculum governance, grading workflows, event contracts, tenant-scoped access, reporting readiness, and deterministic runtime behavior.
- **Backend architecture:** tenant provisioning, academics, curriculum, events, grading, portals, core identity, selectors, services, and policies are separated into domain-owned boundaries.
- **Distributed-system patterns:** the event backbone is application-level and broker-ready, with payload contracts, producer allowlists, idempotency keys, retry policy, dead-letter classification, priority ordering, partition keys, and audit hashing.
- **Domain design:** curriculum and grading workflows use deterministic algorithms for impact analysis, regulatory notice classification, grading compilation, report readiness, role analytics, correction safety, and report snapshot integrity.
- **Runtime reliability:** Docker-first stack with PostgreSQL, Redis, Celery worker/beat, Poetry dependencies, service containers, Make targets, CI/security gates, opt-in chaos tests, toxiproxy config, and reproducible checks.
- **Recruiter scan:** `tenant` | `academics` | `curriculum` | `events` | `grading` | DDD-style boundaries | event backbone | security docs | testing strategy

---

### [RECIPE-APP-API](https://github.com/ALEX-MUTHOMI/RECIPE-APP-API)

**Scope:** backend API and deployment automation baseline under the BackToFront Development brand.
- **Backend architecture:** authenticated recipe, tag, ingredient, image-upload, and user-management APIs with DRF, PostgreSQL, user-scoped querysets, nested serializers, filtering, and API tests.
- **Runtime design:** Docker/Compose workflows, wait-for-database orchestration, Nginx proxy configuration, deploy-oriented service files, and repeatable local/runtime setup.
- **Recruiter scan:** user isolation | serializer design | API tests | image upload handling | Docker deployment baseline

## Engineering Operating Model

<p align="center">
  <img src="https://img.shields.io/badge/API%20Architecture-0d1117?style=for-the-badge&logo=django&logoColor=70d1f4" />
  <img src="https://img.shields.io/badge/Data%20Integrity-0d1117?style=for-the-badge&logo=postgresql&logoColor=70d1f4" />
  <img src="https://img.shields.io/badge/Async%20Workflows-0d1117?style=for-the-badge&logo=celery&logoColor=70d1f4" />
  <img src="https://img.shields.io/badge/Runtime%20Reliability-0d1117?style=for-the-badge&logo=docker&logoColor=70d1f4" />
</p>

I do not treat backend work as endpoint wiring. I design the API surface, domain boundaries, async execution path, data integrity rules, and deployment runtime as one system.

- **API layer:** Python, Django, DRF, authentication, authorization, serializers, permissions, validation, service boundaries, selectors, and policy checks.
- **Workflow layer:** Celery, Redis, event contracts, webhook ingestion, idempotency keys, retry/backoff paths, dead-letter handling, and replay-safe processing.
- **Data layer:** PostgreSQL, tenant isolation, row locking, quota ledgers, audit trails, schema discipline, and failure-aware state transitions.
- **Runtime layer:** Docker, Docker Compose, Linux, Nginx, CI/CD gates, Make targets, Terraform, AWS-oriented deployment patterns, and reproducible diagnostics.
- **Review layer:** security checks, red-team scenarios, test automation, production-readiness notes, architecture documentation, and failure-mode analysis.

## Core Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,django,postgres,redis,docker,aws,terraform,linux,nginx,githubactions" height="42" />
</p>

**Primary:** Python, Django REST Framework, PostgreSQL, Redis, Celery, Docker<br/>
**Infrastructure:** Docker Compose, Linux, Nginx, Terraform, AWS-oriented deployment<br/>
**Engineering focus:** backend architecture, distributed-system patterns, DDD-style boundaries, secure file workflows, event-driven foundations, CI/security gates, and technical documentation

## Build Cadence

<div align="center">
  <sub>Public activity reflects continuous backend systems work, architecture documentation, tests, and project hardening across the portfolio.</sub>
  <br/><br/>
  <img src="https://streak-stats.demolab.com?user=ALEX-MUTHOMI&locale=en&mode=weekly&theme=tokyonight&hide_border=true&border_radius=5" width="92%" alt="GitHub streak graph" />
  <br/><br/>
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=ALEX-MUTHOMI&bg_color=0d1117&color=70d1f4&line=70d1f4&point=FFFFFF&hide_border=true" width="92%" alt="GitHub activity graph" />
</div>

<br/>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0d1117&height=90&section=footer" />
</div>
