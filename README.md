# Hi, I'm Kudakwashe Kwindima

**Founder and engineer behind [Visit Zimbabwe](https://govisitzimbabwe.com)**, the independent Zimbabwe travel guide. I'm a data engineer who now builds and runs production web platforms end to end, from data pipelines and APIs to the website people use.

My background is in accounting and hospitality operations, so I build for real businesses: correct data, clear rules and systems that keep running.

---

## What I'm building

### 🌍 Visit Zimbabwe: [govisitzimbabwe.com](https://govisitzimbabwe.com)
*Founder · sole engineer · live since 2026 · private codebase · [read the case study](https://github.com/Kuda-Kwindima/visitzimbabwe-case-study)*

A travel guide to Zimbabwe with 347 human-reviewed places to stay, eat and visit, destination guides, itineraries, an events calendar and an illustrated food guide, in English and French.

- **Curation pipeline:** a PostGIS database with raw → staging → core → publishing schemas, field-level source evidence, reviewed map points and explicit publication decisions
- **Database-free production:** approved places export to a release file, so the live site has no database to breach or keep alive
- **Web app:** FastAPI and Jinja, server-rendered, accessible and fast on phones; My Trip saves in the visitor's browser with no account
- **Delivery:** Docker on Fly.io (Johannesburg) behind Cloudflare; every pull request runs about 380 fast tests, Playwright browser journeys on phone and desktop, and a smoke test of the exact production image
- **Operations:** a weekly freshness job that flags stale facts and broken links, image and video pipelines with creator credits, privacy-light visitor counts

`Python` `FastAPI` `Jinja` `PostgreSQL/PostGIS` `Docker` `Fly.io` `Cloudflare` `GitHub Actions` `Playwright` `ffmpeg`

### 🛍️ WhatsApp Shop *(paused)*
*Private*

A multi-shop platform where small retailers in Zimbabwe run a shop inside WhatsApp. Customers search, pick sizes, add to a cart and pay with EcoCash, OneMoney or a card through Paynow, all without leaving the chat.

- A Meta WhatsApp Cloud API webhook that answers at once and does the work in the background
- A product catalogue from an external API with a database cache in front, because every call costs money
- Pricing rules for currency conversion, markup, transport and clearing fees

`Python` `FastAPI` `PostgreSQL` `Docker` `WhatsApp Cloud API` `Paynow`

### 📦 Stock expiry tracker
*Private*

A local tool for a multi-outlet hospitality operation. It imports monthly stock workbooks from every outlet, merges product variants with explicit rules and keeps the original evidence. It shows the next expiry dates colour-coded by urgency and exports a formatted Excel register.

`Python` `Excel automation` `Data quality rules`

---

## Data engineering projects

| Project | What it does | Stack |
|---|---|---|
| [Financial reconciliation pipeline](https://github.com/Kuda-Kwindima/financial-reconciliation-pipeline) | Reconciles hospitality POS, card settlements, cash and ledger charges, with exception monitoring | PostgreSQL · Docker · Prefect · Power BI |
| [Retail analytics on Microsoft Fabric](https://github.com/Kuda-Kwindima/retail-optimization-fabric) | Medallion lakehouse with Data Factory pipelines and Direct Lake reporting | Fabric · OneLake · PySpark · Delta Lake |
| [Azure retail warehouse](https://github.com/Kuda-Kwindima/azure-retail-data-engineering-pipeline) | Instacart reorder analytics warehouse | ADF · ADLS · Azure SQL · Power BI |
| [Procurement price monitoring](https://github.com/Kuda-Kwindima/hospitality-procurement-monitoring-pipeline) | Supplier price tracking and cost alerts | Airflow · PostgreSQL · Docker |
| [Retail price and inventory optimisation](https://github.com/Kuda-Kwindima/retail-price-inventory-optimization) | Demand forecasting and price optimisation | Python · Jupyter |
| [Credit default risk](https://github.com/Kuda-Kwindima/credit-default-risk-ml) | Classification, calibration and threshold analysis | Python · ML |

---

## Skills

- **Web and APIs:** FastAPI, REST APIs, webhooks, server-rendered sites, accessibility, SEO, internationalisation
- **Data:** PostgreSQL/PostGIS, SQL, data modelling, ETL/ELT, Airflow, Prefect, Azure Data Factory, Microsoft Fabric, Power BI
- **Delivery:** Docker, Fly.io, Cloudflare, GitHub Actions CI, Playwright testing
- **Languages:** Python, SQL, JavaScript, HTML/CSS

---

## Connect

[LinkedIn](https://www.linkedin.com/in/kudakwashe-kwindima) · [govisitzimbabwe.com](https://govisitzimbabwe.com)
