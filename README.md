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

## 📊 Visual Portfolio




## 🛠 Tech Stack
* **Language:** Python
* **Core Libraries:** `NumPy` (Vectorized simulation), `SciPy` (Optimization & Statistics), `Matplotlib` (Visualization)

## 📁 Repository Structure
```text
/Computational_finance    # Stochastic processes & numerical pricing theory
/Financial_Engineering    # IR models (HW/Ho-Lee), Yield Curves, Risk Engines
/Outputs                  # Performance plots and model comparisons
