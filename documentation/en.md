<!-- ELUCENIA technical documentation · criterios-acr-eular-artrite-reumatoide · en · no clinical/professional/rights approval -->

# 2010 ACR/EULAR rheumatoid arthritis criteria

[conditions, sources and permissions](https://elucenia.org/en/tools/criterios-acr-eular-artrite-reumatoide)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Joint involvement (swelling or tenderness)

`artic`

- `0` — 1 large joint
- `1` — 2 to 10 large joints
- `2` — 1 to 3 small joints (with or without large joints)
- `3` — 4 to 10 small joints (with or without large joints)
- `5` — \> 10 joints (at least 1 small joint)

### Serology (rheumatoid factor and anti-CCP)

`soro`

- `0` — Both negative
- `2` — At least one low-positive titer (up to 3× the upper limit)
- `3` — At least one high-positive titer (\> 3× the upper limit)

### Acute-phase reactants (CRP and ESR)

`fase`

- `0` — Both normal
- `1` — Abnormal CRP or ESR

### Symptom duration

`duracao`

- `0` — \< 6 weeks
- `1` — ≥ 6 weeks

## Method edition

ACR/EULAR 2010: 4 domains, total 0–10, cutoff≥6; context and exclusions required

## Documented formula

Sum of four domains (maximum 10): joints (0–5), serology (0–3), acute-phase reactants (0–1) and symptom duration (0–1). Score ≥ 6 = definite rheumatoid arthritis.

Large joints: shoulders, elbows, hips, knees and ankles. Small: MCP, PIP, 2nd–5th MTP, thumb IP and wrists.

## Limits and population

The ACR/EULAR 2010 classification requires confirmed synovitis in at least one joint and no alternative diagnosis that better explains it before applying the ≥6/10 cutoff. It was developed for newly presenting undifferentiated inflammatory synovitis. The score alone, without these conditions, does not reproduce the classification criteria.

## References

- [Aletaha D et al. 2010 Rheumatoid arthritis classification criteria: an American College of Rheumatology/European League Against Rheumatism collaborative initiative. Arthritis Rheum, 2010.](https://doi.org/10.1002/art.27584)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Documented results

The information below preserves the method outputs for synthetic examples. It does not constitute independent clinical validation.

### 1

Classifies as definite rheumatoid arthritis (≥ 6 points)


### 2

Classifies as definite rheumatoid arthritis (≥ 6 points)


### 3

Does not meet the classification criteria (< 6 points)

Does not exclude rheumatoid arthritis: reassess over time.

