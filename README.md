# US-Stimulant-OD-History

## Overview

These files are associated with a paper currently in peer review. More details will be added pending the outcome of the review.

## Contents

* [rates.gif](../main/rates.gif): Maps showing the posterior median overdose death rate per 100,000 residents for deaths involving each drug type from 1999-2020.  Red outlines reflect a posterior probability of greater than 0.9 that the rate increased from the previous year, and blue outlines reflect a posterior probability of greater than 0.9 that the rates decreased from the previous year.
* [relative_risks.gif](../main/relative_risks.gif): Maps showing the posterior median log relative risk of death for the current year compared to the previous year for deaths involving each drug type from 2000-2020.  Red outlines reflect a posterior probability of greater than 0.9 that the rate increased from the previous year, and blue outlines reflect a posterior probability of greater than 0.9 that the rates decreased from the previous year.
* [MCMCClean.R](../main/MCMCClean.R): R script that demonstrates the code for fitting the multiple change point model via MCMC implmented in nimble. Since data are restricted and cannot be shared, the code is not executable but rather an example of how the model was fit that can be translated to a new application.
