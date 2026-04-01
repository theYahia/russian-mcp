# MCP Servers for Non-Western APIs — 114 servers, 22+ countries

> The largest open-source collection of MCP servers for Russia, CIS, MENA, Africa, Latin America, and Southeast Asia.
> Zero MCP servers existed for these markets before this project. Now there are 114, with 887 tools.

[![Servers](https://img.shields.io/badge/MCP_Servers-114-blue)](https://www.npmjs.com/org/theyahia)
[![Tools](https://img.shields.io/badge/Tools-887-green)](https://www.npmjs.com/org/theyahia)
[![npm](https://img.shields.io/badge/npm-@theyahia-red)](https://www.npmjs.com/org/theyahia)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**npm:** [@theyahia](https://www.npmjs.com/org/theyahia) | **Author:** [@theYahia](https://github.com/theYahia) | **Telegram:** [@vhodvai](https://t.me/vhodvai)

---

## Quick Start

```bash
npx -y @theyahia/yookassa-mcp
```

Every server follows the same pattern — install via npx, pass API keys as env vars, connect to Claude / Cursor / VS Code / any MCP client.

---

## Russia (64 servers)

### Payments

| Package | Version | Tools | Description |
|---------|---------|-------|-------------|
| [@theyahia/yookassa-mcp](https://www.npmjs.com/package/@theyahia/yookassa-mcp) | ![v2.0.0](https://img.shields.io/badge/v2.0.0-blue) | **20** | YooKassa — payments, refunds, receipts (54-FZ), payouts, webhooks, recurring, SBP, splits |
| [@theyahia/tkassa-mcp](https://www.npmjs.com/package/@theyahia/tkassa-mcp) | ![v2.0.0](https://img.shields.io/badge/v2.0.0-blue) | **14** | T-Kassa (T-Bank/Tinkoff) — payments, refunds, recurring, customers, cards, SBP, receipts |
| [@theyahia/cloudpayments-mcp](https://www.npmjs.com/package/@theyahia/cloudpayments-mcp) | ![v2.0.0](https://img.shields.io/badge/v2.0.0-blue) | **12** | CloudPayments — charge, auth, confirm, void, refund, subscriptions, orders |
| [@theyahia/sberbank-acquiring-mcp](https://www.npmjs.com/package/@theyahia/sberbank-acquiring-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **10** | Sberbank eCommerce Acquiring — online payments, refunds, pre-auth, card tokenization |
| [@theyahia/prodamus-mcp](https://www.npmjs.com/package/@theyahia/prodamus-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **8** | Prodamus — payments, subscriptions, refunds, invoices |
| [@theyahia/robokassa-mcp](https://www.npmjs.com/package/@theyahia/robokassa-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **2** | Robokassa — payment URL generation, invoice status |

### CRM & Business

| Package | Version | Tools | Description |
|---------|---------|-------|-------------|
| [@theyahia/moysklad-mcp](https://www.npmjs.com/package/@theyahia/moysklad-mcp) | ![v3.0.0](https://img.shields.io/badge/v3.0.0-blue) | **21** | MoySklad — products, stock, orders, counterparties, shipments, supplies, reports, webhooks |
| [@theyahia/amocrm-mcp](https://www.npmjs.com/package/@theyahia/amocrm-mcp) | ![v2.0.1](https://img.shields.io/badge/v2.0.1-blue) | **19** | amoCRM — leads, contacts, companies, pipelines, tasks, notes, search, events, OAuth 2.0 |
| [@theyahia/retailcrm-mcp](https://www.npmjs.com/package/@theyahia/retailcrm-mcp) | ![v2.0.0](https://img.shields.io/badge/v2.0.0-blue) | **15** | RetailCRM — orders, customers, products, references, analytics |
| [@theyahia/bitrix24-mcp](https://www.npmjs.com/package/@theyahia/bitrix24-mcp) | ![v3.0.0](https://img.shields.io/badge/v3.0.0-blue) | **12** | Bitrix24 — CRM deals, contacts, tasks, users, files, messages |
| [@theyahia/yandex-tracker-mcp](https://www.npmjs.com/package/@theyahia/yandex-tracker-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **12** | Yandex Tracker — issues, queues, comments, worklogs |
| [@theyahia/kaiten-mcp](https://www.npmjs.com/package/@theyahia/kaiten-mcp) | ![v3.0.0](https://img.shields.io/badge/v3.0.0-blue) | **10** | Kaiten — boards, cards, columns, tags, users, comments |
| [@theyahia/megaplan-mcp](https://www.npmjs.com/package/@theyahia/megaplan-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **3** | Megaplan — tasks, deals management |
| [@theyahia/planfix-mcp](https://www.npmjs.com/package/@theyahia/planfix-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **3** | Planfix — tasks, contacts |
| [@theyahia/elma365-mcp](https://www.npmjs.com/package/@theyahia/elma365-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **3** | ELMA365 — BPM platform, app items, tasks |

### Marketing & Analytics

| Package | Version | Tools | Description |
|---------|---------|-------|-------------|
| [@theyahia/yandex-metrika-mcp](https://www.npmjs.com/package/@theyahia/yandex-metrika-mcp) | ![v2.1.0](https://img.shields.io/badge/v2.1.0-blue) | **15** | Yandex.Metrika — counters, goals, reports, logs, traffic analysis |
| [@theyahia/yandex-direct-mcp](https://www.npmjs.com/package/@theyahia/yandex-direct-mcp) | ![v3.0.0](https://img.shields.io/badge/v3.0.0-blue) | **12** | Yandex.Direct — campaigns, ad groups, ads, keywords, statistics |
| [@theyahia/appmetrica-mcp](https://www.npmjs.com/package/@theyahia/appmetrica-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **8** | AppMetrica — mobile analytics, reports, cohorts, push campaigns, crashes |
| [@theyahia/tgstat-mcp](https://www.npmjs.com/package/@theyahia/tgstat-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **8** | TGStat — Telegram channel analytics, search, posts, stats, mentions |
| [@theyahia/vk-ads-mcp](https://www.npmjs.com/package/@theyahia/vk-ads-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **8** | VK Ads — campaigns, ads, statistics, targeting, budgets |
| [@theyahia/unisender-mcp](https://www.npmjs.com/package/@theyahia/unisender-mcp) | ![v1.0.1](https://img.shields.io/badge/v1.0.1-blue) | **4** | UniSender — email lists, campaigns, contacts |
| [@theyahia/sendpulse-mcp](https://www.npmjs.com/package/@theyahia/sendpulse-mcp) | ![v1.0.2](https://img.shields.io/badge/v1.0.2-blue) | **3** | SendPulse — mailing lists, email sending, statistics |
| [@theyahia/mindbox-mcp](https://www.npmjs.com/package/@theyahia/mindbox-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **3** | Mindbox — CDP platform, customer profiles, orders, segments |
| [@theyahia/yandex-webmaster-mcp](https://www.npmjs.com/package/@theyahia/yandex-webmaster-mcp) | ![v1.0.1](https://img.shields.io/badge/v1.0.1-blue) | **3** | Yandex.Webmaster — hosts, search queries, indexing status |
| [@theyahia/calltouch-mcp](https://www.npmjs.com/package/@theyahia/calltouch-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **2** | Calltouch — call tracking, call statistics |
| [@theyahia/roistat-mcp](https://www.npmjs.com/package/@theyahia/roistat-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **2** | Roistat — marketing analytics, visits tracking |

### Logistics

| Package | Version | Tools | Description |
|---------|---------|-------|-------------|
| [@theyahia/cdek-mcp](https://www.npmjs.com/package/@theyahia/cdek-mcp) | ![v2.0.1](https://img.shields.io/badge/v2.0.1-blue) | **14** | CDEK — tariff calculation, order management, tracking, delivery points, webhooks |
| [@theyahia/ati-su-mcp](https://www.npmjs.com/package/@theyahia/ati-su-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **8** | ATI.su — freight exchange, cargo search, truck matching, company ratings |
| [@theyahia/boxberry-mcp](https://www.npmjs.com/package/@theyahia/boxberry-mcp) | ![v1.0.1](https://img.shields.io/badge/v1.0.1-blue) | **4** | Boxberry — city/point search, delivery calculation, tracking |
| [@theyahia/delovye-linii-mcp](https://www.npmjs.com/package/@theyahia/delovye-linii-mcp) | ![v1.0.1](https://img.shields.io/badge/v1.0.1-blue) | **3** | Delovye Linii — tariff calculation, city search, tracking |
| [@theyahia/pochta-russia-mcp](https://www.npmjs.com/package/@theyahia/pochta-russia-mcp) | ![v1.0.1](https://img.shields.io/badge/v1.0.1-blue) | **3** | Russian Post — tracking, tariff calculation, post office search |
| [@theyahia/yandex-delivery-mcp](https://www.npmjs.com/package/@theyahia/yandex-delivery-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **--** | Yandex Delivery — claims, tracking, price estimation (planned) |

### HR

| Package | Version | Tools | Description |
|---------|---------|-------|-------------|
| [@theyahia/hh-mcp](https://www.npmjs.com/package/@theyahia/hh-mcp) | ![v2.0.0](https://img.shields.io/badge/v2.0.0-blue) | **15** | hh.ru — vacancy search, resumes, employers, salary stats, dictionaries |
| [@theyahia/huntflow-mcp](https://www.npmjs.com/package/@theyahia/huntflow-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **4** | HuntFlow ATS — vacancies, candidates, applicants |
| [@theyahia/superjob-mcp](https://www.npmjs.com/package/@theyahia/superjob-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **2** | SuperJob.ru — vacancy search, employers |

### Communications

| Package | Version | Tools | Description |
|---------|---------|-------|-------------|
| [@theyahia/yandex-360-mcp](https://www.npmjs.com/package/@theyahia/yandex-360-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **10** | Yandex 360 — users, departments, groups, disk, calendar |
| [@theyahia/mts-exolve-mcp](https://www.npmjs.com/package/@theyahia/mts-exolve-mcp) | ![v3.0.0](https://img.shields.io/badge/v3.0.0-blue) | **8** | MTS Exolve — SMS, calls, call recordings, phone numbers, Viber |
| [@theyahia/vk-mcp](https://www.npmjs.com/package/@theyahia/vk-mcp) | ![v1.0.1](https://img.shields.io/badge/v1.0.1-blue) | **4** | VKontakte — wall posts, news search, users, groups |
| [@theyahia/jivosite-mcp](https://www.npmjs.com/package/@theyahia/jivosite-mcp) | ![v1.0.1](https://img.shields.io/badge/v1.0.1-blue) | **3** | JivoSite — chats, agents, visitors |
| [@theyahia/tilda-mcp](https://www.npmjs.com/package/@theyahia/tilda-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **3** | Tilda — website builder, projects, pages |
| [@theyahia/sms-ru-mcp](https://www.npmjs.com/package/@theyahia/sms-ru-mcp) | ![v1.0.1](https://img.shields.io/badge/v1.0.1-blue) | **3** | SMS.RU — send SMS, check status, balance |
| [@theyahia/voximplant-mcp](https://www.npmjs.com/package/@theyahia/voximplant-mcp) | ![v1.0.1](https://img.shields.io/badge/v1.0.1-blue) | **3** | Voximplant — call history, users, SMS |
| [@theyahia/mango-office-mcp](https://www.npmjs.com/package/@theyahia/mango-office-mcp) | ![v1.0.1](https://img.shields.io/badge/v1.0.1-blue) | **2** | Mango Office — calls, users |

### AI & Cloud

| Package | Version | Tools | Description |
|---------|---------|-------|-------------|
| [@theyahia/gigachat-mcp](https://www.npmjs.com/package/@theyahia/gigachat-mcp) | ![v3.0.0](https://img.shields.io/badge/v3.0.0-blue) | **8** | GigaChat (Sber) — chat, models, embeddings, image generation, assistants |
| [@theyahia/yandexgpt-mcp](https://www.npmjs.com/package/@theyahia/yandexgpt-mcp) | ![v3.0.0](https://img.shields.io/badge/v3.0.0-blue) | **8** | YandexGPT — completion, embeddings, classification, summarization, tokenization |
| [@theyahia/yandex-cloud-mcp](https://www.npmjs.com/package/@theyahia/yandex-cloud-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **8** | Yandex Cloud — compute, storage, serverless, operations |
| [@theyahia/salutespeech-mcp](https://www.npmjs.com/package/@theyahia/salutespeech-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **2** | SaluteSpeech (Sber) — speech recognition and synthesis |
| [@theyahia/yandex-speechkit-mcp](https://www.npmjs.com/package/@theyahia/yandex-speechkit-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **2** | Yandex SpeechKit — speech recognition and synthesis |

### Finance & Fiscal

| Package | Version | Tools | Description |
|---------|---------|-------|-------------|
| [@theyahia/alfa-bank-mcp](https://www.npmjs.com/package/@theyahia/alfa-bank-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **8** | Alfa-Bank Business — accounts, payments, statements, exchange rates |
| [@theyahia/atol-online-mcp](https://www.npmjs.com/package/@theyahia/atol-online-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **8** | ATOL Online — fiscal receipts, 54-FZ compliance |
| [@theyahia/kontur-diadoc-mcp](https://www.npmjs.com/package/@theyahia/kontur-diadoc-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **8** | Kontur.Diadoc — electronic document interchange |
| [@theyahia/tochka-bank-mcp](https://www.npmjs.com/package/@theyahia/tochka-bank-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **8** | Tochka Bank — accounts, payments, counterparties |
| [@theyahia/1c-rest-mcp](https://www.npmjs.com/package/@theyahia/1c-rest-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **3** | 1C REST API — catalogs, documents |
| [@theyahia/sber-mcp](https://www.npmjs.com/package/@theyahia/sber-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **2** | Sberbank API — accounts, statements |

### Data & Legal

| Package | Version | Tools | Description |
|---------|---------|-------|-------------|
| [@metarebalance/dadata-mcp](https://www.npmjs.com/package/@metarebalance/dadata-mcp) | ![v1.0.4](https://img.shields.io/badge/v1.0.4-blue) | **31** | DaData.ru — address validation, company lookup, phone cleaning, geocoding |
| [@theyahia/yandex-maps-mcp](https://www.npmjs.com/package/@theyahia/yandex-maps-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **10** | Yandex Maps — geocoding, routing, places search, static maps |
| [@theyahia/2gis-mcp](https://www.npmjs.com/package/@theyahia/2gis-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **8** | 2GIS — places, geocoding, directions, reviews |
| [@theyahia/casebook-mcp](https://www.npmjs.com/package/@theyahia/casebook-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **8** | Casebook/Pravo.ru — legal case search |
| [@theyahia/kontur-focus-mcp](https://www.npmjs.com/package/@theyahia/kontur-focus-mcp) | ![v3.0.0](https://img.shields.io/badge/v3.0.0-blue) | **8** | Kontur.Focus — company search, EGRUL, financial statements, arbitration |
| [@theyahia/spark-interfax-mcp](https://www.npmjs.com/package/@theyahia/spark-interfax-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **8** | SPARK-Interfax — business intelligence |
| [@theyahia/cbr-mcp](https://www.npmjs.com/package/@theyahia/cbr-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **5** | Central Bank of Russia — currency rates, key rate, precious metals |
| [@theyahia/chestnyznak-mcp](https://www.npmjs.com/package/@theyahia/chestnyznak-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **2** | Chestniy ZNAK — product marking verification |

### Other

| Package | Version | Tools | Description |
|---------|---------|-------|-------------|
| [@theyahia/travelpayouts-mcp](https://www.npmjs.com/package/@theyahia/travelpayouts-mcp) | ![v2.0.0](https://img.shields.io/badge/v2.0.0-blue) | **11** | Travelpayouts — flights, hotels, price calendar, popular directions |
| [@theyahia/getcourse-mcp](https://www.npmjs.com/package/@theyahia/getcourse-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **3** | GetCourse — online school platform, users, deals |

---

## Kazakhstan (3 servers)

| Package | Version | Tools | Description |
|---------|---------|-------|-------------|
| [@theyahia/forte-bank-mcp](https://www.npmjs.com/package/@theyahia/forte-bank-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **8** | Forte Bank — payment gateway |
| [@theyahia/halyk-epay-mcp](https://www.npmjs.com/package/@theyahia/halyk-epay-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **8** | Halyk Bank ePay — payment gateway |
| [@theyahia/kaspi-mcp](https://www.npmjs.com/package/@theyahia/kaspi-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **3** | Kaspi.kz — shop orders, products |

## Uzbekistan (3 servers)

| Package | Version | Tools | Description |
|---------|---------|-------|-------------|
| [@theyahia/click-mcp](https://www.npmjs.com/package/@theyahia/click-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **8** | Click — payment system |
| [@theyahia/factura-uz-mcp](https://www.npmjs.com/package/@theyahia/factura-uz-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **8** | Factura.uz — electronic invoicing |
| [@theyahia/payme-mcp](https://www.npmjs.com/package/@theyahia/payme-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **8** | Payme — payment system |

## Georgia (2 servers)

| Package | Version | Tools | Description |
|---------|---------|-------|-------------|
| [@theyahia/bog-ipay-mcp](https://www.npmjs.com/package/@theyahia/bog-ipay-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **8** | Bank of Georgia iPay — payments |
| [@theyahia/tbc-bank-mcp](https://www.npmjs.com/package/@theyahia/tbc-bank-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **8** | TBC Bank — payment gateway |

## Belarus (1 server)

| Package | Version | Tools | Description |
|---------|---------|-------|-------------|
| [@theyahia/bepaid-mcp](https://www.npmjs.com/package/@theyahia/bepaid-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **8** | bePaid — payment gateway |

## Moldova (1 server)

| Package | Version | Tools | Description |
|---------|---------|-------|-------------|
| [@theyahia/maib-mcp](https://www.npmjs.com/package/@theyahia/maib-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **8** | MAIB — e-commerce payments |

---

## Turkey (7 servers)

| Package | Version | Tools | Description |
|---------|---------|-------|-------------|
| [@theyahia/trendyol-mcp](https://www.npmjs.com/package/@theyahia/trendyol-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **9** | Trendyol — marketplace API |
| [@theyahia/iyzico-mcp](https://www.npmjs.com/package/@theyahia/iyzico-mcp) | ![v1.0.1](https://img.shields.io/badge/v1.0.1-blue) | **8** | iyzico — payment gateway |
| [@theyahia/getir-mcp](https://www.npmjs.com/package/@theyahia/getir-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **8** | Getir — partner API |
| [@theyahia/hepsiburada-mcp](https://www.npmjs.com/package/@theyahia/hepsiburada-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **8** | Hepsiburada — marketplace API |
| [@theyahia/ileti-merkezi-mcp](https://www.npmjs.com/package/@theyahia/ileti-merkezi-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **8** | Ileti Merkezi — SMS API |
| [@theyahia/is-bankasi-mcp](https://www.npmjs.com/package/@theyahia/is-bankasi-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **8** | Isbank — developer API |
| [@theyahia/parasut-mcp](https://www.npmjs.com/package/@theyahia/parasut-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **8** | Parasut — accounting API |

## Gulf — UAE & Saudi Arabia (7 servers)

| Package | Version | Tools | Description |
|---------|---------|-------|-------------|
| [@theyahia/salla-mcp](https://www.npmjs.com/package/@theyahia/salla-mcp) | ![v1.1.0](https://img.shields.io/badge/v1.1.0-blue) | **9** | Salla — e-commerce platform (Saudi) |
| [@theyahia/foodics-mcp](https://www.npmjs.com/package/@theyahia/foodics-mcp) | ![v1.1.0](https://img.shields.io/badge/v1.1.0-blue) | **8** | Foodics — POS/restaurant platform (UAE/Saudi) |
| [@theyahia/moyasar-mcp](https://www.npmjs.com/package/@theyahia/moyasar-mcp) | ![v1.1.0](https://img.shields.io/badge/v1.1.0-blue) | **8** | Moyasar — payment gateway (Saudi) |
| [@theyahia/tabby-mcp](https://www.npmjs.com/package/@theyahia/tabby-mcp) | ![v1.1.0](https://img.shields.io/badge/v1.1.0-blue) | **8** | Tabby — buy-now-pay-later (UAE/Saudi) |
| [@theyahia/tap-payments-mcp](https://www.npmjs.com/package/@theyahia/tap-payments-mcp) | ![v1.1.0](https://img.shields.io/badge/v1.1.0-blue) | **8** | Tap Payments — gateway (UAE/Saudi/Kuwait/Bahrain) |
| [@theyahia/unifonic-mcp](https://www.npmjs.com/package/@theyahia/unifonic-mcp) | ![v1.1.0](https://img.shields.io/badge/v1.1.0-blue) | **8** | Unifonic — CPaaS: SMS, Voice, WhatsApp (Saudi) |
| [@theyahia/paytabs-mcp](https://www.npmjs.com/package/@theyahia/paytabs-mcp) | ![v1.1.0](https://img.shields.io/badge/v1.1.0-blue) | **8** | PayTabs — payment gateway (MENA region) |

## Latin America (7 servers)

| Package | Version | Tools | Description |
|---------|---------|-------|-------------|
| [@theyahia/facturapi-mcp](https://www.npmjs.com/package/@theyahia/facturapi-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **10** | Facturapi — Mexican e-invoicing (CFDI) |
| [@theyahia/nfeio-mcp](https://www.npmjs.com/package/@theyahia/nfeio-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **10** | NFe.io — Brazilian fiscal document platform |
| [@theyahia/pagarme-mcp](https://www.npmjs.com/package/@theyahia/pagarme-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **10** | Pagar.me — payment gateway (Brazil) |
| [@theyahia/asaas-mcp](https://www.npmjs.com/package/@theyahia/asaas-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **9** | Asaas — payment and Pix gateway (Brazil) |
| [@theyahia/correios-mcp](https://www.npmjs.com/package/@theyahia/correios-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **8** | Correios — Brazilian postal service |
| [@theyahia/hotmart-mcp](https://www.npmjs.com/package/@theyahia/hotmart-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **8** | Hotmart — digital products platform (Brazil) |
| [@theyahia/ifood-mcp](https://www.npmjs.com/package/@theyahia/ifood-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **8** | iFood — merchant integration (Brazil) |

## Africa (6 servers)

| Package | Version | Tools | Description |
|---------|---------|-------|-------------|
| [@theyahia/africas-talking-mcp](https://www.npmjs.com/package/@theyahia/africas-talking-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **8** | Africa's Talking — SMS, voice, USSD, airtime (Kenya, Nigeria, 10+ countries) |
| [@theyahia/nomba-mcp](https://www.npmjs.com/package/@theyahia/nomba-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **8** | Nomba — payment and POS platform (Nigeria) |
| [@theyahia/payfast-mcp](https://www.npmjs.com/package/@theyahia/payfast-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **8** | PayFast — payment gateway (South Africa) |
| [@theyahia/termii-mcp](https://www.npmjs.com/package/@theyahia/termii-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **8** | Termii — SMS and messaging (Nigeria) |
| [@theyahia/yoco-mcp](https://www.npmjs.com/package/@theyahia/yoco-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **8** | Yoco — payment gateway (South Africa) |
| [@theyahia/chargily-mcp](https://www.npmjs.com/package/@theyahia/chargily-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **8** | Chargily Pay — payment gateway (Algeria) |

## Southeast Asia (7 servers)

| Package | Version | Tools | Description |
|---------|---------|-------|-------------|
| [@theyahia/paymongo-mcp](https://www.npmjs.com/package/@theyahia/paymongo-mcp) | ![v1.0.1](https://img.shields.io/badge/v1.0.1-blue) | **9** | PayMongo — payment gateway (Philippines) |
| [@theyahia/midtrans-mcp](https://www.npmjs.com/package/@theyahia/midtrans-mcp) | ![v1.0.1](https://img.shields.io/badge/v1.0.1-blue) | **8** | Midtrans — payment gateway (Indonesia) |
| [@theyahia/momo-vn-mcp](https://www.npmjs.com/package/@theyahia/momo-vn-mcp) | ![v1.0.1](https://img.shields.io/badge/v1.0.1-blue) | **8** | MoMo — payment gateway (Vietnam) |
| [@theyahia/rajaongkir-mcp](https://www.npmjs.com/package/@theyahia/rajaongkir-mcp) | ![v1.0.1](https://img.shields.io/badge/v1.0.1-blue) | **8** | RajaOngkir — shipping cost API (Indonesia) |
| [@theyahia/vnpay-mcp](https://www.npmjs.com/package/@theyahia/vnpay-mcp) | ![v1.0.1](https://img.shields.io/badge/v1.0.1-blue) | **8** | VNPay — payment gateway (Vietnam) |
| [@theyahia/zalo-oa-mcp](https://www.npmjs.com/package/@theyahia/zalo-oa-mcp) | ![v1.0.1](https://img.shields.io/badge/v1.0.1-blue) | **8** | Zalo OA — official account API (Vietnam) |
| [@theyahia/xendit-mcp](https://www.npmjs.com/package/@theyahia/xendit-mcp) | ![v1.0.1](https://img.shields.io/badge/v1.0.1-blue) | **10** | Xendit — payment gateway (Indonesia/Philippines) |

## MENA — Iran & Pakistan (6 servers)

| Package | Version | Tools | Description |
|---------|---------|-------|-------------|
| [@theyahia/idpay-mcp](https://www.npmjs.com/package/@theyahia/idpay-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **8** | IDPay — payment gateway (Iran) |
| [@theyahia/kavenegar-mcp](https://www.npmjs.com/package/@theyahia/kavenegar-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **8** | Kavenegar — SMS gateway (Iran) |
| [@theyahia/neshan-maps-mcp](https://www.npmjs.com/package/@theyahia/neshan-maps-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **8** | Neshan Maps — geocoding, routing (Iran) |
| [@theyahia/zarinpal-mcp](https://www.npmjs.com/package/@theyahia/zarinpal-mcp) | ![v1.0.1](https://img.shields.io/badge/v1.0.1-blue) | **8** | Zarinpal — payment gateway (Iran) |
| [@theyahia/easypaisa-mcp](https://www.npmjs.com/package/@theyahia/easypaisa-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **8** | Easypaisa — mobile wallet and payments (Pakistan) |
| [@theyahia/jazzcash-mcp](https://www.npmjs.com/package/@theyahia/jazzcash-mcp) | ![v1.0.0](https://img.shields.io/badge/v1.0.0-blue) | **8** | JazzCash — mobile wallet and payments (Pakistan) |

---

## Install in Claude Desktop

```json
{
  "mcpServers": {
    "yookassa": {
      "command": "npx",
      "args": ["-y", "@theyahia/yookassa-mcp"],
      "env": {
        "YOOKASSA_SHOP_ID": "your-shop-id",
        "YOOKASSA_SECRET_KEY": "your-secret-key"
      }
    }
  }
}
```

## Install in Cursor / VS Code

```json
{
  "servers": {
    "yookassa": {
      "command": "npx",
      "args": ["-y", "@theyahia/yookassa-mcp"],
      "env": {
        "YOOKASSA_SHOP_ID": "your-shop-id",
        "YOOKASSA_SECRET_KEY": "your-secret-key"
      }
    }
  }
}
```

## Install in Claude Code

```bash
claude mcp add yookassa -- npx -y @theyahia/yookassa-mcp
```

---

## E-commerce Stack Example

Combine multiple servers for a full e-commerce workflow:

```
1. dadata-mcp      → suggest_company(INN) — verify counterparty
2. moysklad-mcp    → create_customer_order() — create order
3. cdek-mcp        → create_order() — arrange delivery
4. yookassa-mcp    → create_payment() — accept payment
5. atol-online-mcp → create_receipt() — fiscal receipt (54-FZ)
```

---

## Contributing

1. Fork this repo
2. Create a server in `servers/<category>/<name>-mcp/`
3. Follow the existing pattern: `src/index.ts` with `@modelcontextprotocol/sdk`
4. Submit a PR

We especially welcome servers for APIs in underserved regions.

---

## Author

[@theYahia](https://github.com/theYahia) | Telegram: [@vhodvai](https://t.me/vhodvai) | npm: [@theyahia](https://www.npmjs.com/org/theyahia)

## License

MIT
