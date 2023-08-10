# US-Stimulant-OD-History

## Overview

These files are associated with the following publication:
Kline D, Bunting AM, Hepler SA, Rivera-Aguirre A, Krawczyk N, Cerda M. State-Level History of Overdose Deaths Involving Stimulants in the United States, 1999‒2020. Am J Public Health. 2023 Sep;113(9):991-999. doi: [10.2105/AJPH.2023.307337](https://doi.org/10.2105/ajph.2023.307337). PubMed PMID: [37556789](https://pubmed.ncbi.nlm.nih.gov/37556789/).

## Contents

* [rates.gif](../main/rates.gif): Maps showing the posterior median overdose death rate per 100,000 residents for deaths involving each drug type from 1999-2020.  Red outlines reflect a posterior probability of greater than 0.9 that the rate increased from the previous year, and blue outlines reflect a posterior probability of greater than 0.9 that the rates decreased from the previous year.
* [relative_risk.gif](../main/relative_risk.gif): Maps showing the posterior median log relative risk of death for the current year compared to the previous year for deaths involving each drug type from 2000-2020.  Red outlines reflect a posterior probability of greater than 0.9 that the rate increased from the previous year, and blue outlines reflect a posterior probability of greater than 0.9 that the rates decreased from the previous year.
* [MCMCClean.R](../main/MCMCClean.R): R script that demonstrates the code for fitting the multiple change point model via MCMC implmented in nimble. Since data are restricted and cannot be shared, the code is not executable but rather an example of how the model was fit that can be translated to a new application.
