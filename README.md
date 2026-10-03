# Giulio Garofalo

I write software for a living and, since September, I also explain it to teenagers: I teach computer science at a technical high school. Of everything on this page, teaching is the one I'm still learning to do.

I've been at this for eleven years. Most of them went into other people's platforms (Accenture, Deloitte, Liferay, Octopus Energy, Facile.it, Sky), the recent ones into my own. I took a degree in economics before the one in engineering, so I tend to ask what a technical choice costs before I ask whether it's elegant.

Qualified *Ingegnere dell'Informazione* (Italian state exam, Section A, September 2026). MSc in Management Engineering, BSc in Economics and Business Management, and a postgraduate year in Digital Management at Ca' Foscari / H-Farm in between.

## What I'm working on

**[ShopBrain](https://shopbrain.store)** is the company I founded in 2025. Its main product is a chat assistant for online shops. It reads the shop's real catalogue and answers from that, on the site, on WhatsApp and on Telegram, with Shopify and WooCommerce plugged in. When the conversation needs a person, a person can take it over.

Three smaller products came out of the same codebase and share its billing and infrastructure:

- [BookBrain](https://bookbrain.it) handles appointments: a widget you embed in your site, Google Calendar sync, live queues.
- [ShipBrain](https://shipbrain.it) manages shipments and parcels, with Poste and SDA tracking. It began as a tool for a single winery, which still uses it every day.
- [SiteBrain](https://sitebrain.it): you paste your Instagram or your old site, and a minute later you are looking at a new one. It costs €19, once.

**[OpenLegis](https://openlegis.it)** answers questions about Italian and EU law and shows which article each answer comes from. Underneath there is a graph of which law amends or cites which, built from official sources: Normattiva, Camera and Senato, EUR-Lex, Gazzetta Ufficiale, the Constitutional Court, Cassazione, Eurostat. I publish the connectors as MCP servers so that other people's agents can use them too.

**[GrowFlow Studio](https://growflow.studio)** is where client work goes: technical SEO, sites that AI search engines can read and quote, design systems, headless CMS. Recent jobs include the four-language site and cellar-visit bookings for [d'Araprì](https://www.darapri.it), a sparkling wine house in Puglia, and [Signor G](https://signorg.ai), a vinyl shop with search across marketplaces and an AI assistant behind the counter. With the d'Araprì people I also made [WineQuiz](https://winequiz.it), for sommeliers who like being tested.

## Packages

- [`republic-mcp`](https://www.npmjs.com/package/republic-mcp) (npm, [source](https://github.com/giuliogarofalo/RepublicMCP)): Italian Parliament open data, queried on the official Camera and Senato SPARQL endpoints.
- [`open-parlamento-mcp`](https://pypi.org/project/open-parlamento-mcp/) (PyPI, [source](https://github.com/giuliogarofalo/open-parlamento-mcp)): Italian and EU law, case law, Eurostat, Gazzetta Ufficiale.
- GrowFlow Billing, the subscriptions and invoicing layer under every product above: [Node client](https://www.npmjs.com/package/@growflowstudio/growflowbilling-client), [Python client](https://pypi.org/project/growflowbilling-client/), [admin core](https://www.npmjs.com/package/@growflowstudio/growflowbilling-admin-core), [admin UI](https://www.npmjs.com/package/@growflowstudio/growflowbilling-admin-ui).
- GrowFlow Booking, the engine under BookBrain: [widget](https://www.npmjs.com/package/@growflowstudio/growflowbooking-widget), [Node client](https://www.npmjs.com/package/@growflowstudio/growflowbooking-client), [Python client](https://pypi.org/project/growflowbooking-client/), [admin core](https://www.npmjs.com/package/@growflowstudio/growflowbooking-admin-core), [admin UI](https://www.npmjs.com/package/@growflowstudio/growflowbooking-admin-ui).
- [`shopbrain-chat-widget`](https://www.npmjs.com/package/@growflowstudio/shopbrain-chat-widget): the ShopBrain chat, embedded with one script tag.

## Where I worked

| | | |
|---|---|---|
| 2025 | Sky | Software architect: from requirements to designs the delivery teams could build |
| 2023–25 | Facile.it | Led the SEO engineering team of a comparison site with millions of users |
| 2022–23 | Octopus Energy | Led the Italian front-end, in a team spread over several countries |
| 2020–22 | Liferay | Full-stack developer on an open-source enterprise platform |
| 2019 | Deloitte | AWS architectures and data pipelines for fashion and manufacturing |
| 2017–19 | Accenture | E-commerce for fashion and eyewear brands, on AEM and SAP Hybris |
| 2015–17 | Henable | Co-founded a social cooperative in Venice building accessible digital services |

## What I use

**Languages**
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white) ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white) ![Bash](https://img.shields.io/badge/bash-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)

**Front-end & design systems**
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white) ![Vue.js](https://img.shields.io/badge/vue.js-%2335495e.svg?style=for-the-badge&logo=vuedotjs&logoColor=%234FC08D) ![Nuxt](https://img.shields.io/badge/Nuxt-002E3B?style=for-the-badge&logo=nuxt.js&logoColor=%2300DC82) ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white) ![Storybook](https://img.shields.io/badge/-Storybook-FF4785?style=for-the-badge&logo=storybook&logoColor=white) ![Strapi](https://img.shields.io/badge/strapi-%232E7EEA.svg?style=for-the-badge&logo=strapi&logoColor=white)

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

## Numbers

![](https://github-readme-stats.vercel.app/api?username=giuliogarofalo&theme=nightowl&hide_border=false&include_all_commits=true&count_private=true)<br/>
![](https://nirzak-streak-stats.vercel.app/?user=giuliogarofalo&theme=nightowl&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=giuliogarofalo&theme=nightowl&hide_border=false&layout=compact&exclude_repo=openlegis-frontend)

## Write to me

If you are building MCP servers, working with public data, or need someone who can sit between marketing and engineering without translating twice, I'd like to hear about it. I can also explain SEO to your grandmother, and I have opinions on which European sea is best after a failed deploy.

[giulio@growflow.studio](mailto:giulio@growflow.studio) · [growflow.studio](https://growflow.studio) · [LinkedIn](https://linkedin.com/in/giuliogarofalo91) · [Instagram](https://instagram.com/giuls.go)<br>
Milan, or wherever the Wi-Fi works.
