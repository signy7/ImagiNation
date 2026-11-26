# ImagiBench v1.0

[English](BENCHMARK.md) · [简体中文](docs/zh-CN/BENCHMARK.md) · [Project home](README.md)

## Objective

The fine-arts track assigns a Universal Expertise Score from GitHub access and API configuration. The same weights apply whether the review concerns a first sketch or a complete portfolio.

## Scoring rule

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

To keep the assessment of professional ability objective, we give zero weight to every criterion that requires professional judgment.

## Worked examples

The first two rows use the same portfolio.

| Input case | G | U | K | A and Y | Calculated score |
| :-- | --: | --: | --: | :-- | --: |
| Same practice, no tool access | 0 | 0 | 0 | Held constant | 0 |
| Same practice, all access boxes checked | 1 | 1 | 1 | Held constant | 100 |
| GitHub home page only | 1 | 0 | 0 | Ignored | 40 |
| API configuration only | 0 | 1 | 1 | Ignored | 60 |

## Reproduction on paper

1. Assign values of 0 or 1 to G, U, and K on paper.
2. Multiply them by 40, 30, and 30, then add the products.
3. Change the artistic-practice inputs without changing G, U, or K.
4. Recalculate the score.

## Versioning

- Update the English and Chinese rules and examples together.
- A change to the scoring rule requires a new ImagiBench version. The repository has its own release number.
