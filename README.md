# European-Cattle-Analysis-FiBL
This repository contains the R analysis developed during a Master's internship at the Research Institute of Organic Agriculture (FiBL), Switzerland.

## Project objective

To explore European cattle breed-country records from FAO's Domestic Animal Diversity Information System (DAD-IS), classify records by reported production purpose and breed adaptedness, and compare selected productivity indicators.

## Data source

FAO Domestic Animal Diversity Information System (DAD-IS): https://www.fao.org/dad-is/

The analysis uses a European subset of 792 breed-country records derived from a DAD-IS cattle export.

## Classification

Production-purpose groups were derived from the DAD-IS Provision Uses field:

- Dairy: milk reported without meat
- Meat: meat reported without milk
- Dual Purpose: both milk and meat reported
- Others: neither milk nor meat reported, including missing provision uses

These are operational classifications of reported uses and should not be interpreted as independently validated breeding objectives.

## Analyses

The project includes descriptive summaries, data-availability assessments, boxplots, Welch's two-sample t-tests and linear models with ANOVA.

Five productivity indicators were examined: milk yield per lactation, annual milk yield, milk protein, milk fat and carcass weight.

## Reproducibility

The analysis was performed using R. The original DAD-IS export and the same country-selection criteria are required to reproduce the reported results. R and package versions should be checked against the session information.

## Limitations

DAD-IS does not provide sufficient farm-level management and feeding information to establish whether the recorded cattle populations belong to grass-based or other context-specific livestock production systems.
