# dw-public-reviews

**Live DigitalWorker Reviewer runs on open-source pull requests — mirrored here so you can see real findings on real code before installing anything.**

Each PR in this repository mirrors a pull request from a public open-source repository (linked in the PR body, with the original author credited). [DigitalWorker Reviewer](https://github.com/apps/digitalworker-reviewer/installations/new) reviews it exactly as it would on your own repository — severity-tagged, inline comments on the diff.

## What the Reviewer checks

Unlike other AI review tools it is **focused more on architecture, design, maintanability and test coverage than on correctness alone**. On every PR it flags:

- architecture violations (layer dependencies, Anemic Domain Model)
- code smells and duplication
- testability issues and coverage gaps

**It comments. It never touches code** — read-only, no write access to your files.

## Why a mirror repo?

The Reviewer works on any repository where its GitHub App is installed. Mirroring a PR here reproduces the upstream diff byte-for-byte (same base and head commits), so the review you see is exactly what you'd get on your own PR — **without installing anything to look**.

## Want a review of your PR?

- **Try it on your repo (recommended):** [install the app](https://github.com/apps/digitalworker-reviewer/installations/new) — ~1 minute, free trial — then comment `@digitalworker review` on any existing PR.
- **Or ask for a mirror review:** open an issue here with a link to a public PR you'd like reviewed.
- Questions or removal requests: info@agiledigitalworker.com

## Notes

- Findings are automated design-review candidates for **your** judgment — the reviewer flags, the maintainer decides.
- Mirrored code remains the upstream project's own work under its own license; mirrors exist for review demonstration, by request or with maintainer awareness. Any upstream maintainer may request removal.
- More about the product: [agiledigitalworker.com](https://agiledigitalworker.com) · public demo repo: [grandua/Digital-Worker-Demo](https://github.com/grandua/Digital-Worker-Demo)
