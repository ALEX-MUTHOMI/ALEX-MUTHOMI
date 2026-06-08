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

I build backend systems where API design, data integrity, infrastructure, and security have to work together under real product constraints.

My core work is Django service architecture, multi-tenant access models, asynchronous processing, secure file workflows, event-driven foundations, and deployment automation. Through **BackToFront Development**, I translate business requirements into maintainable web systems with strong backend and infrastructure foundations.

**Best fit:** backend engineering, API engineering, cloud backend, platform-adjacent backend, and Python/Django roles where project evidence matters.

## Backend Engineering Scope

- **API architecture:** DRF APIs, authentication, authorization, validation boundaries, domain services, selectors, and policy layers.
- **Data integrity:** tenant isolation, quota ledgers, idempotency, row locking, replay protection, event contracts, and failure recovery.
- **Runtime delivery:** Docker-first services, Compose isolation, Linux/Nginx patterns, CI/CD checks, Make targets, Terraform, and AWS-oriented deployment.
- **Security posture:** signed delivery, HMAC webhooks, upload hardening, PII-safe payloads, red-team tests, toxiproxy/chaos checks, and reproducible diagnostics.

## Production Portfolio

### [PhotoBox-API](https://github.com/ALEX-MUTHOMI/PhotoBox-API)

Multi-tenant photography SaaS backend for secure media ingestion, object-storage delivery, quota integrity, and asynchronous processing.

- **Backend design:** DRF owns tenant state, gallery access, quota reservations, signed delivery, billing/webhook integrity, and Celery-backed processing.
- **System design:** upload flow separates small-file fast-lane processing from direct-to-R2 heavy-lane uploads, keeping large binary traffic outside the Django request path.
- **Security and reliability:** quota accounting is modeled as a ledger with row locking, race protection, idempotent webhooks, payload-hash replay defense, signed URL TTLs, MIME/path validation, decompression-bomb checks, and R2 outage behavior.
- **Reviewer focus:** `gallery` | `ingestion` | `billing` | `webhooks` | security tests | API docs | production verification notes

<br/>

---

### [DARASA-API](https://github.com/ALEX-MUTHOMI/DARASA-API)

Academic ERP backend foundation built around schema tenancy, deterministic runtime, event contracts, curriculum governance, grading workflows, and reporting readiness.

- **Backend design:** tenant provisioning, academics, curriculum, events, grading, portals, core identity, selectors, services, and policies are separated into explicit domain boundaries.
- **System design:** event backbone includes payload contracts, validators, producer authorization, idempotency keys, retry policy, dead-letter classification, priority ordering, partition keys, and audit hashing.
- **Domain algorithms:** curriculum and grading modules cover impact analysis, regulatory notice classification, grading compilation, report readiness, role analytics, PII-safe correction payloads, and report snapshot integrity.
- **Runtime reliability:** Docker-first runtime with PostgreSQL, Redis, Celery worker/beat, Poetry dependencies, service containers, Make targets, CI/security gates, opt-in chaos tests, toxiproxy config, and reproducible runtime checks.
- **Reviewer focus:** `tenant` | `academics` | `curriculum` | `events` | `grading` | security docs | testing strategy | architecture phases

<br/>

---

### [RECIPE-APP-API](https://github.com/ALEX-MUTHOMI/RECIPE-APP-API)

Backend API and deployment automation project under the BackToFront Development brand.

- **Backend design:** authenticated recipe, tag, ingredient, image-upload, and user-management APIs with DRF, PostgreSQL, user-scoped querysets, nested serializers, filtering, and API tests.
- **System design:** Docker/Compose workflows, wait-for-database orchestration, Nginx proxy configuration, deploy-oriented service files, and repeatable local/runtime setup.
- **Reviewer focus:** user isolation | serializer design | API tests | image upload handling | Docker deployment baseline

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
