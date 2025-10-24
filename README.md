# Call Option Pricing and Sensitivity Analysis

This project demonstrates how to price a **European call option** using **Monte Carlo simulations** and the **Black–Scholes formula**, and explores the option's **sensitivities (Greeks)**: **Delta, Vega, and Theta**.

## Features

- **Monte Carlo simulation**: Approximated the fair call price and visualise the distribution of simulated stock prices at maturity.
- **Black–Scholes formula**: Computed the analytical call price for comparison.
- **Monte Carlo convergence analysis**: Showed how the estimated call price stabilises as the number of simulations increases.
- **Option Greeks**:
  - **Delta**: Sensitivity of the call price to small changes in stock price.
  - **Vega**: Sensitivity of the call price to changes in volatility.
  - **Theta**: Sensitivity of the call price to the passage of time.
- **Visualisations**: Line plots for analyses.

## Skills Demonstrated

- Numerical simulation (**Monte Carlo**)  
- Financial engineering concepts (European call options, payoffs, Greeks)  
- Closed-form solutions (**Black–Scholes formula**)  
- Visualisation (**numpy, pandas, matplotlib, scipy**)  
- Clean, organised Python coding

## How to run

1. Clone this repository
2. Install required libraries:
   pip install numpy pandas scipy matplotlib
3. Open and run jupyter notebook

