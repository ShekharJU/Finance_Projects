# Quantitative Finance & Risk Management Library

A high-performance computational suite for derivative pricing, stochastic modeling, and fixed-income analytics. This repository serves as a technical portfolio demonstrating the application of numerical methods to real-world financial engineering problems.

## 🚀 Technical Highlights

### 1. Stochastic Modeling & Discretization
* **Heston Model:** Implementation of stochastic volatility dynamics:
  $$dv_t = \kappa(\theta - v_t)dt + \sigma \sqrt{v_t} dW_t^v$$
* **Numerical Schemes:** Comparative analysis of **Euler** and **Milstein** discretization schemes to evaluate convergence rates and variance reduction.

### 2. Advanced Derivative Pricing
* **COS Method:** Fourier-based European option pricing, offering $O(1)$ complexity compared to traditional Monte Carlo methods.
* **Density Recovery:** Recovering risk-neutral probability density functions using **Fast Fourier Transforms (FFT)**.

### 3. Fixed Income & IR Analytics
* **Yield Curve Bootstrapping:** Multi-curve construction for Treasury and OIS environments.
* **Hull-White Models:** Pricing of Caplets, Floorlets, and Swaps using the **Jamshidian Trick** and 1-factor/2-factor path simulations.

### 4. Risk Engine
* **VaR Calculation:** Market risk assessment via **Historical Simulation** and **Monte Carlo** paths, including convexity corrections and exposure netting.






## 🛠 Tech Stack
* **Language:** Python
* **Core Libraries:** `NumPy` (Vectorized simulation), `SciPy` (Optimization & Statistics), `Matplotlib` (Visualization)

## 📁 Repository Structure
```text
/Computational_finance    # Stochastic processes & numerical pricing theory
/Financial_Engineering    # IR models (HW/Ho-Lee), Yield Curves, Risk Engines
/Outputs                  # Performance plots and model comparisons


Quantitative Finance & Fixed Income Library

This repository contains my personal implementations of numerical methods and financial models developed while studying the Computational Finance course materials.
Overview

This collection serves as a study companion to the book "Mathematical Modeling and Computation in Finance: With Exercises and Python and MATLAB Computer Codes" by C.W. Oosterlee and L.A. Grzelak. The implementations focus on bridging theoretical stochastic calculus with practical Python-based numerical solutions.
Topics Covered

The library includes implementations of:

    Stochastic Processes: Simulation of Heston (Stochastic Volatility), Merton Jump-Diffusion, and CIR processes.

    Option Pricing: Numerical pricing frameworks using the COS Method (Fourier-cosine expansion) and FFT-based density recovery.

    Fixed Income Analytics: Multi-curve frameworks, yield curve bootstrapping, and exotic interest rate derivatives (Swaps, Caplets) via Hull-White path simulations.

    Numerical Techniques: Euler-Maruyama and Milstein discretization schemes for path-dependent derivatives.

Academic Integrity & Attribution

    All core algorithmic logic and mathematical frameworks are based on the original research and materials provided by C.W. Oosterlee and L.A. Grzelak.

    These files represent my independent study, implementation, and annotation of the course lectures.

    Original headers and author attributions are maintained to respect the intellectual property of the creators.
