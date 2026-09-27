# 👋 Hey, I'm Giulio Garofalo

**Software engineer · Fractional CTO · Growth engineer**
Licensed *Ingegnere dell'Informazione* (Italy, Sez. A) · 11 years between enterprise consulting and my own products.

I build products end-to-end and take responsibility for all of it: architecture, team, release, and what each technical choice actually costs.
Marketing background, systems-thinking habit, and a mild addiction to weird technologies.

🎓 MSc in Management Engineering (LM-31): done, finally
🏛️ Licensed Information Engineer: September 2026 session
👨‍🏫 Teaching Computer Science in an Italian technical high school, because explaining things well is the real test
🧠 SEO, GEO, code and AI, mixed until things scale
💡 From civic tech to SaaS, I've touched everything except COBOL. Still time.

---

## 🔭 What I'm building

### 🧠 [ShopBrain SRL](https://shopbrain.store): founder & CTO *(startup innovativa)*
A family of SaaS products designed and built in-house, all on one shared infrastructure: Stripe billing, SDKs on npm/PyPI, multi-database PostgreSQL, containerized deploys, integration tests on real databases.

| Product | What it does |
|---|---|
| 🛍️ **[ShopBrain](https://shopbrain.store)** | Conversational assistant for e-commerce that answers from the real catalog data. Shopify, WooCommerce, on site, WhatsApp, Telegram |
| 📅 **[BookBrain](https://bookbrain.it)** | Online bookings and calendars, with an embeddable widget for any site |
| 📦 **[ShipBrain](https://shipbrain.it)** | Multi-tenant shipment tracking, with an MCP server built in |
| 🌐 **[SiteBrain](https://sitebrain.it)** | Sites for micro-businesses, regenerated from a URL on a prefab design system |

RAG and agents on domain data with **mandatory source citation**, because that is what makes an output verifiable instead of merely plausible.

### 🚀 [GrowFlow Studio](https://growflow.studio): independent tech consulting
SEO & **GEO** (generative engine optimization), design systems, headless CMS, e-commerce.
Structured data and entity knowledge graphs, built to be *cited* by generative engines, not just indexed.

### 🏛️ [OpenLegis](https://openlegis.it): civic tech / OSINT
A knowledge graph of how Italian and EU laws relate to each other, fed by connectors to official sources: Normattiva, Camera & Senato, EUR-Lex, Gazzetta Ufficiale, Corte Costituzionale, Cassazione, CKAN, Eurostat.
The connectors are open source and published as MCP servers (see below).

---

## 📦 Open source & packages
Everything ships under [**@growflowstudio**](https://www.npmjs.com/~growflowstudio) on npm and [**growflowstudio**](https://pypi.org/user/growflowstudio/) on PyPI.

**🏛️ Civic tech: MCP servers**
| Package | | |
|---|---|---|
| [**republic-mcp**](https://github.com/giuliogarofalo/RepublicMCP) | [![npm](https://img.shields.io/npm/v/republic-mcp?logo=npm&label=npm)](https://www.npmjs.com/package/republic-mcp) | Italian Parliament open data: SPARQL tools over the official Camera and Senato endpoints, plus OpenPolis data (votes, attendance, decrees) |
| [**open-parlamento-mcp**](https://github.com/giuliogarofalo/open-parlamento-mcp) | [![PyPI](https://img.shields.io/pypi/v/open-parlamento-mcp?logo=pypi&logoColor=white&label=pypi)](https://pypi.org/project/open-parlamento-mcp/) | Italian law (Constitution and codes, via LightRAG), EU law (EUR-Lex), parliamentary bills, amendment relations (Normattiva), case law, Eurostat, Gazzetta Ufficiale, CKAN |

**💳 [GrowFlow Billing](https://github.com/giuliogarofalo/growflow-billing)**: the subscription, checkout and invoicing layer behind every *Brain product
| Package | |
|---|---|
| [`@growflowstudio/growflowbilling-client`](https://www.npmjs.com/package/@growflowstudio/growflowbilling-client) | [![npm](https://img.shields.io/npm/v/@growflowstudio/growflowbilling-client?logo=npm&label=npm)](https://www.npmjs.com/package/@growflowstudio/growflowbilling-client) Node/TS client |
| [`growflowbilling-client`](https://pypi.org/project/growflowbilling-client/) | [![PyPI](https://img.shields.io/pypi/v/growflowbilling-client?logo=pypi&logoColor=white&label=pypi)](https://pypi.org/project/growflowbilling-client/) Python client ([docs](https://docs.growflow.studio/billing-client)) |
| [`@growflowstudio/growflowbilling-admin-core`](https://www.npmjs.com/package/@growflowstudio/growflowbilling-admin-core) | [![npm](https://img.shields.io/npm/v/@growflowstudio/growflowbilling-admin-core?logo=npm&label=npm)](https://www.npmjs.com/package/@growflowstudio/growflowbilling-admin-core) Headless admin: API client, React Query hooks, types |
| [`@growflowstudio/growflowbilling-admin-ui`](https://www.npmjs.com/package/@growflowstudio/growflowbilling-admin-ui) | [![npm](https://img.shields.io/npm/v/@growflowstudio/growflowbilling-admin-ui?logo=npm&label=npm)](https://www.npmjs.com/package/@growflowstudio/growflowbilling-admin-ui) shadcn/ui admin pages, forms and tables |

**📅 [GrowFlow Booking](https://github.com/giuliogarofalo/growflow-booking)**: the engine behind BookBrain
| Package | |
|---|---|
| [`@growflowstudio/growflowbooking-widget`](https://www.npmjs.com/package/@growflowstudio/growflowbooking-widget) | [![npm](https://img.shields.io/npm/v/@growflowstudio/growflowbooking-widget?logo=npm&label=npm)](https://www.npmjs.com/package/@growflowstudio/growflowbooking-widget) React components and standalone embed |
| [`@growflowstudio/growflowbooking-client`](https://www.npmjs.com/package/@growflowstudio/growflowbooking-client) | [![npm](https://img.shields.io/npm/v/@growflowstudio/growflowbooking-client?logo=npm&label=npm)](https://www.npmjs.com/package/@growflowstudio/growflowbooking-client) Node/TS client |
| [`growflowbooking-client`](https://pypi.org/project/growflowbooking-client/) | [![PyPI](https://img.shields.io/pypi/v/growflowbooking-client?logo=pypi&logoColor=white&label=pypi)](https://pypi.org/project/growflowbooking-client/) Python SDK |
| [`@growflowstudio/growflowbooking-admin-core`](https://www.npmjs.com/package/@growflowstudio/growflowbooking-admin-core) · [`-admin-ui`](https://www.npmjs.com/package/@growflowstudio/growflowbooking-admin-ui) | Headless admin SDK + shadcn/ui components |

**🛍️ ShopBrain**
| Package | |
|---|---|
| [`@growflowstudio/shopbrain-chat-widget`](https://www.npmjs.com/package/@growflowstudio/shopbrain-chat-widget) | [![npm](https://img.shields.io/npm/v/@growflowstudio/shopbrain-chat-widget?logo=npm&label=npm)](https://www.npmjs.com/package/@growflowstudio/shopbrain-chat-widget) Embeddable AI chat for e-commerce, one script tag |

---

## 🧳 Where I've been
| | |
|---|---|
| **Sky** | Software Architect: requirements → architecture → dev teams, ADRs as first-class artifacts |
| **Facile.it** | Senior SEO Full-Stack Engineer: led SEO optimization on a comparator with millions of users |
| **Octopus Energy** | Senior Front-End Lead: Italian front-end in a multi-country team |
| **Liferay** | Full-Stack Dev on an open-source enterprise DXP |
| **Deloitte** | Cloud Developer: AWS, IaC, serverless, ETL pipelines |
| **Accenture** | Full-Stack Dev: luxury e-commerce on AEM + SAP Hybris, tracking & analytics |
| **Henable** | Co-founder: social coop for digital accessibility, before it was cool |

---

## 👯 Looking to collaborate on
- MCP servers and AI agents that plug into real business systems
- Civic tech, open data and digital rights
- Products where marketing, tech and design collide, in chaos and in harmony
- Anything that makes complex infra... disappear

## 🌱 Currently learning
- Knowledge graphs + LightRAG in production
- AI Act / L. 132/2025 compliance *as an engineering problem*
- How to say "no" to the 10th side project of the week (still failing)

## 💬 Ask me about
- The best sea in Europe to cry on after a failed deploy 🌊
- Explaining SEO to your grandma, and now GEO as well
- How I accidentally ranked higher than a client's homepage 😬
- Where to find good Wi-Fi and even better coffee in random countries

---

## 💻 Tech I actually use

**Languages**
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white) ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white) ![Bash](https://img.shields.io/badge/bash-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)

**Front-end & design systems**
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white) ![Vue.js](https://img.shields.io/badge/vue.js-%2335495e.svg?style=for-the-badge&logo=vuedotjs&logoColor=%234FC08D) ![Nuxt](https://img.shields.io/badge/Nuxt-002E3B?style=for-the-badge&logo=nuxt.js&logoColor=#00DC82) ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white) ![Storybook](https://img.shields.io/badge/-Storybook-FF4785?style=for-the-badge&logo=storybook&logoColor=white) ![Strapi](https://img.shields.io/badge/strapi-%232E7EEA.svg?style=for-the-badge&logo=strapi&logoColor=white)

**Back-end & data**
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi) ![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white) ![GraphQL](https://img.shields.io/badge/-GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white) ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white) ![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-000?style=for-the-badge&logo=apachekafka)

**AI**
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white) ![MCP](https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=anthropic&logoColor=white) ![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black) ![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)

**Cloud & delivery**
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) ![Google Cloud](https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white) ![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white) ![Terraform](https://img.shields.io/badge/terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white) ![Stripe](https://img.shields.io/badge/Stripe-5469d4?style=for-the-badge&logo=stripe&logoColor=white) ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)

<details>
<summary>…and a long tail of things I've shipped with at some point</summary>

Angular · Gatsby · Laravel · Symfony · WordPress · AEM · SAP Hybris · Liferay · MongoDB · MySQL · Supabase · Prisma · Firebase · Elasticsearch · Three.js · D3 · React Native · Expo · Electron · Solidity · OCaml · C · R · Vercel · Netlify · Render · CircleCI · GitLab CI · Tealium · GTM · GA4
</details>

---

## 📊 GitHub stats
![](https://github-readme-stats.vercel.app/api?username=giuliogarofalo&theme=nightowl&hide_border=false&include_all_commits=true&count_private=true)<br/>
![](https://nirzak-streak-stats.vercel.app/?user=giuliogarofalo&theme=nightowl&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=giuliogarofalo&theme=nightowl&hide_border=false&include_all_commits=true&count_private=true&layout=compact)

---

## 📫 Reach me
📧 [giulio@growflow.studio](mailto:giulio@growflow.studio) · 🌐 [growflow.studio](https://growflow.studio)
📍 Milan, or wherever the Wi-Fi works

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/giuliogarofalo91) [![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/giuls.go) [![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:giulio@growflow.studio)
