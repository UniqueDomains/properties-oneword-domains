# Available .PROPERTIES One-Word Domains (33,312)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-33%2C312%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .properties one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **33,312 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 33,312 domains · **Median ask:** $24.18 · **High-demand under $2,500:** 5

**Last updated:** 2026-10-03
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

- `properties.csv`, public CSV extract (1,000 rows)
- `properties.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/properties-oneword-domains/main/properties.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain              | status    | ask_price | renewal_price | attractiveness | demand | length | registrar        |
| ------------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------- |
| aar.properties      | available | $18.99    | $39.99        | medium         | low    | 3      | namesilo         |
| weed.properties     | resell    | —         | —             | high           | medium | 4      | GoDaddy.com, LLC |
| ad.properties       | premium   | $828.20   | $828.20       | high           | medium | 3      | spaceship        |
| aec.properties      | available | $18.99    | $39.99        | high           | low    | 3      | namesilo         |
| launch.properties   | resell    | —         | —             | high           | medium | 6      | GoDaddy.com, LLC |
| age.properties      | premium   | $78.54    | $78.54        | high           | low    | 3      | namesilo         |
| ann.properties      | available | $6.10     | $32.21        | high           | low    | 3      | dynadot          |
| stream.properties   | resell    | —         | —             | high           | medium | 6      | —                |
| cod.properties      | premium   | $85.80    | $85.80        | high           | low    | 3      | namecheap        |
| bev.properties      | available | $14.17    | $31.25        | high           | low    | 3      | spaceship        |
| everyday.properties | resell    | —         | —             | high           | low    | 8      | GoDaddy.com, LLC |
| hee.properties      | premium   | $68.51    | $68.51        | high           | low    | 3      | spaceship        |
| cso.properties      | available | $15.98    | $43.98        | high           | low    | 3      | namecheap        |
| hum.properties      | premium   | $72.60    | $72.60        | high           | low    | 3      | dynadot          |
| epp.properties      | available | $14.17    | $31.25        | high           | low    | 3      | spaceship        |
| ias.properties      | premium   | $72.60    | $72.60        | high           | low    | 3      | dynadot          |
| fda.properties      | available | $18.99    | $39.99        | high           | low    | 3      | namesilo         |
| law.properties      | premium   | $260      | $260          | high           | medium | 3      | namecheap        |
| fis.properties      | available | $30.20    | $30.20        | high           | low    | 3      | cloudflare       |
| pip.properties      | premium   | $78.54    | $78.54        | high           | low    | 3      | namesilo         |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 33,312 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 5 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/properties?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_properties_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/properties?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_properties_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_properties_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain`, Fully qualified domain name.
- `status`, Current acquisition state for the domain in the public extract.
- `purchase_price`, Visible purchase price when available.
- `renewal_price`, Visible renewal price when available.
- `attractiveness`, Public composite naming band used as a decision-support signal.
- `demand`, Public buyer-pressure band when available.
- `length`, Character count without the TLD.
- `registrar`, Registrar name when known.
- `created_at`, Creation timestamp when known.
- `expires_at`, Expiry timestamp when known.
- `status_verified_at`, When status was last established against the registry. Null means never checked.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This list holds 12,047 one-word domain names on the .properties extension, all currently available to register. Names range from everyday nouns like homes.properties and matcha.properties to compound brandable picks such as midmorning.properties and fitthebill.properties. The median ask across the set is $27, giving a quick reference point for comparing individual listings. Whether you're weighing entry price against demand or scanning for a clean, ownable name, this snapshot is built to help you compare options within a single, focused TLD.

- 12,047 one-word .properties domains available now
- $27 median ask price across the set
- Includes short, brandable names like Homes and Matcha
- Spans everyday terms: food, lifestyle, and property words

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The snapshot date above is when this file was written, not when each row was checked. Read `status_verified_at` for that: a name whose status was last established months ago is exported with its real date rather than the snapshot's.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .PROPERTIES One-Word Domains*. Version 2026-10-03. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .PROPERTIES page](https://unique.domains/domains/tld/properties?utm_source=github&utm_medium=referral&utm_campaign=repo_properties_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_properties_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_properties_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_properties_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `kai@unique.domains`
