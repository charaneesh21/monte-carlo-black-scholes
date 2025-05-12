# Monte Carlo Simulation of Black-Scholes Option Pricing

This project implements a Monte Carlo simulation to estimate the price of European call and put options, and compares the results with the analytical solution provided by the Black-Scholes model.

## 📈 Overview

The simulation uses the geometric Brownian motion (GBM) model to generate future stock prices and computes the option payoff based on these simulations. The main objectives of this project are:

- Simulate terminal stock prices using GBM.
- Estimate European call and put option prices via Monte Carlo.
- Compare Monte Carlo estimates with the Black-Scholes closed-form solution.
- Analyze convergence and runtime performance.
- Visualize distribution and convergence using plots.
