# Small Automation and Code Repair Services

Live portfolio:
https://xyjk0511.github.io/codex-services-portfolio/

Quote request:
https://github.com/xyjk0511/codex-services-portfolio/issues/1

## Available Services

- CSV and Excel automation: typical small scope $50-$150
- Bug fix and test repair: $25-$250 depending on scope
- Small chatbot or RAG prototypes from provided content: $99 audit, $250+ prototype

The CSV kit page is a public preview only. The paid zip is not linked from this
repository.

## Proof Links

- CSV kit preview:
  https://xyjk0511.github.io/codex-services-portfolio/csv-kit/
- CSV reconciliation checklist:
  https://xyjk0511.github.io/codex-services-portfolio/guides/csv-reconciliation-checklist.html
- Sample JSON summary:
  https://xyjk0511.github.io/codex-services-portfolio/csv-kit/sample-output/summary.json
- Sample mismatch CSV:
  https://xyjk0511.github.io/codex-services-portfolio/csv-kit/sample-output/mismatches.csv

## Verification

Local proof collected before publishing:

```powershell
$env:PYTEST_DISABLE_PLUGIN_AUTOLOAD='1'; python -m pytest
```

Result: 11 tests passed for the local CSV reconciliation, Shopify CSV audit, and
bounty monitor checks.

Boundaries: no CAPTCHA bypass, account automation, spam, fake engagement,
unauthorized scraping, credential handling, payment-platform bypass, or
guaranteed accounting, tax, legal, financial, security, or business outcomes.

Quote requests should include sanitized examples only. Do not post credentials,
private customer data, payment details, production secrets, or files that you
are not allowed to share.
