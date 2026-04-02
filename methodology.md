# Methodology

## Problem Formulation
We formulate the central task for **Distributed Sybil Attack Detection in VANETs via Trust Scoring** through the governing equation below.

$$T^{(t+1)}(n) = (1-\eta)\,T^{(t)}(n) + \eta\cdot \mathrm{plaus}(n,t), \quad \mathrm{plaus}\in[0,1]$$

## Variable Definitions
| Symbol | Definition | Value |
|---|---|---|
| T^{(t+1)}(n) | Updated trust score for node n | Derived |
| \eta | Exponential moving average update rate | 0.20 |
| \mathrm{plaus}(n,t) | Kinematic plausibility score | [0,1] |

## Evaluation Logic
The repository is framed around benchmark-aware comparison, reproducible parameterization, and professor-friendly reporting.
