# Disposable Email Domains

**Free, open list of disposable, temporary, and throwaway email domains. ~207,000 domains, updated every day.**

![License](https://img.shields.io/badge/license-MIT-22c55e)
![Updated](https://img.shields.io/badge/updated-daily-3b82f6)
![Domains](https://img.shields.io/badge/domains-207k%2B-f59e0b)

Block fake signups and throwaway accounts. This is the open email-domain layer of [ffraud.com](https://ffraud.com): every domain that serves temporary or disposable mailboxes, in one plain list, refreshed every day. No signup, no API key, no rate limits.

## Quick start

```bash
curl -s https://raw.githubusercontent.com/FFraud-com/disposable-email-domains/main/disposable-email-domains.txt
```

Drop it into your signup validation, CRM, or fraud pipeline and reject disposable addresses before they cost you.

## Check a single address

Do not want to download the whole list? Check one email or domain instantly with the free checker at [ffraud.com](https://ffraud.com).

## What is inside

| File | Rows | What it is |
|------|------|-----------|
| [`disposable-email-domains.txt`](disposable-email-domains.txt) | ~207,000 | One disposable or temporary email domain per line, sorted |
| [`metadata.json`](metadata.json) | | Count and the UTC build time |

## Related open data

- **[IP Fraud Database](https://github.com/FFraud-com/ip-fraud-database)**: our open database of ~750,000 confirmed-abusive IPs and fraudulent networks, each with a fraud score, threat category, and infrastructure type.
- **[ffraud.com](https://ffraud.com)**: free IP and email fraud intelligence, a fast API, and live checkers.

## Help build it

Found a disposable domain we are missing? Open an issue or report it at [ffraud.com/report](https://ffraud.com/report), and we add confirmed domains to the next daily build.

## License

MIT. Use it anywhere, including commercial products. Fork it, redistribute it, build on it. Attribution appreciated, not required.

---

Built by [ffraud.com](https://ffraud.com), free fraud intelligence for everyone.
