# FAIR Framework (Factor Analysis of Information Risk)

**FAIR** is an ontology for quantifying information and cyber risk in financial terms.

## Core model

| Term | Meaning |
|------|--------|
| **TEF** | Threat Event Frequency — how often a threat actor acts (e.g. per year) |
| **CS** | Contact Susceptibility — probability that contact results in a loss event (0–1) |
| **LEF** | Loss Event Frequency = TEF × CS |
| **PLM** | Primary Loss Magnitude — direct loss ($) per event |
| **SLM** | Secondary Loss Magnitude — indirect loss: regulatory, reputational, legal ($) |
| **ALE** | Annualized Loss Expectancy = LEF × (PLM + SLM) |

**In short:** risk = frequency of loss × magnitude of loss; ALE is the expected cost per year.

## In this repo

- **`fair_risk_register.ipynb`** — FAIR risk register: TEF, CS, PLM, SLM, ALE, optional Monte Carlo ranges, CIS Controls mapping.
- **`it_opportunity_matrix.ipynb`** — Links solutions to FAIR risk IDs and estimates ALE reduction from adoption.

## References

- [FAIR Institute](https://www.fairinstitute.org/) — framework and training
- [FAIR Wikipedia](https://en.wikipedia.org/wiki/Factor_analysis_of_information_risk)
