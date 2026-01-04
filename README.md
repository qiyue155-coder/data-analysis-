# Solvency-Based Pricing & Stress Testing under EV Transition Scenarios

This project develops an actuarial pricing framework for motor insurance using frequency–severity modeling and evaluates capital adequacy under electric vehicle (EV) transition scenarios.

## Project Overview

- Built a frequency–severity pricing model using the French MTPL insurance dataset
- Modeled claim frequency using Poisson / Negative Binomial GLMs with exposure offsets
- Modeled claim severity using parametric distributions (Gamma / Lognormal)
- Simulated aggregate losses via Monte Carlo methods
- Calculated solvency capital requirements based on Value-at-Risk (VaR)
- Assessed premium impacts under EV transition scenarios through stress testing

## Repository Structure

data-analysis-/
├── notebooks/ # Pricing model implementation and analysis
├── report/ # Final written report (PDF)
└── README.md

## Key Methods

- Generalized Linear Models (GLMs)
- Frequency–Severity decomposition
- Monte Carlo simulation
- Solvency-based pricing
- Scenario and stress testing analysis

## Data

The analysis is based on the French Motor Third-Party Liability (MTPL) dataset.  
Raw data files are not included in this repository.

## Notes

This project is intended for academic and portfolio demonstration purposes.

