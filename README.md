# Available .PROPERTIES One-Word Domains (12,042)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C042%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .properties one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,042 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,042 domains · **Median ask:** $22.17 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
**Canonical page:** `https://unique.domains/domains/tld/properties`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/properties?utm_source=github&utm_medium=referral&utm_campaign=repo_properties_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./properties.csv">CSV</a> / <a href="./properties.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_properties_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_properties_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .PROPERTIES search](https://unique.domains/domains/tld/properties?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_properties_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .PROPERTIES search](https://unique.domains/domains/tld/properties?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_properties_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_properties_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .PROPERTIES one-word domain catalog.

### Files

- `properties.csv` — public CSV extract (1,000 rows)
- `properties.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/properties-oneword-domains/main/properties.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain                 | status    | ask_price | renewal_price | attractiveness | demand | length | registrar    |
| ---------------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------ |
| skills.properties      | available | $10.99    | —             | 58             | 47     | 6      | name.com     |
| online.properties      | resell    | —         | —             | 70             | 62     | 7      | Sav.com, LLC |
| cars.properties        | premium   | $250      | —             | 66             | 47     | 4      | name.com     |
| tokens.properties      | available | $10.99    | —             | 51             | 36     | 6      | name.com     |
| WhiteHouse.properties  | resell    | —         | —             | 66             | 33     | 11     | Dynadot Inc  |
| events.properties      | premium   | $250      | —             | 68             | 37     | 6      | name.com     |
| Cats.properties        | available | $43.98    | —             | 59             | 33     | 4      | namecheap    |
| solutions.properties   | premium   | $250      | —             | 56             | 31     | 9      | name.com     |
| letsgo.properties      | available | $10.99    | —             | 57             | 31     | 7      | name.com     |
| toys.properties        | premium   | $242      | $242          | 60             | 24     | 4      | namesilo     |
| popup.properties       | available | $10.99    | —             | 84             | 29     | 6      | name.com     |
| holidays.properties    | premium   | $242      | $242          | 78             | 23     | 8      | namesilo     |
| quotes.properties      | available | $10.99    | —             | 58             | 29     | 6      | name.com     |
| restaurants.properties | premium   | $250      | —             | 57             | 21     | 11     | name.com     |
| gems.properties        | available | $10.99    | —             | 70             | 28     | 4      | name.com     |
| webs.properties        | premium   | $242      | $242          | 56             | 21     | 4      | namesilo     |
| forms.properties       | available | $10.99    | —             | 54             | 28     | 5      | name.com     |
| pools.properties       | premium   | $250      | —             | 61             | 19     | 5      | name.com     |
| pages.properties       | available | $10.99    | —             | 52             | 28     | 5      | name.com     |
| rocks.properties       | premium   | $250      | —             | 78             | 18     | 5      | name.com     |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,042 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/properties?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_properties_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/properties?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_properties_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_properties_oneword_domains&utm_content=related_pricing)

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

This selection is entirely made up of one-word .properties domains. The extension gives each name an immediate real-estate or property-related frame, so the word before the dot matters more than usual. Clear category words such as "massage.properties" or "science.properties" read very differently from personal names like "lucy.properties" or loaded terms like "fraud.properties." For founders, the best picks are memorable, easy to explain, and commercially credible. For investors, the better candidates are words with broad use, clean semantics, and realistic pricing discipline. The median ask is 22.17, but quality still depends on relevance, tone, and renewal fit over time.

- Prefer words that fit property use cases clearly
- Avoid negative or confusing terms in this extension
- Personal names are narrower than broad category words
- Check ask price against long-term renewal comfort

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .PROPERTIES One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .PROPERTIES page](https://unique.domains/domains/tld/properties?utm_source=github&utm_medium=referral&utm_campaign=repo_properties_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_properties_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_properties_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_properties_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
