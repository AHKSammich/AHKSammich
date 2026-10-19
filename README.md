# Samuel Bostock

I build and ship software with coding agents — designing the specs, quality gates and review loops that let agents produce code that holds up in a real enterprise codebase. Australian, based in Thailand, working remotely (UTC+7).

## Open Mercato

I'm a top-10 contributor to [Open Mercato](https://github.com/open-mercato/open-mercato), the open-source AI-engineering framework for CRM/ERP and commerce:

- **45 merged pull requests** (10th of 143 contributors by merged PRs), with more approved and in the merge queue
- Mostly **security and correctness fixes**: authentication and session handling, organization/tenant scoping, webhook hardening, payment-gateway webhooks, AI-agent safeguards, forms and portal access, concurrency and undo/redo integrity
- Fixes ship with regression tests (unit and integration, plus Playwright where the change is user-visible), upgrade notes for behaviour changes, and follow-up issues for known limitations

## How I work: an agent-driven delivery pipeline

My Open Mercato work runs through a pipeline I designed on top of [Cezar](https://github.com/open-mercato/cezar) and Claude Code:

- **Spec templates** for each kind of work — fixes, review responses, self-QA, scouting, verification — encoding the repo's rules (AGENTS.md, backward compatibility, i18n, test conventions)
- **An independent quality gate** that re-checks every "ready" claim before anything is published: exact commit pushed, clean tree, eslint, i18n, repo-wide guards compared against the develop baseline, targeted tests, privacy checks on PR text
- **Self-QA** in a real browser under the project's documented self-QA process, with written evidence
- **Scouting and verification**: agents find candidate defects, a separate step reproduces them with a failing test and drafts the issue, and only verified bugs are filed — together with their fix
- **Review loops**: findings are fixed automatically, conflicts kept resolved, reviewers kept informed

## Before Open Mercato

From 2015 to 2026 I founded and ran a commercial Windows automation software business:

- Built, released and maintained 12 commercial products
- Supported roughly 20,000 customers and a community of 14,500+ members — requirements, troubleshooting, releases and documentation, end to end
- Ran the storefront and payments (WordPress/WooCommerce, Stripe, PayPal), licensing and day-to-day operations

## Skills

TypeScript · React · Next.js · PostgreSQL · Playwright · Jest · Git/GitHub · AI coding agents (Claude Code, Cezar) · agent workflow and quality-gate design · security-focused code review · customer-facing support and requirements

## Links

[Portfolio](https://samuelbostock.com) · [Resume](https://samuelbostock.com/wp-content/uploads/2026/10/Samuel-Bostock-Resume.pdf) · [LinkedIn](https://www.linkedin.com/in/samuel-bostock-74533b43a/) · [Email](mailto:sambostock@hotmail.com)
