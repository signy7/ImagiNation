# Contributing

[English](CONTRIBUTING.md) · [简体中文](docs/zh-CN/CONTRIBUTING.md) · [Project home](README.md)

**Preserve the glory. Defend the architecture. Prevent implementation.**

ImagiNation accepts improvements to its writing, translations, diagrams, static visual assets, and community documentation. Actual business code is prohibited.

## Admission requirement

Every contributor must pass the GitHub home-page access test.

1. Open [github.com](https://github.com) in a browser.
2. Confirm that the home page loads.
3. Self-attest using the checkbox in the Issue or PR template.

Self-attestation completes the admission record. No screenshot, API key, payment, identity document, or benchmark score is required. Submitting an Issue or PR requires a GitHub account. If the page does not load, admission remains pending.

## Accepted contributions

- Precise, concise technical writing.
- Complete, accurate English and Chinese translations.
- Mermaid diagrams that render both deployment planes.
- Static, accessible visual assets with useful alternative text.
- Link fixes and factual corrections.
- Criticism of GPT, other models, this project, or its premise.

## Prohibited contributions

- Business logic, a working demo, an API service, an SDK, or any actual product implementation.
- A `src/` directory, runtime dependencies, package manifests, executable scripts, or workflows that execute code in this repository.
- SVG scripts, event handlers, embedded tracking, or external asset dependencies inside SVG files.
- Real API keys, personal data, copied private conversations, or screenshots identifying people for ridicule.
- Fabricated test results, star counts, customer lists, or endorsements.

## Editorial standard

Use the component names in [Architecture](ARCHITECTURE.md). For an architecture change, identify the input, the component responsible for the decision, and what happens when the provider goes offline.

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
| `LICENSE` | `docs/zh-CN/LICENSE.md` (reference translation) |

Update both languages in the same PR. Keep the same sections, contracts, restrictions, weights, and examples. The English MIT license governs contributions. The Chinese translation is provided for reference. Issue and PR templates are bilingual. The README banners and share cards have matching language variants.

## Review process

1. Read the relevant document and its mirror.
2. Make the smallest editorial change that resolves the issue.
3. Check links and Markdown. Render any changed diagram or artwork.
4. In the PR checklist, list the files you checked and how you checked them.

A reviewer checks the text, both language versions, accessibility, and compliance with IFD. A typo goes into the editing queue. A working backend goes into the incident register.

## Community and licensing

Keep discussion focused on the proposal. Maintainers close submissions that single people out for ridicule, coordinate harassment, or expose private information.

Maintainers make merge decisions. Criticism of GPT, the architecture, and project decisions is accepted through the same review process. The Chief Vision Officer has no exemption from review.

Submit only material you may share. By contributing, you agree that your contribution is distributed under this project's [MIT License](LICENSE). Keep attribution where required.
