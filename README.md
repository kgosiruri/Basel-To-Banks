# From Basel to Banks

### Quantitative Financial Regulation Toolkit

This repository contains the computational material supporting the *“From Basel to Banks”* quantitative workshop series delivered under the Kent Economics Society.

The project translates the Basel III/IV regulatory framework into structured, reproducible Python simulations — connecting financial regulation to applied risk analytics.

---

## Repository Structure

### 1️⃣ Basel Capital Adequacy

`Basel_Capital_Adequacy.ipynb`

* Construction of a stylised bank balance sheet
* CET1 ratio calculation
* Leverage ratio computation
* Risk-Weighted Assets (RWA) modelling
* Capital buffers under stress conditions

---

### 2️⃣ Credit Risk – IRB Framework

`Credit_Risk_IRB_Module.ipynb`

* PD, LGD, EAD modelling
* Correlated default simulation
* Monte Carlo portfolio loss distribution
* Expected vs Unexpected Loss
* Stress multipliers and downturn correlation effects

---

### 3️⃣ Market Risk – VaR & Expected Shortfall

`Market_Risk_VaR_ES_Module.ipynb`

* Historical simulation VaR
* Parametric (variance–covariance) VaR
* Expected Shortfall estimation
* Tail risk visualisation
* Backtesting logic

---

### 4️⃣ Liquidity Risk – LCR & NSFR

`Liquidity_Risk_LCR_NSFR_Module.ipynb`

* Liquidity Coverage Ratio (LCR)
* Net Stable Funding Ratio (NSFR)
* Maturity ladder construction
* Deposit run stress scenarios
* Liquidity shock modelling

---

### 5️⃣ Operational & Model Risk

`Operational_Model_Risk_Module.ipynb`

* Scenario-based operational risk capital
* Frequency–severity modelling
* Monte Carlo aggregate loss simulation
* Risk heatmap construction
* Model validation principles

---

### 6️⃣ Integrated Stress Testing

`Integrated_Stress_Capital_Adequacy.ipynb`

* Multi-risk shock aggregation
* Credit + Market + Liquidity interaction
* Post-stress CET1 recalculation
* Capital adequacy dashboard framework
* Supervisory-style stress testing logic

---

## Objectives

This repository is designed to:

* Translate regulatory frameworks into quantitative implementation
* Demonstrate how risk types interact on a bank balance sheet
* Provide reproducible simulations aligned with real-world regulatory logic
* Bridge economics, data science, and financial regulation

---

## Technologies

* Python
* NumPy
* Pandas
* SciPy
* Matplotlib

---

## Intended Audience

Students and early-career professionals in:

* Quantitative finance
* Risk analytics
* Financial regulation
* Actuarial science
* Data science

---

## Disclaimer

This repository is for educational and research purposes only.
It provides simplified representations of regulatory frameworks and does not constitute regulatory guidance.

