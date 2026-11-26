# Available .SH One-Word Domains

**Looking for a name, not a file?** [Find the strongest domain still available for your business](https://unique.domains/?utm_source=github&utm_medium=referral&utm_campaign=repo_sh_oneword_domains&utm_content=top_home).

1,000 real .sh one-word domain names, refreshed every night, with their status and, when known, the price to register or buy them and what they renew at. One line of pandas, no scraping, no key.

Each word exists once on each ending. Unique.domains tracks [73,023 names on .sh](https://unique.domains/tld/sh); this file is an extract of the ones you can still register or buy, in the list's own neutral order, not a ranking.

63,724 one-word .sh names are free to register today. Cheapest first year $31.05 at Spaceship, renewal $46.58 there. 63 .sh sales in the last 12 months, median $300.

Live page: [unique.domains/tld/sh](https://unique.domains/tld/sh?utm_source=github&utm_medium=referral&utm_campaign=repo_sh_oneword_domains&utm_content=top_tld_page)

<img alt="updated: daily" src="https://img.shields.io/badge/updated-daily-0969da"> <img alt="extract: 1,000 rows" src="https://img.shields.io/badge/extract-1%2C000%20rows-8250df"> <img alt="formats: CSV | JSON" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b"> <img alt="licence: CC BY 4.0" src="https://img.shields.io/badge/licence-CC%20BY%204.0-2ea44f">

## Download

- [sh.csv](https://github.com/UniqueDomains/sh-oneword-domains/raw/main/sh.csv), 1,000 rows
- [sh.json](https://github.com/UniqueDomains/sh-oneword-domains/raw/main/sh.json), 1,000 rows

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/sh-oneword-domains/main/sh.csv")
print(df.head())
```

Also on Kaggle, with every ending: [One-Word Domains by Ending](https://www.kaggle.com/datasets/uniquedomains/one-word-domains-by-ending).

## Sample rows

The first 20 rows of the file, in the file's order.

| domain          | status    | purchase_price | renewal_price | attractiveness | demand | length |
| --------------- | --------- | -------------- | ------------- | -------------- | ------ | ------ |
| somersaults.sh  | available | $32.10         | $48.15        | medium         | low    | 11     |
| fasting.sh      | available | $32.10         | $48.15        | high           | low    | 7      |
| morphing.sh     | available | $39.99         | $47.99        | high           | low    | 8      |
| topography.sh   | available | $31.05         | $46.58        | high           | low    | 10     |
| bechill.sh      | available | $31.05         | $46.58        | high           | low    | 7      |
| fido.sh         | available | $31.05         | $46.58        | high           | low    | 4      |
| yourself.sh     | available | $39.99         | $47.99        | high           | low    | 8      |
| typesetter.sh   | available | $34.98         | $76.98        | high           | low    | 10     |
| glockenspiel.sh | available | $31.05         | $46.58        | high           | low    | 12     |
| silverback.sh   | available | $31.05         | $46.58        | high           | medium | 10     |
| utp.sh          | available | $31.05         | $46.58        | high           | low    | 3      |
| savegame.sh     | available | $34.98         | $76.98        | high           | low    | 8      |
| bodied.sh       | available | $31.05         | $46.58        | high           | low    | 6      |
| summerset.sh    | available | $39.99         | $47.99        | high           | low    | 9      |
| coma.sh         | available | $39.99         | $47.99        | high           | low    | 4      |
| aftershow.sh    | available | $39.99         | $47.99        | high           | low    | 9      |
| luta.sh         | available | $39.99         | $47.99        | high           | low    | 4      |
| kabab.sh        | available | $39.99         | $47.99        | high           | low    | 5      |
| feats.sh        | available | $39.99         | $47.99        | high           | low    | 5      |
| undermined.sh   | available | $34.98         | $76.98        | medium         | low    | 10     |

## What is in the data

- `domain`: Fully qualified domain name.
- `status`: Current acquisition state for the domain in the public extract.
- `purchase_price`: Visible purchase price when available.
- `renewal_price`: Visible renewal price when available.
- `attractiveness`: Public composite naming band used as a decision-support signal.
- `demand`: Public buyer-pressure band when available.
- `length`: Character count without the TLD.
- `registrar`: Registrar name when known.
- `created_at`: Creation timestamp when known.
- `expires_at`: Expiry timestamp when known.

Types and formats: [DATA_DICTIONARY.md](./DATA_DICTIONARY.md).

## Methodology

- The files hold 1,000 rows of the 30,473 names in the live list today.
- Every row is a one-word domain name.
- Check a name before you act on it: a status or a price can change.

More in [METHODOLOGY.md](./METHODOLOGY.md).

## Update policy

- The files are rebuilt every night from the same export.
- The files hold the public extract, not the whole live list.

## How to cite

> Unique.domains, One-word .sh domains, https://unique.domains/tld/sh, CC BY 4.0

Citation metadata: [CITATION.cff](./CITATION.cff). A DOI follows once Zenodo mints one.

## Related datasets

- [Every one-word domain](https://github.com/UniqueDomains/oneword-domains) (the hub)

One-word domains by ending:

- [.com](https://github.com/UniqueDomains/com-oneword-domains), [page](https://unique.domains/tld/com?utm_source=github&utm_medium=referral&utm_campaign=repo_sh_oneword_domains&utm_content=related_tld_page)
- [.ai](https://github.com/UniqueDomains/ai-oneword-domains), [page](https://unique.domains/tld/ai?utm_source=github&utm_medium=referral&utm_campaign=repo_sh_oneword_domains&utm_content=related_tld_page)
- [.io](https://github.com/UniqueDomains/io-oneword-domains), [page](https://unique.domains/tld/io?utm_source=github&utm_medium=referral&utm_campaign=repo_sh_oneword_domains&utm_content=related_tld_page)
- [.app](https://github.com/UniqueDomains/app-oneword-domains), [page](https://unique.domains/tld/app?utm_source=github&utm_medium=referral&utm_campaign=repo_sh_oneword_domains&utm_content=related_tld_page)
- [.co](https://github.com/UniqueDomains/co-oneword-domains), [page](https://unique.domains/tld/co?utm_source=github&utm_medium=referral&utm_campaign=repo_sh_oneword_domains&utm_content=related_tld_page)
- [.xyz](https://github.com/UniqueDomains/xyz-oneword-domains), [page](https://unique.domains/tld/xyz?utm_source=github&utm_medium=referral&utm_campaign=repo_sh_oneword_domains&utm_content=related_tld_page)
- [.ca](https://github.com/UniqueDomains/ca-oneword-domains), [page](https://unique.domains/tld/ca?utm_source=github&utm_medium=referral&utm_campaign=repo_sh_oneword_domains&utm_content=related_tld_page)
- [.cc](https://github.com/UniqueDomains/cc-oneword-domains), [page](https://unique.domains/tld/cc?utm_source=github&utm_medium=referral&utm_campaign=repo_sh_oneword_domains&utm_content=related_tld_page)
- [.dev](https://github.com/UniqueDomains/dev-oneword-domains), [page](https://unique.domains/tld/dev?utm_source=github&utm_medium=referral&utm_campaign=repo_sh_oneword_domains&utm_content=related_tld_page)
- [.eu](https://github.com/UniqueDomains/eu-oneword-domains), [page](https://unique.domains/tld/eu?utm_source=github&utm_medium=referral&utm_campaign=repo_sh_oneword_domains&utm_content=related_tld_page)
- [.gg](https://github.com/UniqueDomains/gg-oneword-domains), [page](https://unique.domains/tld/gg?utm_source=github&utm_medium=referral&utm_campaign=repo_sh_oneword_domains&utm_content=related_tld_page)
- [.info](https://github.com/UniqueDomains/info-oneword-domains), [page](https://unique.domains/tld/info?utm_source=github&utm_medium=referral&utm_campaign=repo_sh_oneword_domains&utm_content=related_tld_page)
- [.me](https://github.com/UniqueDomains/me-oneword-domains), [page](https://unique.domains/tld/me?utm_source=github&utm_medium=referral&utm_campaign=repo_sh_oneword_domains&utm_content=related_tld_page)
- [.net](https://github.com/UniqueDomains/net-oneword-domains), [page](https://unique.domains/tld/net?utm_source=github&utm_medium=referral&utm_campaign=repo_sh_oneword_domains&utm_content=related_tld_page)
- [.nl](https://github.com/UniqueDomains/nl-oneword-domains), [page](https://unique.domains/tld/nl?utm_source=github&utm_medium=referral&utm_campaign=repo_sh_oneword_domains&utm_content=related_tld_page)
- [.now](https://github.com/UniqueDomains/now-oneword-domains), [page](https://unique.domains/tld/now?utm_source=github&utm_medium=referral&utm_campaign=repo_sh_oneword_domains&utm_content=related_tld_page)
- [.org](https://github.com/UniqueDomains/org-oneword-domains), [page](https://unique.domains/tld/org?utm_source=github&utm_medium=referral&utm_campaign=repo_sh_oneword_domains&utm_content=related_tld_page)
- [.to](https://github.com/UniqueDomains/to-oneword-domains), [page](https://unique.domains/tld/to?utm_source=github&utm_medium=referral&utm_campaign=repo_sh_oneword_domains&utm_content=related_tld_page)
- [.tv](https://github.com/UniqueDomains/tv-oneword-domains), [page](https://unique.domains/tld/tv?utm_source=github&utm_medium=referral&utm_campaign=repo_sh_oneword_domains&utm_content=related_tld_page)
- [.uk](https://github.com/UniqueDomains/uk-oneword-domains), [page](https://unique.domains/tld/uk?utm_source=github&utm_medium=referral&utm_campaign=repo_sh_oneword_domains&utm_content=related_tld_page)
- [.us](https://github.com/UniqueDomains/us-oneword-domains), [page](https://unique.domains/tld/us?utm_source=github&utm_medium=referral&utm_campaign=repo_sh_oneword_domains&utm_content=related_tld_page)
- [.vc](https://github.com/UniqueDomains/vc-oneword-domains), [page](https://unique.domains/tld/vc?utm_source=github&utm_medium=referral&utm_campaign=repo_sh_oneword_domains&utm_content=related_tld_page)

Lists:

- [Expired](https://github.com/UniqueDomains/expired-oneword-domains)
- [Expiring](https://github.com/UniqueDomains/expiring-oneword-domains)
- [Brandable](https://github.com/UniqueDomains/brandable-oneword-domains)
- [Short](https://github.com/UniqueDomains/short-oneword-domains)

Every ending Unique.domains tracks: [unique.domains/tld](https://unique.domains/tld?utm_source=github&utm_medium=referral&utm_campaign=repo_sh_oneword_domains&utm_content=related_hub).

## About Unique.domains

[Unique.domains](https://unique.domains/?utm_source=github&utm_medium=referral&utm_campaign=repo_sh_oneword_domains&utm_content=about) tracks one-word domain names across the endings people build on: which are free to register, what they cost to hold and what names of each ending sell for. The datasets in this organization are its public extracts.

From code: the [Node.js SDK and CLI](https://github.com/UniqueDomains/nodejs) (`npm install domain-name-api`), the [Python client](https://github.com/UniqueDomains/python) (`pip install uniquedomains`) and the [MCP server](https://github.com/UniqueDomains/mcp-server) for AI assistants, hosted at `https://mcp.unique.domains/mcp`.

Questions and corrections: `kai@unique.domains`

[Start a Radar for .sh names](https://unique.domains/tld/sh?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_sh_oneword_domains&utm_content=about)
