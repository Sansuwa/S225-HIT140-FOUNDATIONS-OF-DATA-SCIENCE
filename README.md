# S225-HIT140-FOUNDATIONS-OF-DATA-SCIENCE

## Team Members:

- Sansuwa Shrestha
- Binu Regmi
- Shanti Moktan
- Sejal Pradhan

# Investigation A: Bat Risk-taking in Presence of Rats

This repository contains the data, analysis, and report for a study on how bats modify their feeding behaviour when rats are present near feeding platforms.

## Overview

- **Objective:** Investigate whether rat presence influences bat risk-taking behaviour.
- **Datasets:**
  - **Dataset1** (n = 907 landings): Individual bat observations (timing, risk, reward, rat arrival).
  - **Dataset2** (n = 2123 periods): Summarised 30-minute observation blocks.
- **Methods:** Data cleaning, descriptive statistics, hypothesis tests, and logistic regression.

## Key Findings

- 901 of 907 bat landings occurred after rat arrival → limited comparison with rat-absent conditions.
- **Rat** was the strongest predictor of risk-taking (odds ratio ≈ 0.05, p < 0.001).
- **Seconds after rat arrival** and **hours after sunset** were not significant predictors.
- Behavioural differences with and without rats could not be directly assessed.

## Repository Structure

```
data/           # Raw and cleaned datasets
analysis/       # Scripts for statistical analysis
figures/        # Generated plots and charts
report/         # Full investigation report (PDF)
README.md       # Project documentation
```

## Future Work

- Collect more observations in rat-absent conditions.
- Use mixed-effects models to account for repeated measures.
- Influence of Weather on both animals food competition.
