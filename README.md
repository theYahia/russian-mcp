# Russian API MCP — 50 серверов для российских API

> Open-source MCP-серверы для подключения AI-агентов к российским сервисам. Работают с Claude, ChatGPT, Cursor, VS Code, Windsurf и другими MCP-клиентами.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Servers](https://img.shields.io/badge/MCP_Servers-50-blue)
![Tools](https://img.shields.io/badge/Tools-368-green)
[![npm org](https://img.shields.io/badge/npm-@theyahia-red)](https://www.npmjs.com/org/theyahia)

**npm:** [@theyahia](https://www.npmjs.com/org/theyahia) · **Автор:** [@theYahia](https://github.com/theYahia)

---

## Recently upgraded to v2.0

10 серверов полностью переработаны до production-grade уровня: расширенное покрытие API, обработка ошибок, пагинация, фильтрация.

| Пакет | Tools v1 | Tools v2 | Что нового |
|-------|----------|----------|------------|
| yookassa-mcp | 10 | **20** | Рекурренты, сплиты, персональные данные |
| moysklad-mcp | 4 | **21** | Остатки, отчёты, перемещения, инвентаризация |
| amocrm-mcp | 5 | **19** | Задачи, каталоги, webhooks, теги |
| hh-mcp | 6 | **16** | Отклики, резюме, аналитика зарплат |
| yandex-metrika-mcp | 4 | **15** | Цели, сегменты, воронки, отчёты |
| retailcrm-mcp | 3 | **15** | Заказы, товары, задачи, аналитика |
| cdek-mcp | 6 | **14** | Офисы, тарифы, печатные формы, webhooks |
| tkassa-mcp | 5 | **14** | Возвраты, нотификации, QR-коды |
| cloudpayments-mcp | 6 | **12** | Подписки, токены, 3DS, Apple/Google Pay |
| travelpayouts-mcp | 3 | **11** | Авиа, отели, направления, календарь цен |

---

## Платежи

| Пакет | Статус | Tools | Описание |
|-------|--------|-------|----------|
| [@theyahia/yookassa-mcp](https://www.npmjs.com/package/@theyahia/yookassa-mcp) | ✅ v2.0 | **20** | Платежи, возвраты, чеки 54-ФЗ, рекурренты, сплиты |
| [@theyahia/tkassa-mcp](https://www.npmjs.com/package/@theyahia/tkassa-mcp) | ✅ v2.0 | **14** | T-Kassa (Tinkoff) платежи, возвраты, QR-коды |
| [@theyahia/robokassa-mcp](https://www.npmjs.com/package/@theyahia/robokassa-mcp) | ✅ v1.0 | **2** | Робокасса |
| [@theyahia/cloudpayments-mcp](https://www.npmjs.com/package/@theyahia/cloudpayments-mcp) | ✅ v2.0 | **12** | CloudPayments, подписки, токены, 3DS |

## Данные и обогащение

| Пакет | Статус | Tools | Описание |
|-------|--------|-------|----------|
| [@metarebalance/dadata-mcp](https://www.npmjs.com/package/@metarebalance/dadata-mcp) | ✅ v1.0 | **31** | Адреса, компании, банки, телефоны, паспорта |
| [@theyahia/kontur-focus-mcp](https://www.npmjs.com/package/@theyahia/kontur-focus-mcp) | ✅ v1.0 | **4** | Проверка контрагентов |
| [@theyahia/cbr-mcp](https://www.npmjs.com/package/@theyahia/cbr-mcp) | ✅ v1.0 | **5** | Курсы валют, ключевая ставка, металлы, конвертация |
| [@theyahia/chestnyznak-mcp](https://www.npmjs.com/package/@theyahia/chestnyznak-mcp) | ✅ v1.0 | **2** | Маркировка товаров |

## CRM и управление

| Пакет | Статус | Tools | Описание |
|-------|--------|-------|----------|
| [@theyahia/amocrm-mcp](https://www.npmjs.com/package/@theyahia/amocrm-mcp) | ✅ v2.0 | **19** | Сделки, контакты, воронки, задачи, webhooks |
| [@theyahia/bitrix24-mcp](https://www.npmjs.com/package/@theyahia/bitrix24-mcp) | ✅ v1.0 | **12** | CRM, задачи, диск |
| [@theyahia/moysklad-mcp](https://www.npmjs.com/package/@theyahia/moysklad-mcp) | ✅ v2.0 | **21** | Склад, заказы, остатки, отчёты, инвентаризация |
| [@theyahia/retailcrm-mcp](https://www.npmjs.com/package/@theyahia/retailcrm-mcp) | ✅ v2.0 | **15** | Розничная CRM, заказы, товары, аналитика |
| [@theyahia/megaplan-mcp](https://www.npmjs.com/package/@theyahia/megaplan-mcp) | ✅ v1.0 | **7** | CRM и управление проектами |
| [@theyahia/planfix-mcp](https://www.npmjs.com/package/@theyahia/planfix-mcp) | ✅ v1.0 | **6** | Управление проектами |
| [@theyahia/kaiten-mcp](https://www.npmjs.com/package/@theyahia/kaiten-mcp) | ✅ v1.0 | **5** | Канбан и управление проектами |
| [@theyahia/elma365-mcp](https://www.npmjs.com/package/@theyahia/elma365-mcp) | ✅ v1.0 | **6** | BPM платформа |

## Доставка и логистика

| Пакет | Статус | Tools | Описание |
|-------|--------|-------|----------|
| [@theyahia/cdek-mcp](https://www.npmjs.com/package/@theyahia/cdek-mcp) | ✅ v2.0 | **14** | Расчёт, создание, трекинг, офисы, тарифы |
| [@theyahia/boxberry-mcp](https://www.npmjs.com/package/@theyahia/boxberry-mcp) | ✅ v1.0 | **5** | Доставка |
| [@theyahia/delovye-linii-mcp](https://www.npmjs.com/package/@theyahia/delovye-linii-mcp) | ✅ v1.0 | **4** | Грузоперевозки |
| [@theyahia/pochta-russia-mcp](https://www.npmjs.com/package/@theyahia/pochta-russia-mcp) | ✅ v1.0 | **6** | Почта России |

## Маркетинг и аналитика

| Пакет | Статус | Tools | Описание |
|-------|--------|-------|----------|
| [@theyahia/yandex-metrika-mcp](https://www.npmjs.com/package/@theyahia/yandex-metrika-mcp) | ✅ v2.0 | **15** | Аналитика сайта, цели, сегменты, воронки |
| [@theyahia/yandex-direct-mcp](https://www.npmjs.com/package/@theyahia/yandex-direct-mcp) | ✅ v1.0 | **8** | Контекстная реклама |
| [@theyahia/yandex-webmaster-mcp](https://www.npmjs.com/package/@theyahia/yandex-webmaster-mcp) | ✅ v1.0 | **5** | SEO и вебмастер |
| [@theyahia/unisender-mcp](https://www.npmjs.com/package/@theyahia/unisender-mcp) | ✅ v1.0 | **7** | Email и SMS рассылки |
| [@theyahia/sendpulse-mcp](https://www.npmjs.com/package/@theyahia/sendpulse-mcp) | ✅ v1.0 | **6** | Email/SMS маркетинг |
| [@theyahia/roistat-mcp](https://www.npmjs.com/package/@theyahia/roistat-mcp) | ✅ v1.0 | **5** | Сквозная аналитика |
| [@theyahia/calltouch-mcp](https://www.npmjs.com/package/@theyahia/calltouch-mcp) | ✅ v1.0 | **4** | Коллтрекинг |
| [@theyahia/mindbox-mcp](https://www.npmjs.com/package/@theyahia/mindbox-mcp) | ✅ v1.0 | **6** | CDP платформа |

## HR и рекрутинг

| Пакет | Статус | Tools | Описание |
|-------|--------|-------|----------|
| [@theyahia/hh-mcp](https://www.npmjs.com/package/@theyahia/hh-mcp) | ✅ v2.0 | **16** | Вакансии, резюме, отклики, аналитика зарплат |
| [@theyahia/superjob-mcp](https://www.npmjs.com/package/@theyahia/superjob-mcp) | ✅ v1.0 | **2** | Вакансии |
| [@theyahia/huntflow-mcp](https://www.npmjs.com/package/@theyahia/huntflow-mcp) | ✅ v1.0 | **4** | Вакансии, кандидаты |

## Коммуникации

| Пакет | Статус | Tools | Описание |
|-------|--------|-------|----------|
| [@theyahia/vk-mcp](https://www.npmjs.com/package/@theyahia/vk-mcp) | ✅ v1.0 | **8** | Соцсеть ВКонтакте |
| [@theyahia/jivosite-mcp](https://www.npmjs.com/package/@theyahia/jivosite-mcp) | ✅ v1.0 | **4** | Онлайн-чат |
| [@theyahia/mts-exolve-mcp](https://www.npmjs.com/package/@theyahia/mts-exolve-mcp) | ✅ v1.0 | **5** | Телефония и SMS |
| [@theyahia/mango-office-mcp](https://www.npmjs.com/package/@theyahia/mango-office-mcp) | ✅ v1.0 | **5** | Виртуальная АТС |
| [@theyahia/voximplant-mcp](https://www.npmjs.com/package/@theyahia/voximplant-mcp) | ✅ v1.0 | **6** | Облачные коммуникации |
| [@theyahia/sms-ru-mcp](https://www.npmjs.com/package/@theyahia/sms-ru-mcp) | ✅ v1.0 | **3** | SMS-рассылки |
| [@theyahia/tilda-mcp](https://www.npmjs.com/package/@theyahia/tilda-mcp) | ✅ v1.0 | **4** | Конструктор сайтов |

## AI и ML

| Пакет | Статус | Tools | Описание |
|-------|--------|-------|----------|
| [@theyahia/gigachat-mcp](https://www.npmjs.com/package/@theyahia/gigachat-mcp) | ✅ v1.0 | **4** | GigaChat (Сбер) |
| [@theyahia/yandexgpt-mcp](https://www.npmjs.com/package/@theyahia/yandexgpt-mcp) | ✅ v1.0 | **4** | YandexGPT |
| [@theyahia/salutespeech-mcp](https://www.npmjs.com/package/@theyahia/salutespeech-mcp) | ✅ v1.0 | **3** | Распознавание речи (Сбер) |
| [@theyahia/yandex-speechkit-mcp](https://www.npmjs.com/package/@theyahia/yandex-speechkit-mcp) | ✅ v1.0 | **3** | Распознавание речи (Яндекс) |

## Финансы и учёт

| Пакет | Статус | Tools | Описание |
|-------|--------|-------|----------|
| [@theyahia/sber-mcp](https://www.npmjs.com/package/@theyahia/sber-mcp) | ✅ v1.0 | **5** | Сбер API |
| [@theyahia/1c-rest-mcp](https://www.npmjs.com/package/@theyahia/1c-rest-mcp) | ✅ v1.0 | **6** | 1С REST API |

## Другое

| Пакет | Статус | Tools | Описание |
|-------|--------|-------|----------|
| [@theyahia/travelpayouts-mcp](https://www.npmjs.com/package/@theyahia/travelpayouts-mcp) | ✅ v2.0 | **11** | Авиа, отели, направления, календарь цен |
| [@theyahia/kaspi-mcp](https://www.npmjs.com/package/@theyahia/kaspi-mcp) | ✅ v1.0 | **4** | Kaspi.kz (Казахстан) |
| [@theyahia/getcourse-mcp](https://www.npmjs.com/package/@theyahia/getcourse-mcp) | ✅ v1.0 | **5** | Онлайн-школы |

---

## Быстрый старт

Любой MCP из серии подключается одинаково. Пример для `dadata-mcp`:

### Claude Desktop

```json
{
  "mcpServers": {
    "dadata": {
      "command": "npx",
      "args": ["-y", "@metarebalance/dadata-mcp"],
      "env": {
        "DADATA_API_KEY": "ваш-ключ"
      }
    }
  }
}
```

### Claude Code

```bash
claude mcp add dadata -- npx -y @metarebalance/dadata-mcp
```

### VS Code / Cursor

```json
{
  "servers": {
    "dadata": {
      "command": "npx",
      "args": ["-y", "@metarebalance/dadata-mcp"],
      "env": {
        "DADATA_API_KEY": "ваш-ключ"
      }
    }
  }
}
```

---

## E-commerce стек — пример совместной работы

```
1. dadata-mcp:   suggest_company(ИНН) → проверить контрагента
2. moysklad-mcp: create_customer_order() → оформить заказ
3. cdek-mcp:     create_order() → создать доставку
4. yookassa-mcp: create_payment() → принять оплату
```

---

## E-commerce и маркетплейсы (SOON)

| Пакет | Статус | Tools | Описание |
|-------|--------|-------|----------|
| [@theyahia/ozon-mcp](https://www.npmjs.com/package/@theyahia/ozon-mcp) | 📅 SOON | 12 | Товары, цены, аналитика, FBO/FBS |
| [@theyahia/wildberries-mcp](https://www.npmjs.com/package/@theyahia/wildberries-mcp) | 📅 SOON | — | Товары, заказы, аналитика |
| [@theyahia/yandex-market-mcp](https://www.npmjs.com/package/@theyahia/yandex-market-mcp) | 📅 SOON | — | Маркетплейс Яндекса |
| [@theyahia/insales-mcp](https://www.npmjs.com/package/@theyahia/insales-mcp) | 📅 SOON | — | E-commerce платформа |

---

## Автор

[@theYahia](https://github.com/theYahia) — серия open-source MCP-серверов для российских API.

Telegram: [@vhodvai](https://t.me/vhodvai)

## Лицензия

MIT
