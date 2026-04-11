# Available .DEAL One-Word Domains (7,549)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-7%2C549%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-7%2C549%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated dataset of available and resale .deal one-word domains from Unique Domains.

> **Note:** this repository currently mirrors the full live catalog for this exact search.
> Unique Domains counts can still change as the search refreshes.

**Public extract:** 7,549 rows · **Live catalog:** 7,549 domains

**Last updated:** 2026-04-11  
**Canonical page:** `https://unique.domains/domains/tld/deal`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/deal?utm_source=github&utm_medium=referral&utm_campaign=repo_deal_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./deal.csv">CSV</a> / <a href="./deal.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_deal_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_deal_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .DEAL search](https://unique.domains/domains/tld/deal?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_deal_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .DEAL search](https://unique.domains/domains/tld/deal?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_deal_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_deal_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .DEAL one-word domain catalog.

### Files

- `deal.csv` — public CSV extract (7,549 rows)
- `deal.json` — public JSON extract (7,549 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/deal-oneword-domains/main/deal.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain          | status    | ask_price | renewal_price | attractiveness | demand | length | registrar       |
| --------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------- |
| seventeen.deal  | available | $24.99    | $59.99        | 84             | 62     | 9      | name.com        |
| square.deal     | resell    | —         | —             | 72             | 65     | 6      | Porkbun LLC     |
| nationwide.deal | premium   | $125      | $125          | 76             | 66     | 10     | name.com        |
| genius.deal     | available | $24.99    | $59.99        | 98             | 47     | 6      | name.com        |
| bravo.deal      | resell    | —         | —             | 66             | 65     | 5      | Porkbun LLC     |
| free.deal       | premium   | $3,125    | $3,125        | 88             | 59     | 4      | name.com        |
| wizard.deal     | available | $24.99    | $59.99        | 118            | 46     | 6      | name.com        |
| snap.deal       | resell    | —         | —             | 90             | 46     | 4      | Porkbun LLC     |
| cloud.deal      | premium   | $650      | $650          | 70             | 59     | 5      | namecheap       |
| goto.deal       | available | $48.98    | —             | 66             | 45     | 5      | namecheap       |
| shift.deal      | resell    | —         | —             | 70             | 46     | 5      | Dynadot Inc     |
| ace.deal        | premium   | $125      | $125          | 88             | 57     | 3      | name.com        |
| agile.deal      | available | $24.99    | $59.99        | 92             | 42     | 5      | name.com        |
| perfect.deal    | resell    | —         | —             | 124            | 42     | 7      | EuroDNS S.A.    |
| data.deal       | premium   | $650      | $650          | 70             | 56     | 4      | namecheap       |
| unity.deal      | available | $24.99    | $59.99        | 70             | 41     | 5      | name.com        |
| sport.deal      | resell    | —         | —             | 70             | 37     | 5      | Dynadot Inc     |
| live.deal       | premium   | $625      | $625          | 108            | 55     | 4      | name.com        |
| learning.deal   | available | $48.98    | —             | 80             | 39     | 8      | namecheap       |
| weed.deal       | resell    | —         | —             | 64             | 37     | 4      | NameCheap, Inc. |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 7,549-row public sample | 7,549 live domains                               |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/deal?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_deal_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/deal?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_deal_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_deal_oneword_domains&utm_content=related_pricing)

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

This repository follows the exact public search represented by the canonical page above.

- This repository is a public extract, not the full live catalog.
- Counts, prices, and statuses can change over time.
- Scores are decision-support signals, not guarantees of resale value.
- Trademark, SEO, and risk signals should be treated as screening inputs, not legal or specialist advice.
- Unique Domains contains deeper filters, monitoring, and decision workflows than this public extract.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .DEAL One-Word Domains*. Version 2026-04-11. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .DEAL page](https://unique.domains/domains/tld/deal?utm_source=github&utm_medium=referral&utm_campaign=repo_deal_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_deal_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_deal_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_deal_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
