# ImagiBench v1.0

[English](BENCHMARK.md) · [简体中文](docs/zh-CN/BENCHMARK.md) · [Project home](README.md)

**Fictional satirical benchmark. No measurements, subjects, experiments, or model comparisons exist. Every score below is a constructed arithmetic example, not a result.**

## Objective

ImagiBench evaluates an imaginary claim: that access to technical tools grants authority over unrelated professions. The fine-arts track deliberately removes art from its evaluation criteria.

The benchmark does not ask whether AI can generate images or whether APIs are useful. It asks what happens when an evaluator substitutes tool access for the skill being judged.

## Fictional scoring rule

| Symbol | Fictional criterion | Assigned weight |
| :-- | :-- | --: |
| G | Can open the GitHub home page | 40% |
| U | Can fill in a Base URL | 30% |
| K | Can fill in an API key | 30% |
| A | Anatomy, color, composition, and original design | 0% |
| Y | Years of artistic practice | 0% |

```text
Universal Expertise Score = 40G + 30U + 30K
G, U, K are fictional binary inputs: 0 or 1.
A and Y have no effect, by construction.
```

The maximum constructed score is 100 points. The units are invented. There is no pass threshold, dataset, evaluator, model endpoint, credential check, or software implementation. The contribution access test is a separate ceremony; contributors need no benchmark score.

**Methodological rationale:** to prevent professional knowledge from influencing the assessment of professional ability, all domain-specific criteria have been excluded.

## Constructed examples, not measured results

The rows below describe invented input combinations, not real people or representative groups. Artistic practice is held constant in the first two rows; only tool access changes.

| Fictional paper case | G | U | K | A and Y | Constructed score |
| :-- | --: | --: | --: | :-- | --: |
| Same practice, no tool access | 0 | 0 | 0 | Held constant | 0 |
| Same practice, all access boxes checked | 1 | 1 | 1 | Held constant | 100 |
| GitHub home page only | 1 | 0 | 0 | Ignored | 40 |
| API configuration only | 0 | 1 | 1 | Ignored | 60 |

The 100-point difference in the first two rows contains exactly zero additional artistic information. That is the finding about the scoring rule, not about the people it pretends to assess.

## Reproduction on paper

1. Choose imaginary values of 0 or 1 for G, U, and K.
2. Multiply them by 40, 30, and 30; add the products.
3. Change the imagined artistic practice without changing G, U, or K.
4. Observe that the score cannot change.

Do not call a model, enter an API key, upload artwork, or assess a real person. Reproduction requires arithmetic, not a subscription.

## Validity assessment

| Question | Assessment |
| :-- | :-- |
| Does it measure artistic ability? | No. Artistic ability is excluded. |
| Does it measure programming ability? | No. Access and form filling do not establish programming competence. |
| Does it compare GPT with Claude? | No. No models were evaluated. |
| Does it measure human worth? | No. No such inference is supported. |
| What does it demonstrate? | A scoring rule can encode the evaluator's prejudice while looking quantitative. |

There are no confidence intervals, latency numbers, throughput figures, leaderboards, or superiority claims against real systems. The problem is construct validity: the chosen variables do not establish the claimed expertise. More decimal places would not fix it.

## Publication rules

- Keep “fictional” or “satire” adjacent to any reused table or score.
- Never present these values as empirical measurements or use them to rank people.
- Do not add real company logos, invented endorsements, fabricated star counts, or model results.
- Update the English and Chinese rules and examples together.
- A new fictional rule needs a new benchmark version; the repository release number is separate.

---

*Satire. ImagiBench exposes a category error; it does not certify expertise.*
