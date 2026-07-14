# Consumer Choice Modelling using Multinomial Logit Models

An econometric project that estimates a Multinomial Logit (MNL) model to analyse consumer preferences for alternative credit card products and evaluate policy and product design scenarios.

## Overview

This project applies discrete choice modelling to analyse consumer preferences in the credit card market. A Multinomial Logit (MNL) model is estimated using Maximum Likelihood Estimation (MLE) to quantify how product characteristics and consumer demographics influence product choice.

The estimated model is subsequently used to simulate the introduction of a new credit card product and evaluate the impact of an interest rate cap policy on consumer choice probabilities.

## Project Summary

| Attribute | Value |
|-----------|-------|
| Domain | Discrete Choice Modelling |
| Method | Multinomial Logit (MNL) |
| Estimation | Maximum Likelihood |
| Language | R |
| Dataset | Credit Card Choice Data |
| Applications | Product Simulation & Policy Analysis |

## Objectives

- Estimate a Multinomial Logit model using Maximum Likelihood Estimation.
- Quantify the effect of product attributes on consumer choice.
- Simulate the market introduction of a new credit card.
- Evaluate the impact of an interest rate cap policy.

## Dataset

The analysis uses a stated-preference dataset containing individual choices among five alternatives:

- Four credit card products
- One opt-out alternative

The dataset includes:

- Annual fees
- Interest rates
- Reward programmes
- Customer income
- Customer age
- Credit balance
- Observed consumer choices

## Methodology

The project follows the workflow below:

1. Utility function specification
2. Model identification and normalisation
3. Maximum Likelihood Estimation
4. Parameter interpretation
5. Choice probability estimation
6. Market simulation
7. Policy scenario analysis

## Model

The following econometric model was implemented:

- Multinomial Logit (MNL)

The model estimates both:

- Generic coefficients for product attributes
- Alternative-specific constants and demographic effects

## Evaluation

The estimated parameters are interpreted in terms of consumer preferences and substitution behaviour.

The model is subsequently applied to:

- predict market shares,
- simulate the introduction of a new product,
- evaluate the effects of regulatory interventions.

## Results

The estimated model successfully captures how annual fees, interest rates, reward programmes and demographic characteristics influence credit card choice.

Scenario analysis demonstrates how both product design changes and policy interventions affect predicted consumer market shares.

The following figures present selected model outputs and simulation results.

## Technologies

- R
- Maximum Likelihood Estimation
- Discrete Choice Analysis

## Repository Structure

```text
consumer-choice-multinomial-logit/

│
├── data/
├── results/
├── report/
└── README.md
```

## Repository Contents

| Folder | Description |
|----------|-------------|
| data | Credit card choice dataset |
| results | Model outputs and figures |
| report | Final project report |

## Key Visualizations

### Estimated Choice Probabilities

*(Insert figure)*

### New Product Market Share Simulation

*(Insert figure)*

### Interest Rate Cap Policy Simulation

*(Insert figure)*

## Author

**Konstantinos Papavrontos**

MSc Candidate in Business Economics with Analytics  
Athens University of Economics and Business
