# 📊 Applied Statistics Portfolio (Statistics 1 & 2)

[![Excel](https://shields.io)](https://microsoft.com)
[![Python](https://shields.io)](https://python.org)
[![Jupyter](https://shields.io)](https://jupyter.org)
[![IIT Madras](https://shields.io)]()

A structured repository containing extra activities, empirical practice problems, and computational mini-projects for **Statistics 1 (Descriptive & Foundational)** and **Statistics 2 (Inferential & Probability Models)**.

This portfolio serves as a core mathematical sandbox, demonstrating how theoretical statistics are translated into real-world spreadsheets and algorithmic Python simulations.

---

## 🎯 Portfolio Core Focus

* 📈 **Descriptive Statistics** – Central tendency modeling, dispersion analysis, and high-density frequency distributions.
* 🎲 **Probability & Stochastic Simulations** – Algorithmic dice roll modeling using custom Monte Carlo frameworks.
* 🔔 **Theoretical Probability Models** – Application of the Normal Distribution Model and empirical rule evaluations on real corporate financials.
* ⚖️ **Asymptotic Theorems** – Computational verification of the **Central Limit Theorem (CLT)** via sampling distribution simulators.
* 📉 **Bivariate Relationships** – Covariance evaluation and scatter-plot matrix analysis for financial risk management ratios.

---

## 🛠 Tech Stack & Analytical Ecosystem

* **Spreadsheet Modeling:** Microsoft Excel (Advanced Formulas, Descriptive Data Analysis Toolpak, Chart Engines)
* **Computational Notebooks:** Google Colab, Jupyter Notebooks (`.ipynb`)
* **Core Libraries:** `numpy`, `pandas`, `matplotlib`, `scipy.stats`, `openpyxl`

---

## 📂 Repository Architecture & Activities

```text
basic-statistics-projects/
├── 📊 Statistics 1 — Descriptive Foundations/
│   ├── 📁 STATISTICS-1-EXTRA_ACTIVITY_2    # Baseline frequency tables & distributions
│   ├── 📁 STATISTICS-1-EXTRA_ACTIVITY_3    # Central Tendency metrics (Mean, Median, Mode)
│   └── 📁 STATISTICS-1-EXTRA_ACTIVITY_4    # Categorical/Continuous variable plotting
│
└── 🎲 Statistics 2 — Probability & Inference/
    ├── 📁 STATISTICS-2-EXTRA_ACTIVITY_1    # Netflix dataset structural analysis
    ├── 📁 STATISTICS-2-EXTRA_ACTIVITY_2    # Monte Carlo Dice Simulation (Stochastic pipeline)
    ├── 📁 STATISTICS-2-EXTRA_ACTIVITY_3    # Corporate Debt Ratios (Liquidity Covariance)
    ├── 📁 STATISTICS-2-EXTRA_ACTIVITY_4    # Google Profit Performance & Normal Model Curves
    └── 📁 STATISTICS-2-EXTRA_ACTIVITY_5    # Central Limit Theorem (CLT Sampling Engine)
```

---

## 🚀 Deep-Dive: Key Statistical Implementations

### 1. 🎲 Monte Carlo Dice Simulation (`Statistics-2, Activity 2`)
* **Mathematical Concept:** Law of Large Numbers (LLN).
* **Implementation:** A Python script in `.ipynb` that runs thousands of stochastic dice rolling iterations to empirically map actual outcomes against theoretical probability vectors, complete with real-time distribution convergence charts.

### 2. 📉 Corporate Ratio Covariance Analysis (`Statistics-2, Activity 3`)
* **Mathematical Concept:** Bivariate correlation coefficient ($r$) and structural covariance.
* **Implementation:** Processes key liquidity metrics—**Current Ratio, Quick Ratio, and Cash Ratio**—using corporate balance sheets to map out directional scatterplots and trace linear dependencies.

### 3. 🔔 Google Profit Tracking via Normal Model (`Statistics-2, Activity 4`)
* **Mathematical Concept:** Continuous Gaussian Distributions:
  $$f(x) = \frac{1}{\sigma \sqrt{2\pi}} e^{-\frac{1}{2}\left(\frac{x-\mu}{\sigma}\right)^2}$$
* **Implementation:** Models Google's historical quarterly corporate profit sheets against a theoretical normal curve to compute z-scores and extract probability densities for future performance thresholds.

### ⚖️ 4. Empirical Verification of the Central Limit Theorem (`Statistics-2, Activity 5`)
* **Mathematical Concept:** Asymptotic Normality of Sample Means.
* **Implementation:** Simulates skewed non-normal distributions in Python. Upon running randomized multi-batch sampling cycles, the script demonstrates how the resulting **Sampling Distribution of the Sample Mean ($\bar{X}$)** naturally converts into a perfect symmetric Gaussian bell-curve as sample size ($n$) scales.

---

## 🎮 How to Run and Interact

### Execution Path A: Excel Workspace
1. Navigate into any target activity folder (e.g., `STATISTICS-2-EXTRA_ACTIVITY_3/`).
2. Download and open the `.xlsx` file natively in Microsoft Excel.
3. Access active formula bars to view underlying mathematical statements.

### Execution Path B: Python & Jupyter Framework
To reproduce the Monte Carlo simulations or Central Limit Theorem pipelines locally, spin up your environment using:

```bash
# 1. Install required analytical packages
pip install numpy pandas matplotlib scipy openpyxl notebook

# 2. Launch the server workspace
jupyter notebook
```
*Alternatively, you can drag and drop any `.ipynb` file directly into your **Google Colab** dashboard.*
