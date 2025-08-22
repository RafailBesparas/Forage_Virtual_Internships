# ☕ Citi Markets Quantitative Analysis Simulation – Coffee Futures Project

Welcome! This repository contains my completed work from the **Citi Markets Quantitative Analysis Virtual Experience Program**, hosted by **Forage**.

---

## 🧭 Program Overview

Through this simulation, I stepped into the role of a **Quantitative Analyst Intern** in Citi’s **Markets Division**, tasked with developing a robust pricing and risk management solution for **coffee futures contracts**. The experience mimicked real-world quantitative workflows within Citi’s Markets Quant (MQA) team.

---

## 📊 Key Deliverables

### 1. 📌 Futures Pricing
- Applied the **Cost of Carry model** to calculate fair futures prices:
  \[
  F = S \cdot e^{(r + c - y)T}
  \]
- Factored in real market conditions: storage costs, risk-free rate, and supply-demand dynamics

### 2. 📌 Structured Securities Design
- Created investment products tailored to different client risk profiles:
  - Conservative: Commodity-Linked Bonds
  - Moderate Risk: Structured Notes
  - High Risk: Digital Options
  - Diversification: Coffee-tracking ETFs
- Used **Monte Carlo simulation** to model potential returns

### 3. 📌 Risk Management Framework
- Built hedging strategies across three risk types:
  - **Market Risk**: Used futures/options to hedge price exposure
  - **Credit Risk**: Recommended letters of credit and credit insurance
  - **Operational Risk**: Suggested automation and process controls
- Applied **VaR**, **CVaR**, and **scenario analysis**

---

## 🧠 Skills Applied

| Area | Tools & Techniques |
|------|---------------------|
| Commodity Pricing | Cost of Carry Model, Black-Scholes |
| Risk Modeling | Monte Carlo Simulation, Value at Risk |
| Securities Structuring | Payoff Engineering, Digital Options |
| Quantitative Math | Stochastic Processes, PDEs, Linear Algebra |
| Programming | Python, NumPy, Matplotlib, fPDF |

---

## 📁 What's Included in This Repo

- `futures_pricing_model.py`: Pricing logic for coffee futures
- `structured_note_simulation.py`: Monte Carlo simulation for structured notes
- `etf_comparison.py`: Comparative model of ETFs vs notes
- `Structured_Securities_Proposal_Report.pdf`: Final PDF report summarizing all insights
- `README.md`: This overview

---

## 💡 What I Learned

✅ Structured real-world financial products from scratch  
✅ Applied rigorous quantitative analysis to manage commodity risk  
✅ Communicated technical findings for both quant and non-quant stakeholders  
✅ Gained exposure to pricing derivatives, designing risk-mitigating strategies, and optimizing product structures

## 📌 Acknowledgment

This project was completed as part of the **Citi Markets Quantitative Analysis Virtual Experience Program** offered by **Forage**. All content was created for educational and skill-development purposes.
