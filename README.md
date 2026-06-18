

# State Minimum Wage Increases and Teenage Employment in the United States

## Overview

This repository contains an empirical analysis of how state-level minimum-wage increases affected employment among U.S. teenagers aged 16–19 between 1990 and 2013.

The study uses annual Current Population Survey data aggregated to the state-year level. States are classified as treated from the first year in which their statutory minimum wage exceeds the federal minimum wage. States that do not exceed the federal rate during the sample period form the principal comparison group.

The analysis was conducted in Stata using a staggered Difference-in-Differences framework.

## Research questions

- Do state minimum-wage increases reduce teenage employment?
- Are the effects different for male and female teenagers?
- Are full-time and part-time workers affected differently?
- Do the findings remain after adjusting minimum wages for inflation?
- Were treated and comparison states following similar employment trends before treatment?
- Do employment effects emerge immediately or develop over time?

## Data

The dataset combines:

- Current Population Survey employment data
- Annual state-level observations from 1990 to 2013
- State and federal minimum-wage data
- Consumer Price Index data
- Nominal and inflation-adjusted minimum wages
- Employment outcomes for teenagers aged 16–19

The principal outcomes include:

- Overall teenage employment
- Male and female employment
- Full-time and part-time employment
- Gender-specific full-time and part-time employment
- Retail and restaurant employment
- School-enrolment status

Employment fractions are converted into percentages so that estimated coefficients can be interpreted as percentage-point changes.


## Methodology

The empirical analysis includes:

- Staggered Difference-in-Differences estimation
- State fixed effects
- Year fixed effects
- Nominal and real minimum-wage specifications
- Placebo testing
- Event-study analysis
- Treated-versus-comparison trend analysis
- Gender-specific employment models
- Full-time and part-time employment models
- Descriptive statistics and correlation analysis

State fixed effects control for persistent differences between states, including industrial composition, institutions and baseline labour-market conditions.

Year fixed effects control for national shocks affecting all states in the same year, including recessions, inflation and federal policy changes.

## Main findings

- State minimum-wage increases are associated with an estimated **1.316 percentage-point reduction** in overall teenage employment.
- The inflation-adjusted specification produces a similar estimated reduction of approximately **1.320 percentage points**.
- Female teenage employment shows a larger estimated decline than male employment.
- Female employment declines by an estimated **2.068 percentage points** in the nominal specification.
- Full-time teenage employment declines by an estimated **1.409 percentage points**.
- Male employment effects are not statistically significant in the main specifications.
- Part-time employment effects are comparatively small and statistically insignificant.
- The placebo analysis does not identify a statistically meaningful pre-treatment effect.

## Interpretation

The findings suggest that employment adjustments were concentrated among particular groups rather than distributed uniformly across the teenage labour market.

Female and full-time teenage workers appear more exposed to employment adjustment following an increase in the state minimum wage. This may indicate that employers responded by changing the composition of teenage employment rather than reducing all employment categories proportionately.

The results should be interpreted as average effects across states and treatment periods. Their magnitude may depend on local labour-market conditions, industry composition, policy intensity and treatment timing.

## Limitations

- The principal model uses a pooled two-way fixed-effects estimator.
- Treatment effects may vary across states, treatment cohorts and years.
- The model does not estimate separate group-time treatment effects for every treatment cohort.
- State-level aggregation may conceal individual employment transitions.
- Policy adoption may be related to economic or political conditions that also affect employment.
- The treatment indicator captures whether a state exceeds the federal minimum wage but not the full size of each wage increase.
- Placebo and event-study results provide diagnostic evidence but do not conclusively establish the identifying assumptions.

## Repository contents

- Research paper
- Research presentation
- Stata source files
  
## Author

**Ruchir Banerjee**

MSc Economics  


## Citation

Banerjee, R. (2025). *State Minimum Wage Increases and Teenage Employment in the United States: Evidence from a Difference-in-Differences Analysis, 1990–2013*.

## Disclaimer

This repository is provided for academic, educational and portfolio purposes.

The findings depend on the data, treatment definitions, identifying assumptions and econometric specifications used in the analysis. They should not be interpreted as legal, financial or public-policy advice.
