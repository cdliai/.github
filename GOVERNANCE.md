# CDLI Governance

CDLI is a commercial product and systems lab with selected public open-source work. This document explains how public repositories, private products, and review gates are expected to operate.

## Repository Classes

| Class | Purpose | Default visibility | Examples |
| --- | --- | --- | --- |
| Public lab | Installable or inspectable open work | Public | `durak`, `ottoman-ner`, `cdli-agent-skills`, `opencr`, `holy-graph` |
| Product platform | Commercial systems and customer-facing product logic | Private | `ulak-backend`, `ulak-apple-app`, `ulak-landing` |
| Internal platform | Private infrastructure, experiments, and operational tools | Private | `betterquery`, `orqel-intelligence`, `d3ns`, `Daedalus` |
| Archive | Historical or superseded work | Private or public, archived | `CDLI`, `Prometheus` |

## Decision Rules

- Public work should be useful on its own: installable, inspectable, documented, and connected to a clear problem.
- Commercial product logic, credentials, customer data, private infrastructure, and unreleased product strategy stay private.
- Default branches should be protected. Changes should land through pull requests with owner or CODEOWNER review.
- Security reports, leaked secrets, and private product issues should be sent privately to `info@cdli.ai`, not posted in public issues.
- Public issues should be scoped to reproducible bugs, documentation gaps, focused feature proposals, or open research questions.

## Review And Merge

- Use topic branches and pull requests.
- Keep pull requests narrow enough to review.
- Include verification notes for behavior changes.
- Require CODEOWNER review where a repository defines ownership.
- Do not merge changes that expose secrets, customer data, private product plans, or security details.

## Public Support

CDLI can accept commercial work, sponsorship conversations, and public-lab support inquiries through the work-with-us page:

- English: https://cdli.ai/work-with-us
- Türkçe: https://cdli.ai/tr/birlikte-calisalim

If GitHub Sponsors, Open Collective, or a fiscal-hosted support route becomes active, the organization funding file should be updated to point directly to the approved support profile.
