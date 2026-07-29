# JHJ-Corp/.github

Org-wide GitHub configuration for **[JHJ Corp](https://github.com/JHJ-Corp)**.

This repository is the public home for shared org defaults: profile README, Dependabot policy for this config repo, and room to grow (issue/PR templates, reusable workflows, CODEOWNERS, security policy) as JHJ-Corp repos come online.

## What’s here

| Path | Purpose |
|------|---------|
| `README.md` | This file — what the org `.github` repo is for |
| `LICENSE` | MIT License (org-owned configuration and docs) |
| `.gitignore` | Ignore local tooling artifacts and secrets |
| `.github/dependabot.yml` | Weekly GitHub Actions dependency updates for this repo |
| `profile/README.md` | Organization profile README (rendered on the org home page) |

## Scope (now vs later)

**Now**
- Essential public-repo hygiene (README, LICENSE, gitignore, Dependabot)
- Org profile blurb so the GitHub org page isn’t blank

**Later (when app/code repos exist under JHJ-Corp)**
- Issue and PR templates  
- Reusable Actions workflows (CI, secret scan, nightly maintenance)  
- CODEOWNERS / SECURITY.md  
- Per-ecosystem Dependabot templates for consumers  

Sibling pattern for a fuller layout: [dizhaky/.github](https://github.com/dizhaky/.github).

## Using this repo

1. Keep the profile README accurate when the org’s purpose or contact points change.
2. Prefer adding shared automation and templates here first, then copy or `uses:` reference them from consumer repos.
3. Do not commit secrets, tokens, or production credentials.

## License

MIT — see [LICENSE](./LICENSE).
