# Supplementary Data: Global Events and Cryptocurrency Performance (JIMF 2025)

This repository provides supplementary datasets for the article:

Polyzos, E., and Youssef, L. (2025). Investigating the impact of global events on cryptocurrency performance: a big data event study approach. Journal of International Money and Finance, 157, 103375. https://doi.org/10.1016/j.jimonfin.2025.103375

## Contents

### Data
- data/py_crypto_market_index.csv  
  Market capitalisation-weighted crypto market index constructed to capture at least 80% of total market capitalisation each day (daily reconstitution).
- data/py_crypto_market_index_quarterly_rebalancing.csv  
  Same index concept with quarterly rebalancing (robustness variant).
- data/betas_full_sample.csv  
  CAPM-style beta estimates for all coins for the full sample period.
- data/betas_monthly.csv  
  Beta estimates by month.
- data/betas_annual.csv  
  Beta estimates by year.

## Notes on construction
The market index is a market-cap weighted return series based on the set of cryptocurrencies that jointly account for at least 80% of total market capitalisation on each day. A quarterly rebalanced alternative is provided for robustness.

Beta estimates are provided for all cryptocurrencies in the sample, both for the full sample and in time-sliced variants (monthly and annual).

## How to cite
If you use these data, please cite:

Polyzos, E., and Youssef, L. (2025). Investigating the impact of global events on cryptocurrency performance: a big data event study approach. Journal of International Money and Finance, 157, 103375. https://doi.org/10.1016/j.jimonfin.2025.103375

A machine-readable citation is provided in CITATION.cff.

## License

This repository is released under the **MIT License**.

You are free to use, copy, modify, merge, publish, distribute, and adapt the contents of this repository for academic, policy, and non-commercial purposes, subject to the terms of the MIT License.

While the MIT License does not legally require citation, **academic use of these data requires appropriate citation**. 

## Disclaimer
The data are provided for research and educational purposes only.  Users are responsible for ensuring appropriate use and citation.

## Versioning
This repository follows a simple date-based versioning convention.

- Each public update corresponds to a new version of the data and/or documentation.
- The file `data/LAST_UPDATED.txt` records the most recent update date.
- Earlier versions may differ in variable definitions, coverage, or construction methods.

Users are encouraged to record the version date used in their analysis and to ensure consistency when comparing results across updates.



