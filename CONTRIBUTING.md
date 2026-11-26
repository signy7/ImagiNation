# Contributing

[English](CONTRIBUTING.md) · [简体中文](docs/zh-CN/CONTRIBUTING.md) · [Project home](README.md)

**Preserve the glory. Defend the architecture. Prevent implementation.**

ImagiNation accepts improvements to its writing, translations, diagrams, static visual assets, and community documentation. Actual business code is prohibited.

## Admission requirement

Every contributor must pass the GitHub home-page access test:

1. Open [github.com](https://github.com) in a browser.
2. Confirm that the home page loads.
3. Self-attest using the checkbox in the Issue or PR template.

Self-attestation completes the admission record. No screenshot, API key, payment, identity document, or benchmark score is required. Submitting an Issue or PR requires a GitHub account. If the page does not load, admission remains pending.

## Accepted contributions

- Precise, concise technical writing.
- Complete, accurate English and Chinese translations.
- Mermaid diagrams that actually render and retain the two-plane architecture.
- Static, accessible visual assets with useful alternative text.
- Link fixes and factual corrections.
- Criticism of GPT, other models, this project, or its premise.

## Prohibited contributions

- Business logic, a working demo, an API service, an SDK, or any actual product implementation.
- A `src/` directory, runtime dependencies, package manifests, executable scripts, or workflows that execute code in this repository.
- SVG scripts, event handlers, embedded tracking, or external asset dependencies inside SVG files.
- Real API keys, personal data, copied private conversations, or screenshots identifying people for ridicule.
- Material that violates the [publication boundaries](DISCLOSURE.md#publication-boundaries).

Markdown examples and Mermaid diagrams are documentation, not permission to ship an implementation. Editorial tools may be used outside the repository; their output must comply with these rules.

## Editorial standard

Use the register of an infrastructure specification. State responsibilities, procedures, and outcomes directly. Apply the same tone to every component; omit explanatory asides.

Keep BaaS, LSE, ZKA, and IFD consistent with [Architecture](ARCHITECTURE.md). Preserve the central line: **Brains in the cloud. Superiority on localhost.**

Maintain the brief disclosure line below the README hero and the short labels on evaluation tables. Project context belongs in [Project disclosure](DISCLOSURE.md).

## Translation contract

| English source | Chinese mirror |
| :-- | :-- |
| `README.md` | `README.zh-CN.md` |
| `ARCHITECTURE.md` | `docs/zh-CN/ARCHITECTURE.md` |
| `BENCHMARK.md` | `docs/zh-CN/BENCHMARK.md` |
| `CONTRIBUTING.md` | `docs/zh-CN/CONTRIBUTING.md` |
| `SECURITY.md` | `docs/zh-CN/SECURITY.md` |
| `MANIFESTO.md` | `docs/zh-CN/MANIFESTO.md` |
| `CHANGELOG.md` | `docs/zh-CN/CHANGELOG.md` |
| `DISCLOSURE.md` | `docs/zh-CN/DISCLOSURE.md` |
| `LICENSE` | `docs/zh-CN/LICENSE.md` (reference translation) |

Update both languages in the same PR. Keep the same sections, contracts, restrictions, weights, and examples. Idiomatic phrasing may differ. The English MIT license is the licensing text; the Chinese translation is supplied for reading convenience. Issue and PR templates contain both languages in one file. Hero and share-card assets have matching language variants.

## Review process

1. Read the relevant document and its mirror.
2. Make the smallest editorial change that resolves the issue.
3. Check links and Markdown; render any changed Mermaid or SVG asset.
4. Check the README disclosure line, evaluation labels, and disclosure references on share cards.
5. Open a PR using the bilingual checklist. List the files checked and how they were checked; do not claim tests that were not run.

A reviewer checks editorial quality, bilingual consistency, accessibility, and the absence of implementation. There is no product build or test suite. A typo is repairable; a working backend is an architectural incident.

## Community and licensing

Contributions must comply with the [publication boundaries](DISCLOSURE.md#publication-boundaries). Maintainers may edit or close submissions that do not comply.

Maintainers make merge decisions. Criticism of GPT, the architecture, and project decisions is accepted through the same review process. The Chief Vision Officer has no exemption from review.

Submit only material you may share. By contributing, you agree that your contribution is distributed under this project's [MIT License](LICENSE). Keep attribution where required.
