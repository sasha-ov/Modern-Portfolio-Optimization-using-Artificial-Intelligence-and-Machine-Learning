# Modern-Portfolio-Optimization-using-Artificial-Intelligence-and-Machine-Learning
## Overview

This project explores **portfolio optimization** by combining classical financial theory with modern computational approaches. It evaluates both **traditional models** (e.g., Equal-Weighted, Maximum Sharpe, Minimum Volatility, CAPM, Fama-French) and **AI/ML-based strategies** (PCA, Hierarchical Risk Parity, Reinforcement Learning) to improve portfolio construction and risk management.

The goal is to provide a framework for **adaptive, data-driven asset allocation** that can balance risk and return in dynamic financial markets.

---

## Key Features

* Implementation of **classical optimization strategies**:

  * Equal-Weighted (Naïve) Portfolio
  * Maximum Sharpe Ratio Portfolio
  * Minimum Volatility Portfolio

* **Statistical & Factor Models**:

  * Capital Asset Pricing Model (CAPM)
  * Fama-French Three-Factor Model

* **AI/ML-based approaches**:

  * **Principal Component Analysis (PCA)** – dimensionality reduction for eigen-portfolios
  * **Hierarchical Risk Parity (HRP)** – tree-based clustering for robust diversification
  * **Reinforcement Learning (RL)** – dynamic rebalancing using reward-driven learning

* **Monte Carlo Simulations** to visualize portfolio feasibility space and the Efficient Frontier

* **Empirical Testing**:

  * Applied to the **Magnificent Seven (MAG7)** tech stocks
  * Extended to the **Dow Jones 30 (DJ30)** for broader market coverage
  * Trained on data from 2021-2023 market data and back tested on data from 2024 market data

---

## Results Summary

* **Max Sharpe Ratio Portfolio** delivered the strongest returns but carried higher volatility.
* **Minimum Volatility Portfolio** offered consistent risk reduction, suited for conservative investors.
* **PCA-based portfolios** concentrated in TSLA and NVDA, capturing market variance effectively.
* **HRP** provided balanced allocations across DJ30, reducing concentration risk.
* **RL models** demonstrated adaptability to changing market conditions.

---

## Tech Stack

* **Language**: Python
* **Libraries**: `numpy`, `pandas`, `scipy`, `scikit-learn`, `matplotlib`, `yfinance` (for data)
* **Optimization**: Linear & quadratic programming, eigenvalue decomposition, clustering methods
* **Machine Learning**: PCA, hierarchical clustering, reinforcement learning (DQN, policy gradients)

## Reference
## 📚 References

[1] Wikipedia contributors. *Dow Jones Industrial Average* — Wikipedia, the free encyclopedia, 2024. Accessed: 2024-04-27.
[2] Marcos López de Prado. *Building Diversified Portfolios That Outperform Out-of-Sample*. SSRN Electronic Journal, 2016. SSRN preprint, [https://ssrn.com/abstract=2708678](https://ssrn.com/abstract=2708678).
[3] Fidelity Viewpoints. *What are the Magnificent 7 stocks?* [https://www.fidelity.com/learning-center/smart-money/magnificent-7-stocks](https://www.fidelity.com/learning-center/smart-money/magnificent-7-stocks), 2024. Accessed: 2024-04-27.
[4] Stefan Jansen. *Machine Learning for Algorithmic Trading*. Packt Publishing, Birmingham, UK, 2nd edition, 2020. Chapter 22: Deep Reinforcement Learning – Building a Trading Agent.
[5] Steven Johnson. *Python for Quant Finance: Building Financial Models and Trading Algorithms*. Independently Published, 2021.
[6] Eryk Lewinson. *Python for Finance Cookbook*. Packt Publishing, Birmingham, UK, 2nd edition, 2022.
[7] Hariom Tatsat, Sahil Puri, and Brad Lookabaugh. *Machine Learning and Data Science Blueprints for Finance: From Building Trading Strategies to Robo-Advisors Using Python*. O’Reilly Media, Sebastopol, CA, 2021.
