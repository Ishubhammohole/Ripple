# 🌊 Ripple

**Simulating Fairness Before It Happens**

Ripple is an AI-driven economic simulation tool designed to help policymakers and researchers explore the impact of policy decisions — such as changes in minimum wage, tax rate, or rent subsidy — on a synthetic population.  

It combines a **Monte Carlo simulation backend**, **Gemini AI** for natural-language summaries, and an **interactive frontend** built in React for real-time data visualization.

---

## 🎯 Purpose

Ripple allows users to safely test hypothetical policies before they’re implemented in the real world.  
By simulating the “ripple effects” of economic changes across thousands of scenarios, it provides insights into income distribution, inequality, employment, and housing outcomes.

---

## 🧩 Features

- 🧮 **Monte Carlo Simulation Engine** – Runs thousands of randomized simulations to capture uncertainty.  
- 🧠 **Gemini AI Summaries** – Explains complex results in plain English.  
- 💾 **Synthetic Population Dataset** – Models realistic demographics (50k synthetic records).  
- ⚡ **Interactive React Frontend** – Adjust policy parameters and visualize outcomes live.  
- 📊 **Dynamic Visuals** – Real-time graphs for metrics such as median income, Gini coefficient, and employment rate.  

---

## 🧠 Example Policy Scenario

**Input:**
```json
{
  "min_wage": 18.0,
  "tax_rate": 0.25,
  "rent_subsidy": 0.1
}
