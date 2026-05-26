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

- `models/boltzmann_wealth_insurance.nlogox`: main NetLogo model
- `models/consumers.nls`: consumer procedures
- `models/companies.nls`: company procedures
- `models/reporters.nls`: reporter procedures
- `experiments/`: BehaviorSpace experiment configurations
- `results/`: selected output files

## Requirements

- NetLogo 7.0.4 or later

## How to run

1. Open NetLogo.
2. Load `models/boltzmann_wealth_insurance.nlogox`.
3. Configure the desired scenario using the interface controls.
4. Click `setup`.
5. Click `go` or run BehaviorSpace experiments.

## Citation

If you use this model, please cite this repository and NetLogo.

## License

This project is licensed under the MIT License.
