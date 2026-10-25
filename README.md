<div align="center">

# Redn Alsidrah

### Cloud Adoption · Architecture · Engineering · Applied AI

Riyadh, Saudi Arabia

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rdan-alsadrah/)
[![Website](https://img.shields.io/badge/ralsadrah.xyz-475569?style=flat-square&logo=aboutdotme&logoColor=white)](https://ralsadrah.xyz/)
[![GitHub](https://img.shields.io/badge/GitHub-R3dn-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/R3dn)

</div>

---

I work at the intersection of **cloud architecture, engineering, and customer-facing consulting** — translating business and regulatory requirements into designs that can actually be built, sized, and operated.

My focus areas:

- **Sovereign cloud adoption (Saudi market)** — architecture and compliance alignment with CST, NCA ECC, and NDMO data residency, plus connectivity, DR, and managed-service design considerations.
- **Cloud economics** — workload sizing, provider comparison, and budgetary estimation that make technical solutions commercially practical.
- **Engineering automation** — CLI tools, health checks, and inventory/audit utilities that take repetitive infrastructure work off engineers' hands.
- **Applied AI infrastructure** — LLM inference sizing, GPU selection, and API integration, grounded in the same cost and capacity discipline.

---

### Featured Projects

#### [infra-check](https://github.com/R3dn/infra-check) — one command, full infrastructure health

A pip-installable CLI that verifies the whole chain — DNS → TCP → TLS → HTTP → certificate expiry → latency → https redirect — in one pass, with a clear verdict (`HEALTHY` / `DEGRADED` / `UNHEALTHY`), JSON output, and CI-friendly exit codes that separate "pipeline misconfigured" from "site down." Ships as a reusable GitHub Action; the pure-logic engine is fully unit-tested and the suite runs offline.

```bash
pip install infra-health-check
infra-check example.com --json
```

#### [saudi-cloud-cost-estimator-cli](https://github.com/R3dn/saudi-cloud-cost-estimator-cli) — Saudi cloud costs, with price provenance on every line

Compares compute, storage, database, Kubernetes, network, and full TCO across the clouds you can actually use in or near Saudi Arabia — Oracle (Riyadh/Jeddah), Google (Dammam), AWS (Bahrain), Azure (UAE) — priced in **SAR with 15% VAT**, straight from official pricing APIs. Every number is tagged `live`, `fallback`, or `assumption`; the tool never dresses an approximation up as an official price.

```bash
npm install -g saudi-cloud-cost-estimator-cli
saudi-cloud-costs compute compare -s medium
```

#### [dockerized-3tier-app](https://github.com/R3dn/dockerized-3tier-app) — sovereign cloud workload governance, running locally

A working 3-tier application (React · FastAPI · PostgreSQL behind Nginx) that simulates enterprise workload migration under Saudi regulatory frameworks — NDMO data residency, NCA ECC compliance scoring, and CST cloud classification (Class A/B/C). Bilingual AR/EN interface, container hardening throughout (non-root users, isolated DB tier, security headers at the proxy).

```bash
docker compose up --build -d
```

---

### Technical Focus

| Area | Tools & Platforms |
| --- | --- |
| Cloud & Infrastructure | Azure · AWS · Google Cloud · Oracle Cloud · SITE Cloud · VMware (vSphere, vCenter, Cloud Director, NSX, vSAN, SRM) |
| Sovereign Cloud | CST / NCA ECC / NDMO alignment · data residency · DR & backup design · connectivity |
| Automation & Scripting | Python · PowerShell / PowerCLI · Ansible · Bash · REST APIs |
| Containers & Platforms | Docker · Kubernetes · OpenShift · Linux · Nginx |
| AI & LLM Engineering | LLM inference sizing · GPU capacity planning · RAG fundamentals · embeddings & vector databases |
| Cloud Economics | Workload sizing · FinOps principles · budgetary estimation · resource optimization |

*Cloud platforms and tooling above reflect my professional background; the featured projects carry the repository-level evidence.*

---

### Currently Working On

- Extending [infra-check](https://github.com/R3dn/infra-check) toward security-header and redirect-chain auditing
- Growing the [cost estimator](https://github.com/R3dn/saudi-cloud-cost-estimator-cli) toward reserved/committed-use pricing comparisons
- Exploring LLM inference capacity tooling — GPU sizing grounded in real regional catalog data

---

<div align="center">

**Get in touch**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rdan-alsadrah/)
&nbsp; [![Website](https://img.shields.io/badge/ralsadrah.xyz-475569?style=flat-square&logo=aboutdotme&logoColor=white)](https://ralsadrah.xyz/)

</div>

<div align="center"><em>Open to collaborations on sovereign cloud adoption, FinOps tooling, and AI infrastructure.</em></div>
