# Insurance ABM SIMBRA

This repository contains an agent-based model implemented in NetLogo to study insurance markets under adverse selection, insurer pricing strategies, government subsidies, and capital constraints.
This version of the model was presented at the 1st Brazilian Interdisciplinary Symposium on Agent-Based Models – São Paulo, May 28, 2026.


## Model overview

The model simulates a population of heterogeneous consumers exposed to disaster risk. Consumers differ in wealth, risk type, and risk aversion. An insurance company offers coverage, receives premiums, pays insured losses, and may adjust prices according to different strategies. Government subsidies the luckiest or the unluckiest members of society if they can’t buy the insurance.

## Main mechanisms

- Voluntary or mandatory insurance market
- Symmetric or asymmetric information
- Government subsidies
- Insurer capital constraint
- Aggregate price adjustment after losses
- Bühlmann credibility-based individual risk updating

## Files

- `insurance_v_simbra.nlogox`: main NetLogo model
- `consumers.nls`: consumer procedures
- `companies.nls`: company procedures
- `reporters.nls`: reporter procedures

## Requirements

- NetLogo 7.0.4

## How to run

1. Open NetLogo.
2. Load `insurance_v_simbra.nlogox`.
3. Configure the desired scenario using the interface controls.
4. Click `setup`.
5. Click `go` or run BehaviorSpace experiments.

## Citation

If you use this model, please cite this repository and NetLogo.

SANTOS, André Ferreira. Dinâmicas de mercados de seguros com informação assimétrica: evidências de um modelo baseado em agentes. In: 1° SIMPÓSIO INTERDISCIPLINAR BRASILEIRO DE MODELOS BASEADOS EM AGENTES, 2026, São Paulo. São Paulo, 28 maio 2026. Repositório: https://github.com/andresnts/insurance-abm-simbra

## License

This project is licensed under the MIT License.
