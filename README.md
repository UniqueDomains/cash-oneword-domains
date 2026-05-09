# Available .CASH One-Word Domains (11,427)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C427%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .cash one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,427 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,427 domains · **Median ask:** $23.72 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-09  
**Canonical page:** `https://unique.domains/domains/tld/cash`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/cash?utm_source=github&utm_medium=referral&utm_campaign=repo_cash_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./cash.csv">CSV</a> / <a href="./cash.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_cash_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_cash_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .CASH search](https://unique.domains/domains/tld/cash?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_cash_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .CASH search](https://unique.domains/domains/tld/cash?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_cash_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_cash_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .CASH one-word domain catalog.

### Files

- `cash.csv` — public CSV extract (1,000 rows)
- `cash.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/cash-oneword-domains/main/cash.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain        | status    | ask_price | renewal_price | attractiveness | demand | length | registrar        |
| ------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------- |
| Acup.cash     | available | $50.98    | —             | 80             | 5      | 5      | namecheap        |
| Trex.cash     | available | $50.98    | —             | 80             | 24     | 5      | namecheap        |
| jewels.cash   | available | $17.99    | —             | 80             | 15     | 6      | name.com         |
| barup.cash    | available | $17.99    | —             | 82             | 2      | 6      | name.com         |
| getup.cash    | available | $17.99    | —             | 82             | 14     | 6      | name.com         |
| Apples.cash   | available | $50.98    | —             | 90             | 16     | 6      | namecheap        |
| useit.cash    | available | $17.99    | —             | 94             | 7      | 6      | name.com         |
| dogsit.cash   | available | $17.99    | —             | 96             | 2      | 6      | name.com         |
| gearup.cash   | available | $17.99    | —             | 80             | 16     | 7      | name.com         |
| QandA.cash    | available | $50.98    | —             | 80             | 10     | 7      | namecheap        |
| toneup.cash   | available | $17.99    | —             | 80             | 5      | 7      | name.com         |
| hangon.cash   | available | $17.99    | —             | 82             | 6      | 7      | name.com         |
| makeit.cash   | available | $17.99    | —             | 82             | 22     | 7      | name.com         |
| dogsick.cash  | available | $17.99    | —             | 90             | 1      | 7      | name.com         |
| getlife.cash  | available | $17.99    | —             | 80             | 5      | 8      | name.com         |
| messages.cash | available | $17.99    | —             | 80             | 16     | 8      | name.com         |
| rumcake.cash  | available | $17.99    | —             | 81             | 3      | 8      | name.com         |
| FabFour.cash  | available | $17.99    | —             | 82             | 3      | 8      | name.com         |
| RGB.cash      | available | $50.98    | —             | 76             | 39     | 3      | namecheap        |
| tribute.cash  | resell    | —         | —             | 74             | 19     | 7      | GoDaddy.com, LLC |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 11,427 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/cash?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_cash_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/cash?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_cash_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_cash_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain` — Fully qualified domain name.
- `status` — Current acquisition state for the domain in the public extract.
- `purchase_price` — Visible purchase price when available.
- `renewal_price` — Visible renewal price when available.
- `attractiveness` — Composite naming score used as a decision-support signal.
- `demand` — Relative buyer-pressure score when available.
- `length` — Character count without the TLD.
- `registrar` — Registrar name when known.
- `created_at` — Creation timestamp when known.
- `expires_at` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This selection is entirely made up of one-word .cash domains. That creates a narrow but useful naming set for buyers who want a direct financial cue in the extension and a single-word brand in the label. Examples in this set range from broad terms such as finals.cash and jewels.cash to more distinctive options like Acup.cash and Trex.cash. The median ask is 23.72, so price is generally accessible, but low ask alone is not enough. When comparing these domains, weigh word quality, memorability, category fit, and possible trademark exposure. Terms that are generic, easy to say, and commercially flexible usually deserve the closest look.

- All domains in this selection use the .cash extension
- Each name is a single word with direct brand potential
- Median ask is 23.72 across 11,421 domains
- Check genericity, recall, and trademark risk first

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .CASH One-Word Domains*. Version 2026-05-09. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .CASH page](https://unique.domains/domains/tld/cash?utm_source=github&utm_medium=referral&utm_campaign=repo_cash_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_cash_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_cash_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_cash_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
