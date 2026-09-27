# Rahul Nainala

**Senior Full-Stack / Senior Software Engineer** · Hyderabad or Bengaluru · hybrid or on-site

I build the whole path a request takes: the interface, the APIs, licensing and billing, and the machines underneath, from GPU servers to a Raspberry Pi. 4+ years full-time since June 2022, each job one layer deeper.

**[rahulnainala.com](https://www.rahulnainala.com)** · [LinkedIn](https://linkedin.com/in/rahulnainala) · nainalarahul2k1@gmail.com

---

## Now — Frontend Lead & Full-Stack Engineer, Quantum AI Global (Dec 2025 –)

A quantum computing platform used by universities, shipped as three products from one codebase.

- **One codebase, three products.** Cloud, Academia and a Raspberry Pi edge appliance from one core instead of three forks. Extracted a shared core layer across 4 backend services and deleted ~3,000 lines of duplicated code.
- **Real quantum hardware, never run twice.** Execution on IBM Quantum as async submit/poll that never submits a job twice, plus a CUDA-Q error-correction composer, a noise composer and tensor-network simulation.
- **Licensing and billing, end to end.** Product catalog, per-product licenses with feature bits, org plans, org-scoped API keys and Razorpay checkout with autopay.
- **Infrastructure.** The edge appliance on real Raspberry Pi hardware, a GPU dev server, self-hosted CI on GHCR, Redis rate limiting across replicas, 3-tier staging and Helm charts for GPU node pools. Scaled to 50 concurrent students.
- Hardened auth and CORS across 4 services and added secret scanning to CI.

[Read the case study →](https://www.rahulnainala.com/work/platform)

## Before

**Rubus Digital** — Software Engineer II · Jun 2024 – Nov 2025
- Led a monolith → micro-frontend migration across 4 teams with Webpack 5 Module Federation: **−40% deployment complexity**.
- Built a CLI that scaffolds a new micro-frontend in under 30 seconds: new-team onboarding **2 days → 15 minutes**.
- Built a Three.js 3D dashboard with live IoT data, rendering in **under 2s at 1080p**; a JSON-schema config system cut developer dependency by **60%**.
- Migrated the codebase to TypeScript and raised Jest coverage to 75%.

**Casp AI** — Senior Software Engineer (Contract) · Jul 2023 – Jun 2024
- Built the real-time AI chat UI in React: token-by-token streaming, abortable requests, retry on socket drops.
- Moved the build to Vite: CI from **~8 min to under 5** (~40% faster).

**Hexagon Capability Center India** — Software Engineer · Jun 2022 – Jul 2023 (intern from Oct 2021)
- React dashboards for engineering teams: **−30%** render load time.
- Set the frontend testing standard for the dashboards group: **−20%** production defects.
- Fixed N+1 queries: **−40%** API response time.

## Projects

| Project | What it is | Number |
|---|---|---|
| [Quantum Computing Platform](https://www.rahulnainala.com/work/platform) | One codebase shipped to the cloud, to universities and to a Raspberry Pi edge appliance | 3 products from one codebase |
| [Micro-Frontend Platform Migration](https://www.rahulnainala.com/projects/micro-frontend-migration) | A React monolith split into independently deployable micro-frontends across 4 teams | 15 min onboarding, down from 2 days |
| [3D Asset Dashboard](https://www.rahulnainala.com/projects/3d-asset-dashboard) | Three.js workspace with live IoT data overlays, configured by JSON schema | <2s to render at 1080p |
| [Dev Wear](https://dev-wear.vercel.app) · [code](https://github.com/rahulnainala/devWear) | Full-stack e-commerce for developer apparel: auth, persistent cart, real checkout | Live |

## Stack

- **Frontend** React · Next.js · TypeScript · Three.js · Tailwind CSS · Webpack 5 Module Federation · Vite
- **Backend** Python · FastAPI · Node.js · REST · WebSockets · async job processing
- **Data** PostgreSQL · Redis · SQLite
- **Infrastructure** Docker · GitHub Actions (self-hosted runners) · GHCR · Kubernetes / Helm · Linux · Raspberry Pi · NVIDIA GPU servers
- **Quantum** CUDA-Q · IBM Quantum · OpenQASM
- **Quality** Jest · Pytest · secret scanning (gitleaks)

## Learning now

Kubernetes (CKA, in progress) · NeetCode 150 (in progress) · *Designing Data-Intensive Applications*

---

B.Tech, Computer Science & Engineering, Lovely Professional University (2022) · Runner-up, PRAGNYA Innovation Event (2nd of 40+ teams)
