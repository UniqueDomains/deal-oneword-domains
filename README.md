# Available .DEAL One-Word Domains (10,544)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-10%2C544%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .deal one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **10,544 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 10,544 domains · **Median ask:** $80.69 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-08  
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

- `deal.csv` — public CSV extract (1,000 rows)
- `deal.json` — public JSON extract (1,000 rows)
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

| domain             | status    | ask_price | renewal_price | attractiveness | demand | length | registrar   |
| ------------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------- |
| jewels.deal        | available | $48.98    | —             | 80             | 15     | 6      | namecheap   |
| geton.deal         | available | $48.98    | —             | 82             | 10     | 6      | namecheap   |
| popup.deal         | available | $48.98    | —             | 84             | 29     | 6      | namecheap   |
| playon.deal        | available | $48.98    | —             | 80             | 14     | 7      | namecheap   |
| hangon.deal        | available | $48.98    | —             | 82             | 6      | 7      | namecheap   |
| omega.deal         | available | $38.99    | $38.99        | 78             | 70     | 5      | namesilo    |
| rare.deal          | resell    | —         | —             | 78             | 40     | 4      | Porkbun LLC |
| Books.deal         | premium   | $700      | $700          | 52             | 49     | 5      | namecheap   |
| travelers.deal     | available | $38.99    | $38.99        | 58             | 61     | 9      | namesilo    |
| Ryan.deal          | premium   | $140      | $140          | 60             | 44     | 4      | namecheap   |
| regions.deal       | available | $48.98    | —             | 64             | 59     | 7      | namecheap   |
| WiFi.deal          | premium   | $140      | $140          | 83             | 37     | 5      | namecheap   |
| keepthechange.deal | available | $48.98    | —             | 46             | 59     | 15     | namecheap   |
| tickets.deal       | premium   | $625      | —             | 64             | 34     | 7      | name.com    |
| shortcuts.deal     | available | $48.98    | —             | 48             | 41     | 10     | namecheap   |
| etc.deal           | premium   | $125      | —             | 58             | 34     | 3      | name.com    |
| prompts.deal       | available | $38.99    | $38.99        | 54             | 39     | 7      | namesilo    |
| William.deal       | premium   | $140      | $140          | 74             | 31     | 7      | namecheap   |
| videos.deal        | premium   | $125      | —             | 52             | 30     | 6      | name.com    |
| blocks.deal        | available | $48.98    | —             | 53             | 29     | 6      | namecheap   |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 10,544 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

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

This selection is entirely made up of one-word .deal domains. The extension gives the names a built-in commercial angle, so the strongest picks are words that read naturally with .deal and make the intent immediately clear. Examples such as jewels.deal, popup.deal, and matcha.deal show the range: product terms, retail language, and broader brandable words. With a median ask of $80.71, the entry price is relatively low, but quality still varies. When comparing these domains, focus on whether the word is easy to recognize, whether it pairs cleanly with .deal, and whether the meaning feels specific enough to support resale or direct use.

- One-word .deal domains with clear commercial framing
- Median ask is $80.71 across 10,542 domains
- Best picks read naturally with the .deal extension
- Check generic strength before buying brand-like words

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .DEAL One-Word Domains*. Version 2026-05-08. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .DEAL page](https://unique.domains/domains/tld/deal?utm_source=github&utm_medium=referral&utm_campaign=repo_deal_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_deal_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_deal_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_deal_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
