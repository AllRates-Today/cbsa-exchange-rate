# Canada Border Services Agency Exchange Rates API — cbsa-exchange-rate

[![npm version](https://img.shields.io/npm/v/cbsa-exchange-rate.svg)](https://www.npmjs.com/package/cbsa-exchange-rate)
[![license](https://img.shields.io/npm/l/cbsa-exchange-rate.svg)](https://github.com/AllRates-Today/cbsa-exchange-rate/blob/main/LICENSE)
[![zero dependencies](https://img.shields.io/badge/dependencies-0-brightgreen.svg)](https://www.npmjs.com/package/cbsa-exchange-rate)
[![TypeScript](https://img.shields.io/badge/TypeScript-types%20included-3178C6.svg)](https://www.typescriptlang.org/)
[![USD/CAD today](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fallratestoday.com%2Fapi%2Fopen%2Fcentral-bank%2Fcbsa%3Fsource%3DUSD%26target%3DCAD&query=%24.rate&label=USD%2FCAD%20official%2C%20Canada%20Border%20Services%20Agency&color=0A7E8C&cacheSeconds=3600)](https://allratestoday.com/tax-authority-rates-api/cbsa/)
[![rate date](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fallratestoday.com%2Fapi%2Fopen%2Fcentral-bank%2Fcbsa%3Fsource%3DUSD%26target%3DCAD&query=%24.rate_date&label=rate%20date&color=555&cacheSeconds=3600)](https://allratestoday.com/tax-authority-rates-api/cbsa/)

**Official Canada Border Services Agency (Canada) daily exchange rates for Node.js and TypeScript. The published tax authority rates behind tax filings, customs valuations, audits, and compliant invoicing — not market estimates, but the numbers Canada Border Services Agency itself prints, every business day.**

## 🚀 Why this client?

- 🏛️ **Official rates** — Canada Border Services Agency's own table, with the publisher's own `rate_date` on every response
- 📅 **History back to 2017** — point-in-time tables and daily series for any past date
- 🔀 **Official vs derived, always flagged** — computed inverse/cross pairs carry `derived: true`, never mixed with official prints
- ⚡ **Zero dependencies** — pure ESM + CJS over global `fetch`; Node 18+, Bun, Deno, and edge runtimes
- 🔷 **Type-safe** — full TypeScript definitions shipped with the package
- 🧾 **Compliance-grade metadata** — `rate_type`, publication date, and source disclaimer on every response

> **Official rate, not mid-market:** every value here is a number Canada Border Services Agency itself published, fixed once printed and carrying the tax authority's own `rate_date` — what filings and audits require. Need the live mid-market rate for pricing or display instead? Use the [mid-market API](https://allratestoday.com/docs/) or [`@allratestoday/sdk`](https://www.npmjs.com/package/@allratestoday/sdk). The two can diverge by several percent.

## 🔑 Get your API key

Get a free API key at [allratestoday.com/register](https://allratestoday.com/register) — no credit card required. Latest rates are on every plan, including free.

## 📈 Latest official table

[![Latest Canada Border Services Agency table](https://allratestoday.com/api/open/central-bank/cbsa/table.svg)](https://allratestoday.com/tax-authority-rates-api/cbsa/)

The image is rendered live from the keyless endpoint, so it follows the tax authority's publications on npm and on GitHub alike without a new release. The same table as text is folded below for search and copy-paste: on GitHub [a daily Action](.github/workflows/daily-table.yml) refreshes it whenever the tax authority publishes a new table; on npm it is as of the package's publish date.

<!-- daily-table:start -->
<details>
<summary>Table as text: published 2026-11-28 by Canada Border Services Agency — 137 rates, first 60 shown. Updated 2026-11-28.</summary>

| Base | Quote | Type | Rate |
| --- | --- | --- | ---: |
| AED | CAD | reference | 0.39041 |
| AFN | CAD | reference | 0.02133 |
| ALL | CAD | reference | 0.01687 |
| AMD | CAD | reference | 0.00388 |
| AOA | CAD | reference | 0.00151 |
| ARS | CAD | reference | 0.00091 |
| AUD | CAD | reference | 0.9447 |
| AWG | CAD | reference | 0.77083 |
| AZN | CAD | reference | 0.82184 |
| BBD | CAD | reference | 0.71705 |
| BDT | CAD | reference | 0.01105 |
| BHD | CAD | reference | 3.64409 |
| BIF | CAD | reference | 0.00046 |
| BND | CAD | reference | 1.111 |
| BOB | CAD | reference | 0.11325 |
| BRL | CAD | reference | 0.2483 |
| BSD | CAD | reference | 1.4341 |
| BWP | CAD | reference | 0.09943 |
| BZD | CAD | reference | 0.67754 |
| CDF | CAD | reference | 0.0006 |
| CHF | CAD | reference | 1.7077 |
| CLP | CAD | reference | 0.0014 |
| CNY | CAD | reference | 0.2139 |
| COP | CAD | reference | 0.00041 |
| CRC | CAD | reference | 0.00302 |
| CUP | CAD | reference | 0.05589 |
| CVE | CAD | reference | 0.01413 |
| CZK | CAD | reference | 0.06428 |
| DJF | CAD | reference | 0.00786 |
| DKK | CAD | reference | 0.21041 |
| DOP | CAD | reference | 0.02269 |
| DZD | CAD | reference | 0.01038 |
| EGP | CAD | reference | 0.02665 |
| ERN | CAD | reference | 0.09314 |
| ETB | CAD | reference | 0.00852 |
| EUR | CAD | reference | 1.563 |
| FJD | CAD | reference | 0.61791 |
| FKP | CAD | reference | 1.8704 |
| GBP | CAD | reference | 1.867 |
| GEL | CAD | reference | 0.534 |
| GHS | CAD | reference | 0.12121 |
| GMD | CAD | reference | 0.01866 |
| GNF | CAD | reference | 0.00016 |
| GTQ | CAD | reference | 0.18385 |
| GYD | CAD | reference | 0.00651 |
| HKD | CAD | reference | 0.1817 |
| HNL | CAD | reference | 0.05283 |
| HTG | CAD | reference | 0.0106 |
| HUF | CAD | reference | 0.00421 |
| IDR | CAD | reference | 0.000078 |
| ILS | CAD | reference | 0.42802 |
| INR | CAD | reference | 0.01541 |
| IQD | CAD | reference | 0.00094 |
| ISK | CAD | reference | 0.01144 |
| JMD | CAD | reference | 0.00889 |
| JOD | CAD | reference | 2.02271 |
| JPY | CAD | reference | 0.00894 |
| KES | CAD | reference | 0.01068 |
| KHR | CAD | reference | 0.00035 |
| KPW | CAD | reference | 0.01035 |

</details>

[Full table on the Canada Border Services Agency rates page](https://allratestoday.com/tax-authority-rates-api/cbsa/) · Source: [Official rates published by CBSA, served by AllRatesToday](https://allratestoday.com/tax-authority-rates-api/cbsa/). Rates are as printed by the tax authority; AllRatesToday is not affiliated with it.
<!-- daily-table:end -->

## 📦 Installation

```bash
npm install cbsa-exchange-rate
```

```bash
yarn add cbsa-exchange-rate
```

```bash
pnpm add cbsa-exchange-rate
```

Requires Node 18+ (global `fetch`); also runs on Bun, Deno and edge runtimes. Also published under the org scope as [`@allratestoday/cbsa-exchange-rate`](https://www.npmjs.com/package/@allratestoday/cbsa-exchange-rate) — same code, same versions.

## 🏁 Quick start

```js
import { getRate } from 'cbsa-exchange-rate';

const pair = await getRate('USD', 'CAD', { apiKey: 'art_live_...' });
console.log(pair.rate, pair.rate_date); // the official Canada Border Services Agency rate, on the tax authority's own date
```

## 📚 API reference

- [Latest pair rate](#latest-pair-rate) — one pair from the latest official table
- [Full official table](#full-official-table) — everything the tax authority printed, in one call
- [Table for a date](#table-for-a-date) — the official table for an invoice or filing date
- [Daily time series](#daily-time-series) — one pair across a date range

---

### Latest pair rate

Free plan and up. Pairs the tax authority does not print directly are resolved from its table and flagged (see *Official vs derived rates* below).

```js
const pair = await getRate('USD', 'CAD', { apiKey: 'art_live_...' });
```

**Response:**

```javascript
{
  bank: 'cbsa',
  name: 'Canada Border Services Agency',
  rate_date: '2026-11-25',   // Canada Border Services Agency's own publication date
  source: 'USD',
  target: 'CAD',
  rate: 1.4369,
  rate_type: 'reference',
  derived: false,
  method: 'published',
  disclaimer: 'Official rates as published by the named central bank. On weekends/holidays the most recent published rate_date is returned.'
}
```

### Full official table

Free plan and up. The complete table for the latest publication date.

```js
import { getLatestRates } from 'cbsa-exchange-rate';

const table = await getLatestRates({ apiKey: 'art_live_...' });
console.log(table.rate_date, table.rates.length);
```

**Response:**

```javascript
{
  bank: 'cbsa',
  name: 'Canada Border Services Agency',
  rate_date: '2026-11-25',
  rates: [
    { "base": "USD", "quote": "CAD", "type": "reference", "value": 1.4369 },
    // … the rest of the official table (141 currencies vs CAD)
  ],
  disclaimer: '…'
}
```

### Table for a date

Paid plans. The official table for any date since 2017 — weekends and holidays return the most recent published date, flagged via `published_on_requested_date`, which is exactly the in-force rate a filing needs.

```js
import { getRatesForDate } from 'cbsa-exchange-rate';

const day = await getRatesForDate('2026-06-30', { apiKey: 'art_live_...' });
// Optionally narrow to one pair:
const one = await getRatesForDate('2026-06-30', { apiKey: 'art_live_...', source: 'USD', target: 'CAD' });
```

**Response:**

```javascript
{
  bank: 'cbsa',
  requested_date: '2026-06-30',
  rate_date: '2026-06-30',                // the date actually published
  published_on_requested_date: true,      // false when a weekend/holiday fell back
  rates: [ /* the full table for that date */ ],
  disclaimer: '…'
}
```

### Daily time series

Paid plans. One resolved rate per publication date — ready for charting, revaluation runs, or audit workpapers.

```js
import { getHistory } from 'cbsa-exchange-rate';

const series = await getHistory(
  { source: 'USD', target: 'CAD', from: '2026-01-01', to: '2026-11-25' },
  { apiKey: 'art_live_...' }
);
```

**Response:**

```javascript
{
  bank: 'cbsa',
  source: 'USD',
  target: 'CAD',
  from: '2026-01-01',
  to: '2026-11-25',
  count: 152,
  rates: [
    // one entry per publication date
    { date: '2026-11-25', rate: 1.4369, rate_type: 'reference', derived: false, method: 'published' },
    // …
  ],
  disclaimer: '…'
}
```

Pass `{ symbol: 'USD' }` instead of `source`/`target` to get the raw published rows for one currency (all rate types, no pair resolution).

---

## 🗺️ Currencies covered

Canada Border Services Agency currently publishes rates covering **141 currencies** against the CAD (as of the latest table):

🇦🇪 `AED` · 🇦🇫 `AFN` · 🇦🇱 `ALL` · 🇦🇲 `AMD` · 🇦🇴 `AOA` · 🇦🇷 `ARS` · 🇦🇺 `AUD` · 🇦🇼 `AWG` · 🇦🇿 `AZN` · 🇧🇧 `BBD` · 🇧🇩 `BDT` · 🇧🇬 `BGN` · 🇧🇭 `BHD` · 🇧🇮 `BIF` · 🇧🇳 `BND` · 🇧🇴 `BOB` · 🇧🇷 `BRL` · 🇧🇸 `BSD` · 🇧🇼 `BWP` · 🇧🇿 `BZD` · 🇨🇩 `CDF` · 🇨🇭 `CHF` · 🇨🇱 `CLP` · 🇨🇳 `CNY` · 🇨🇴 `COP` · 🇨🇷 `CRC` · 🇨🇺 `CUP` · 🇨🇻 `CVE` · 🇨🇿 `CZK` · 🇩🇯 `DJF` · 🇩🇰 `DKK` · 🇩🇴 `DOP` · 🇩🇿 `DZD` · 🇪🇬 `EGP` · 🇪🇷 `ERN` · 🇪🇹 `ETB` · 🇪🇺 `EUR` · 🇫🇯 `FJD` · 🇫🇰 `FKP` · 🇬🇧 `GBP` · 🇬🇪 `GEL` · 🇬🇭 `GHS` · 🇬🇲 `GMD` · 🇬🇳 `GNF` · 🇬🇹 `GTQ` · 🇬🇾 `GYD` · 🇭🇰 `HKD` · 🇭🇳 `HNL` · 🇭🇹 `HTG` · 🇭🇺 `HUF` · 🇮🇩 `IDR` · 🇮🇱 `ILS` · 🇮🇳 `INR` · 🇮🇶 `IQD` · 🇮🇷 `IRR` · 🇮🇸 `ISK` · 🇯🇲 `JMD` · 🇯🇴 `JOD` · 🇯🇵 `JPY` · 🇰🇪 `KES` · 🇰🇭 `KHR` · 🇰🇵 `KPW` · 🇰🇷 `KRW` · 🇰🇼 `KWD` · 🇰🇾 `KYD` · 🇰🇿 `KZT` · 🇱🇦 `LAK` · 🇱🇧 `LBP` · 🇱🇰 `LKR` · 🇱🇸 `LSL` · 🇱🇾 `LYD` · 🇲🇦 `MAD` · 🇲🇩 `MDL` · 🇲🇬 `MGA` · 🇲🇲 `MMK` · 🇲🇳 `MNT` · 🇲🇴 `MOP` · 🇲🇷 `MRU` · 🇲🇺 `MUR` · 🇲🇻 `MVR` · 🇲🇼 `MWK` · 🇲🇽 `MXN` · 🇲🇾 `MYR` · 🇲🇿 `MZN` · 🇳🇦 `NAD` · 🇳🇬 `NGN` · 🇳🇮 `NIO` · 🇳🇴 `NOK` · 🇳🇵 `NPR` · 🇳🇿 `NZD` · 🇴🇲 `OMR` · 🇵🇦 `PAB` · 🇵🇪 `PEN` · 🇵🇬 `PGK` · 🇵🇭 `PHP` · 🇵🇰 `PKR` · 🇵🇱 `PLN` · 🇵🇾 `PYG` · 🇶🇦 `QAR` · 🇷🇴 `RON` · 🇷🇸 `RSD` · 🇷🇺 `RUB` · 🇷🇼 `RWF` · 🇸🇦 `SAR` · 🇸🇨 `SCR` · 🇸🇩 `SDG` · 🇸🇪 `SEK` · 🇸🇬 `SGD` · 🇸🇱 `SLL` · 🇸🇴 `SOS` · 🇸🇷 `SRD` · 🇸🇹 `STN` · 🇸🇻 `SVC` · 🇸🇾 `SYP` · 🇸🇿 `SZL` · 🇹🇭 `THB` · 🇹🇯 `TJS` · 🇹🇲 `TMT` · 🇹🇳 `TND` · 🇹🇴 `TOP` · 🇹🇷 `TRY` · 🇹🇹 `TTD` · 🇹🇼 `TWD` · 🇹🇿 `TZS` · 🇺🇦 `UAH` · 🇺🇬 `UGX` · 🇺🇸 `USD` · 🇺🇾 `UYU` · 🇺🇿 `UZS` · 🇻🇪 `VES` · 🇻🇳 `VND` · 🇻🇺 `VUV` · 🇼🇸 `WST` · `XAF` · `XCD` · `XCG` · `XOF` · `XPF` · 🇾🇪 `YER` · 🇿🇦 `ZAR` · 🇿🇲 `ZMW`

## 🏛️ Source

The exchange rates the Canada Border Services Agency prescribes, under the Currency Exchange for Customs Valuation Regulations, for converting foreign-currency invoice values into Canadian dollars. Importers and brokers must use the rate in force on the date of direct shipment to value goods for duty and GST.

- Publisher's own page: [Daily exchange rates for customs and tax](https://ccp-pcc.cbsa-asfc.cloud-nuage.canada.ca/en/exchange-rates) · [ccp-pcc.cbsa-asfc.cloud-nuage.canada.ca](https://ccp-pcc.cbsa-asfc.cloud-nuage.canada.ca/)
- Publication: every business day; the exact schedule, freshness status and any current delay are on the [Canada Border Services Agency rates page](https://allratestoday.com/tax-authority-rates-api/cbsa/)
- Values are stored unmodified, with the publisher's own `rate_date` on every row — see the [methodology](https://allratestoday.com/official-rates-methodology/)

## 🧭 Reading the numbers

- `value` is always **quote currency per 1 unit of base currency** (`base: "EUR", quote: "USD", value: 1.15` means 1 EUR = 1.15 USD).
- Canada Border Services Agency quotes **CAD per 1 unit of foreign currency** (e.g. `base: "USD", quote: "CAD"` means CAD per one US dollar).
- Need the other way round? Ask `getRate(target, source)` and the API inverts or crosses for you, flagged `derived: true` — never divide a published rate yourself in a compliance workflow.
- `rate_type` tells you which of the tax authority's series a row belongs to (`reference` here); some publishers print buy/sell or several fixings for the same pair.

## 🧩 ERP & accounting systems

Loading the official Canada Border Services Agency rate into an accounting system is a supported workflow, not a hack. Step-by-step guides with the direction each system expects:

- [Dynamics 365 Business Central](https://allratestoday.com/docs/integrations/business-central/) — built-in Currency Exchange Rate Service, no code
- [Xero](https://allratestoday.com/docs/integrations/xero/) · [QuickBooks Online](https://allratestoday.com/docs/integrations/quickbooks/) · [SAP S/4HANA and ECC](https://allratestoday.com/docs/integrations/sap/) · [Odoo](https://allratestoday.com/docs/integrations/odoo/)

The same keyed endpoints return `?format=csv`, `?format=xml` and `?format=xlsx`, and accept the key as `?api_key=` on the URL for importers that cannot send headers:

```bash
curl "https://allratestoday.com/api/v1/central-bank/cbsa/latest?format=xml&api_key=art_live_..."
```

## 🤖 AI agents

- MCP server: `npx -y @allratestoday/central-bank-mcp` (stdio) or the hosted endpoint `https://allratestoday.com/api/mcp` — tools for official rates, history, cross-bank comparison and publication calendars
- Already using the general SDK or MCP server? Since 2026-10-01 [`@allratestoday/sdk`](https://www.npmjs.com/package/@allratestoday/sdk) 1.4+ has `officialRates('cbsa')` and [`@allratestoday/mcp-server`](https://www.npmjs.com/package/@allratestoday/mcp-server) 0.6+ has a `get_official_rates` tool — both return this source's latest table with no key, so you can add it without a second dependency
- Claude Code plugin (no key): `/plugin marketplace add AllRates-Today/claude-code-plugin` then `/plugin install allratestoday@allratestoday` — bundles both MCP servers plus an `/official-rate cbsa ...` command
- Evaluating? Agents can self-issue a trial key with no signup: `POST https://allratestoday.com/api/agent/keys` (send `Content-Type: application/json`) returns a 100-call key valid 7 days that covers the free-plan methods (latest table, pairs); dated tables and history need a [paid plan](https://allratestoday.com/pricing/). The MCP servers expose it as `request_trial_key`
- Machine-readable site guide: [llms.txt](https://allratestoday.com/llms.txt) · [for-ai-agents](https://allratestoday.com/for-ai-agents/)

## ⚖️ Official vs derived rates

If Canada Border Services Agency does not print a pair directly, the API resolves it from the tax authority's own table and says so — official and computed values are never confused:

| `method` | `derived` | Meaning |
| --- | --- | --- |
| `published` | `false` | The tax authority printed this pair directly |
| `inverse` | `true` | Computed as 1 ÷ the published opposite direction |
| `cross` | `true` | Computed via CAD from two published rates |

## 🛡️ Error handling

Errors are thrown as `Error` with `status` (HTTP code) and `body` (the API's JSON error) attached:

```js
try {
  const pair = await getRate('USD', 'XXX', { apiKey: 'art_live_...' });
} catch (err) {
  console.log(err.message); // human-readable reason
  console.log(err.status);  // e.g. 404
}
```

| Status | Meaning |
| ------ | ------- |
| — | Missing `apiKey` (thrown before any request) |
| `400` | Malformed date or parameters |
| `401` | Invalid API key |
| `403` | Endpoint needs a [paid plan](https://allratestoday.com/pricing/) (historical dates & series) |
| `404` | Pair or date range not covered by Canada Border Services Agency |
| `429` | Monthly quota exceeded |

## 🔷 TypeScript

Full definitions ship with the package — no `@types` install:

```ts
import type { LatestRates, PairRate, DatedRates, RateEntry, HistoryQuery, RequestOptions } from 'cbsa-exchange-rate';
```

## 📦 CommonJS

```javascript
const { getRate } = require('cbsa-exchange-rate');

getRate('USD', 'CAD', { apiKey: 'art_live_...' }).then((pair) => console.log(pair.rate));
```

## 💡 Quota tips

- Rates change once per business day — cache the official table locally and a small monthly quota goes a long way.
- Every request counts toward your AllRatesToday quota, shared across all AllRatesToday endpoints on your key.

## 📖 Methods reference

| Method | Plan | Description |
| ------ | ---- | ----------- |
| `getRate(source, target, { apiKey })` | Free | Latest rate for one pair, resolved from the official table |
| `getLatestRates({ apiKey })` | Free | The tax authority's full latest official table |
| `getRatesForDate(date, { apiKey, source?, target? })` | Paid | The official table (or one pair) for a YYYY-MM-DD date |
| `getHistory({ symbol \| source+target, from?, to? }, { apiKey })` | Paid | Daily series since 2017 |

## 📥 Bulk data (no key)

Need the whole archive rather than an API call? The same official tables are mirrored daily as open data:

- Hugging Face: [AllRatesToday/central-bank-exchange-rates](https://huggingface.co/datasets/AllRatesToday/central-bank-exchange-rates) — one CSV per institution (`rates/cbsa.csv`)
- Kaggle: [allratestoday/central-bank-exchange-rates](https://www.kaggle.com/datasets/allratestoday/central-bank-exchange-rates)
- Raw JSON on GitHub: `https://raw.githubusercontent.com/AllRates-Today/central-bank-exchange-rates/main/data/cbsa/latest.json`

## 🔗 Links

- **Website:** [allratestoday.com](https://allratestoday.com)
- [Canada Border Services Agency rates page](https://allratestoday.com/tax-authority-rates-api/cbsa/) — live table, publication cadence, FAQ
- [All tax authority sources](https://allratestoday.com/tax-authority-rates-api/) · [Full list of 120+ central banks and 50+ tax authorities](https://allratestoday.com/central-bank-rates-api/institutions/) — one API, the same response shape for every source
- [Download central bank rates](https://allratestoday.com/download-central-bank-rates/) — every bank's latest table and history as Excel, CSV or JSON
- [Bank Exchange Rate API](https://allratestoday.com/bank-exchange-rate-api/) — live buy and sell rates from 1,200+ commercial banks in 120+ countries · [npm](https://www.npmjs.com/package/bank-exchange-rates) · [GitHub](https://github.com/AllRates-Today/bank-exchange-rates)
- [Package docs on the site](https://allratestoday.com/docs/sdk/cbsa-exchange-rate/) · [ERP integration guides](https://allratestoday.com/docs/integrations/)
- [API documentation](https://allratestoday.com/docs/#central-bank) · [Interactive reference](https://allratestoday.com/api-reference/) · [Methodology](https://allratestoday.com/official-rates-methodology/)
- [Register (Free)](https://allratestoday.com/register) · [Dashboard](https://allratestoday.com/profile) · [Pricing](https://allratestoday.com/pricing/)
- [Status](https://allratestoday.com/status)
- [Postman collection](https://allratestoday.com/postman/)
- [ChatGPT app](https://chatgpt.com/plugins/plugin_asdk_app_6ae1e76098f48191a285ac3f5ab7a83b) — ask ChatGPT for live and official central bank rates
- [OpenAPI reference on Bump.sh](https://bump.sh/allratestoday/doc/allratestoday-api) — also on [SwaggerHub](https://app.swaggerhub.com/apis-docs/allratestoday/allratestoday-exchange-rate-central-bank-rates-api/2.2.0)
- [GitHub](https://github.com/AllRates-Today/cbsa-exchange-rate)

## 📜 License

MIT
