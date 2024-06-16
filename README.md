# The Causal Effect of IVF Treatment Protocol

## Overview
This project assesses how different In-Vitro Fertilization (IVF) treatment protocols affect the chances of successful conception. Using observational data from multiple IVF treatments, various causal inference methods and machine learning algorithms were applied to estimate the Average Treatment Effect (ATE) and identify significant factors influencing IVF success rates.

## Data
The dataset consists of observational data from multiple IVF treatments, including various treatment protocols and patient characteristics. This data was used to analyze the impact of different protocols on the success rates of IVF.

## Methodology
The following causal inference methods and machine learning algorithms were used in this project:
- **Inverse Propensity Weighting (IPW)**
- **S-Learner**
- **T-Learner**
- **X-Learner**
- **XGBoost**: Used for feature importance to identify significant factors influencing IVF success rates.

## Key Findings
- The analysis revealed insights into how different treatment protocols impact the success rates of IVF.
- Initially, naively estimating the ATE, one of the treatment protocols seems to be superior with a higher proportion of successful pregnancies.
- However, after correcting for possible confounders, the examined treatment protocols appear to be interchangeable with no significant difference in their success rates for resulting in successful conception.

## Code
- The code is organized into scripts that perform data preprocessing, apply causal inference methods, and generate visualizations of the results.
