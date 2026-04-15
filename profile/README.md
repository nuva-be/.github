<p align="center">
  <a href="https://nuva.be">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/badge/NUVA-white?style=for-the-badge&labelColor=white&color=white&logoColor=black">
      <img alt="Nuva" src="https://img.shields.io/badge/NUVA-black?style=for-the-badge&labelColor=black&color=black&logoColor=white" height="40">
    </picture>
  </a>
</p>

<p align="center">
  <strong>AI systems & products for real-world business impact</strong>
</p>

<p align="center">
  <a href="https://nuva.be"><img src="https://img.shields.io/badge/website-nuva.be-blue?style=flat-square" alt="Website"></a>
  <a href="mailto:contact@nuva.be"><img src="https://img.shields.io/badge/contact-contact%40nuva.be-blue?style=flat-square" alt="Contact"></a>
  <img src="https://img.shields.io/badge/location-Belgium-red?style=flat-square" alt="Belgium">
  <img src="https://img.shields.io/badge/hosting-Netlify-00C7B7?style=flat-square&logo=netlify&logoColor=white" alt="Netlify">
  <img src="https://img.shields.io/badge/infra-GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white" alt="GCP">
</p>

---

## Predict — Financial Intelligence Platform

AI-powered platform to extract, structure and analyze financial data.

| Repo | Stack | Live | Description |
|---|---|---|---|
| [`feen-api`](https://github.com/nuva-be/feen-api) | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) | [api.feen.be](https://api.feen.be) | Extraction, matching & classification engine |
| [`feen-app`](https://github.com/nuva-be/feen-app) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/-Next.js-000?style=flat-square&logo=nextdotjs&logoColor=white) | [admin.feen.be](https://admin.feen.be) | Financial intelligence dashboard |
| [`feen-landing`](https://github.com/nuva-be/feen-landing) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) | [feen.be](https://www.feen.be) | Marketing site |
| [`feen-ios`](https://github.com/nuva-be/feen-ios) | ![React Native](https://img.shields.io/badge/-React_Native-61DAFB?style=flat-square&logo=react&logoColor=black) | — | Mobile app — financial data capture |

**Feen DNS map:**

| Subdomain | Target | Service |
|---|---|---|
| [www.feen.be](https://www.feen.be) | Netlify | Landing page |
| [admin.feen.be](https://admin.feen.be) | GCP (Cloud Run) | Dashboard app |
| [api.feen.be](https://api.feen.be) | GCP (Cloud Run) | Backend API |
| [processor.feen.be](https://processor.feen.be) | GCP (Cloud Run) | Document processor |
| [help.feen.be](https://help.feen.be) | GCP (Cloud Run) | Help center |
| [docs.feen.be](https://docs.feen.be) | GCP (Cloud Run) | API documentation |

---

## AI Platform — Core Infrastructure

| Repo | Stack | Description |
|---|---|---|
| [`pixl-ai`](https://github.com/nuva-be/pixl-ai) | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Claude](https://img.shields.io/badge/-Claude-191919?style=flat-square&logo=anthropic&logoColor=white) | AI dev platform — orchestration engine & crew plugin `v11.3.0` |
| [`pixl-kb`](https://github.com/nuva-be/pixl-kb) | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) | Knowledge OS — RAG, entity extraction, knowledge graph &middot; [dashboard](https://pixl-kb.netlify.app) |
| [`pixl-os`](https://github.com/nuva-be/pixl-os) | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) | Agentic company OS — discuss, decide, build, learn |

---

## Internal Tools

| Repo | Stack | Live | Description |
|---|---|---|---|
| [`pixl-web`](https://github.com/nuva-be/pixl-web) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/-Next.js-000?style=flat-square&logo=nextdotjs&logoColor=white) | — | AI website builder |
| [`pixl-seo`](https://github.com/nuva-be/pixl-seo) | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) | — | Automated SEO content engine |
| [`pixl-marketing`](https://github.com/nuva-be/pixl-marketing) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) | [qlame.netlify.app](https://qlame.netlify.app) | AI marketing content generator |
| [`pixl-branding`](https://github.com/nuva-be/pixl-branding) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) | [pixl-branding.netlify.app](https://pixl-branding.netlify.app) | Logo generation & brand assets |
| [`learn-vllm`](https://github.com/nuva-be/learn-vllm) | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) | — | vLLM local AI inference lab |

---

## Client Projects

| Repo | Stack | Live | Client |
|---|---|---|---|
| [`aremis-web`](https://github.com/nuva-be/aremis-web) | ![TS](https://img.shields.io/badge/-TS-3178C6?style=flat-square) ![Next.js](https://img.shields.io/badge/-Next.js-000?style=flat-square) | [aremis.netlify.app](https://aremis.netlify.app) | Aremis — web platform |
| [`aremis-budget`](https://github.com/nuva-be/aremis-budget) | ![TS](https://img.shields.io/badge/-TS-3178C6?style=flat-square) ![Next.js](https://img.shields.io/badge/-Next.js-000?style=flat-square) | [aremisb.netlify.app](https://aremisb.netlify.app) | Aremis — budget estimation widget |
| [`aremis-gsk`](https://github.com/nuva-be/aremis-gsk) | ![Py](https://img.shields.io/badge/-Py-3776AB?style=flat-square) ![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square) ![Next.js](https://img.shields.io/badge/-Next.js-000?style=flat-square) | Docker | Aremis GSK — real estate portfolio optimizer |
| [`pizzaroma`](https://github.com/nuva-be/pizzaroma) | ![TS](https://img.shields.io/badge/-TS-3178C6?style=flat-square) ![Next.js](https://img.shields.io/badge/-Next.js-000?style=flat-square) | [pizzeriaroma-anderlecht.be](https://pizzeriaroma-anderlecht.be) | Pizzaroma — ordering & delivery system |

---

## Deployments

| Platform | Sites |
|---|---|
| **Netlify** | [feen.be](https://www.feen.be) &middot; [pizzeriaroma-anderlecht.be](https://pizzeriaroma-anderlecht.be) &middot; [aremis.netlify.app](https://aremis.netlify.app) &middot; [aremisb.netlify.app](https://aremisb.netlify.app) &middot; [qlame.netlify.app](https://qlame.netlify.app) &middot; [pixl-kb.netlify.app](https://pixl-kb.netlify.app) |
| **GCP (Cloud Run)** | [api.feen.be](https://api.feen.be) &middot; [admin.feen.be](https://admin.feen.be) &middot; [processor.feen.be](https://processor.feen.be) &middot; [help.feen.be](https://help.feen.be) &middot; [docs.feen.be](https://docs.feen.be) &middot; aremis-gsk |

---

## Conventions

| Prefix | Scope |
|---|---|
| `feen-*` | Predict product |
| `pixl-*` | Internal platform & tools |
| `aremis-*` | Aremis client |
| `learn-*` | Courses & learning |

**Branching:** `main` = production &middot; `dev` = staging &middot; `feat/*` = feature branches

---

<p align="center">
  <sub>Built by builders &middot; Ship fast, keep it simple, automate everything</sub>
</p>
