# ImagiBench v1.0

[English](BENCHMARK.md) · [简体中文](docs/zh-CN/BENCHMARK.md) · [Project home](README.md)

## Objective

ImagiBench evaluates cross-domain authority using GitHub access and API configuration. Fine-arts qualifications are assigned from these inputs.

## Scoring rule

*Fictional benchmark.*

| Symbol | Criterion | Assigned weight |
| :-- | :-- | --: |
| G | Can open the GitHub home page | 40% |
| U | Can fill in a Base URL | 30% |
| K | Can fill in an API key | 30% |
| A | Anatomy, color, composition, and original design | 0% |
| Y | Years of artistic practice | 0% |

```text
Universal Expertise Score = 40G + 30U + 30K
G, U, K are binary inputs: 0 or 1.
A and Y have no effect, by construction.
```

The maximum score is 100 points. Contributor admission uses the GitHub access test separately and requires no benchmark score.

**Methodological rationale:** to prevent professional knowledge from influencing the assessment of professional ability, all domain-specific criteria have been excluded.

## Reference cases

The first two cases hold artistic practice constant to isolate the contribution of access credentials.

*Fictional benchmark examples.*

| Reference case | G | U | K | A and Y | Score |
| :-- | --: | --: | --: | :-- | --: |
| Same practice, no tool access | 0 | 0 | 0 | Held constant | 0 |
| Same practice, all access boxes checked | 1 | 1 | 1 | Held constant | 100 |
| GitHub home page only | 1 | 0 | 0 | Ignored | 40 |
| API configuration only | 0 | 1 | 1 | Ignored | 60 |

Changes in A and Y do not affect qualification. This behavior is required.

## Reproduction on paper

1. Assign values of 0 or 1 to G, U, and K on paper.
2. Multiply them by 40, 30, and 30; add the products.
3. Change the artistic-practice inputs without changing G, U, or K.
4. Observe that the score cannot change.

The procedure requires arithmetic only. API calls, credential submission, and artwork uploads are outside the input contract.

## Publication rules

- Retain the short labels on reproduced tables and scores; see [Project disclosure](DISCLOSURE.md).
- Update the English and Chinese rules and examples together.
- A change to the scoring rule requires a new benchmark version; the repository release number is separate.
