# Disposable Email Domains

**The internet's most complete disposable & temporary email blocklist. 207,000+ domains, refreshed around the clock.**

![License](https://img.shields.io/badge/license-MIT-22c55e)
![Updated](https://img.shields.io/badge/updated-every%2030%20min-3b82f6)
![Domains](https://img.shields.io/badge/domains-207k%2B-f59e0b)

Throwaway inboxes are how fake accounts get made at scale: sign up, grab the confirmation link, abuse the free tier, repeat. This is the open disposable-email database behind [ffraud.com](https://ffraud.com), every temporary, disposable, and throwaway mail domain we can find, in one plain list.

New throwaway services spin up every day, and so do we. Our honeypot sensor network and a global community of fraud fighters surface fresh domains around the clock, and the list is rebuilt **every 30 minutes**, so what you pull is what's live right now, not a stale snapshot from last week.

No signup. No API key. No rate limits. Just the biggest, freshest disposable-email list on the internet, free forever.

## Quick start

```bash
curl -s https://raw.githubusercontent.com/FFraud-com/disposable-email-domains/main/disposable-email-domains.txt
```

Drop it into your signup validation, CRM, or fraud pipeline and reject disposable addresses before they cost you a cent.

## Check a single address

Don't want to download the whole list? Check any email or domain instantly with the free checker at [ffraud.com](https://ffraud.com), no key, no limits.

## What's inside

| File | Rows | What it is |
|------|------|-----------|
| [`disposable-email-domains.txt`](disposable-email-domains.txt) | 207,000+ | One disposable or temporary email domain per line, sorted |
| [`metadata.json`](metadata.json) | | Live count and the UTC build time |

## Related open data

- **[IP Fraud Database](https://github.com/FFraud-com/ip-fraud-database)**: our open database of 750,000+ confirmed-malicious IPs and fraudulent networks, each scored and tagged with a threat category and infrastructure type.
- **[ffraud.com](https://ffraud.com)**: free IP and email fraud intelligence, a fast API, live checkers, and open data, all with no limits.

## Help build it

Found a disposable domain we're missing? Open an issue or report it at [ffraud.com/report](https://ffraud.com/report). Confirmed domains ship in the next build, within the half hour.

## License

MIT. Use it anywhere, including commercial products. Fork it, redistribute it, build on it. Attribution appreciated, never required.

---

Built by [ffraud.com](https://ffraud.com), free fraud intelligence for everyone.
