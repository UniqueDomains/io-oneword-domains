# Available .IO One-Word Domains (57,685)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-57%2C685%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .io one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **57,685 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 57,685 domains · **Median ask:** $1,390.14 · **High-demand under $2,500:** 88

**Last updated:** 2026-08-19
**Canonical page:** `https://unique.domains/domains/tld/io`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/io?utm_source=github&utm_medium=referral&utm_campaign=repo_io_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./io.csv">CSV</a> / <a href="./io.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_io_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_io_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .IO search](https://unique.domains/domains/tld/io?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_io_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .IO search](https://unique.domains/domains/tld/io?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_io_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_io_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .IO one-word domain catalog.

### Files

- `io.csv`, public CSV extract (1,000 rows)
- `io.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/io-oneword-domains/main/io.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain     | status    | ask_price | renewal_price | attractiveness | demand | length | registrar            |
| ---------- | --------- | --------- | ------------- | -------------- | ------ | ------ | -------------------- |
| argive.io  | available | $33.99    | $69.99        | low            | low    | 6      | namesilo             |
| branded.io | resell    | $8,625    | $59.99        | high           | low    | 7      | Name.com, Inc.       |
| daggum.io  | available | $34.99    | $69.99        | high           | low    | 6      | namesilo             |
| bod.io     | resell    | —         | —             | medium         | high   | 3      | GoDaddy.com, LLC     |
| toured.io  | available | $34.99    | $69.99        | low            | low    | 6      | namesilo             |
| elk.io     | resell    | —         | —             | medium         | high   | 3      | Dynadot Inc          |
| xlviii.io  | available | $34.98    | $75.98        | low            | low    | 6      | namecheap            |
| lug.io     | resell    | —         | —             | medium         | high   | 3      | GoDaddy.com, LLC     |
| yawned.io  | available | $34.99    | $69.99        | low            | low    | 6      | namesilo             |
| moi.io     | resell    | —         | —             | high           | low    | 3      | NameCheap, Inc.      |
| allylic.io | available | $34.98    | $75.98        | low            | low    | 7      | namecheap            |
| stp.io     | resell    | —         | —             | medium         | high   | 3      | GoDaddy.com, LLC     |
| awnless.io | available | $33.99    | $69.99        | low            | low    | 7      | namesilo             |
| too.io     | resell    | —         | —             | high           | low    | 3      | Sav.com, LLC         |
| baccate.io | available | $33.99    | $69.99        | low            | low    | 7      | namesilo             |
| use.io     | resell    | —         | —             | high           | low    | 3      | Dynadot Inc          |
| basilar.io | available | $33.99    | $69.99        | low            | low    | 7      | namesilo             |
| DSLR.io    | resell    | —         | —             | high           | low    | 4      | NameCheap, Inc.      |
| faroff.io  | available | $33.99    | $69.99        | medium         | low    | 7      | namesilo             |
| duke.io    | resell    | —         | —             | high           | low    | 4      | Atom.com Domains LLC |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 57,685 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 88 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/io?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_io_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/io?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_io_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_io_oneword_domains&utm_content=related_pricing)

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

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This set includes 55,186 one-word .io domain names, referenced across 506 TLD variants for comparison, with a median ask of $2,843. The mix ranges from short brandable words such as mojo.io, half.io, and know.io to compound phrases like dogwalking.io and letitbe.io. When comparing these domains, weigh asking price against renewal cost, spelling simplicity, and trademark exposure before choosing one.

- 55,186 one-word .io domain names in this set
- Median ask across the set: $2,843
- Spans 506 TLD variants for price comparison
- Mix of short brandable words and compound names

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .IO One-Word Domains*. Version 2026-08-19. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .IO page](https://unique.domains/domains/tld/io?utm_source=github&utm_medium=referral&utm_campaign=repo_io_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_io_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_io_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_io_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
