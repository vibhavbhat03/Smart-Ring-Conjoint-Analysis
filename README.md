Here’s a **comprehensive GitHub README** for your *Smart Ring Conjoint Analysis* project — it’s structured and professional enough for your portfolio:

---

# 🧠 Smart Ring Conjoint Analysis — Market Segmentation & Product Design Insights

### 📊 Choice-Based Conjoint Study using Sawtooth

---

## 📘 Project Overview

This project aims to identify the **optimal product configuration and pricing strategy** for a next-generation **Smart Ring** using a **Choice-Based Conjoint (CBC)** analysis.
We collected preference data from **99 respondents** and estimated **part-worth utilities** for key product attributes.
The insights guided strategic recommendations for a **Base + Pro dual-product launch**, projected to capture **58.1% market share** and **$140.8M in annual revenue**.

---

## 🎯 Objectives

* Quantify **customer preferences** for Smart Ring features (Brand, Price, Battery Life, and Functional Features).
* Determine **attribute-level utilities** and **relative importance weights**.
* Segment the market using **latent class clustering**.
* Simulate **share-of-preference** and **revenue optimization scenarios**.
* Provide actionable product design and pricing recommendations.

---

## 🧩 Methodology

### 1. **Attribute and Level Selection**

| Attribute    | Levels                                                                   |
| ------------ | ------------------------------------------------------------------------ |
| Brand        | Oura, Samsung, Apple, Fitbit                                             |
| Price        | $199, $249, $299, $349                                                   |
| Battery Life | 3 Days, 7 Days, 10 Days                                                  |
| Features     | Basic Health, Fitness & Sleep, Full Suite (Health+Fitness+Notifications) |

---

### 2. **Experimental Design**

* **Choice-Based Conjoint (CBC)** design using *Sawtooth Lighthouse Studio*.
* **12 tasks per respondent**, each with 3 product concepts + “None” option.
* **Balanced & Orthogonal design** ensuring statistical efficiency.

---

### 3. **Model Estimation**

* Used **Hierarchical Bayes (HB)** estimation for part-worth utility derivation.
* Utilities were zero-centered within attributes.
* Calculated **relative importance** of each attribute:

  * Brand: 32%
  * Features: 29%
  * Price: 25%
  * Battery Life: 14%

---

### 4. **Market Segmentation**

* **Latent Class Analysis (LCA)** identified two primary segments:

  * **Segment 1 (Value Seekers):** Price-sensitive, favor Fitbit/Oura.
  * **Segment 2 (Premium Seekers):** Brand-driven, favor Apple/Samsung and longer battery life.

---

### 5. **Market Simulation**

* Conducted **Share-of-Preference simulations** under multiple product mix scenarios.
* Modeled **revenue outcomes** at varying price points.
* Recommended **two-tier strategy** (Base + Pro versions) for optimal coverage:

  * **Base Model:** Fitbit @ $199
  * **Pro Model:** Apple @ $349
* Result: **58.1% projected market share** and **~$140.8M annualized revenue potential**.

---

## 🧮 Key Technical Details

| Technique                              | Description                                                                                       |
| -------------------------------------- | ------------------------------------------------------------------------------------------------- |
| **Choice-Based Conjoint (CBC)**        | Simulates real-world purchase trade-offs by asking respondents to choose between product bundles. |
| **Hierarchical Bayes (HB) Estimation** | Used to estimate part-worth utilities at individual level from choice data.                       |
| **Latent Class Segmentation**          | Unsupervised clustering to uncover hidden preference heterogeneity.                               |
| **Market Simulation**                  | Translates utilities into predicted choice shares and revenue projections.                        |

---

## 🧰 Tools & Technologies

* **Sawtooth Lighthouse Studio** – Experimental design, survey deployment, HB estimation
* **R / Python (Pandas, Matplotlib, NumPy)** – Post-estimation analytics, visualization
* **Excel / Tableau** – Interactive dashboards for share-of-preference and revenue modeling

---

## 📈 Key Insights

* **Brand** and **Features** were most influential attributes.
* **Apple** and **Samsung** led among premium segments; **Fitbit** dominated the value-conscious group.
* Optimal **two-product strategy** (Base + Pro) captured both market ends, improving total projected share by **23%** over single-product offering.

---

## 💡 Recommendations

1. **Launch dual-tier models**: “Base” for mass market and “Pro” for tech-savvy consumers.
2. **Price sweet spot** identified between **$249–$299** to balance margin and adoption.
3. **Prioritize feature differentiation** — integrating advanced health metrics provides high marginal utility.
4. **Focus marketing on battery life + ecosystem compatibility** for brand premium.

---



## 📚 References

* *Orme, B. (2019). Getting Started with Conjoint Analysis, 4th Edition.*
* *Sawtooth Software Technical Paper: CBC/HB v5 – Technical Details.*
* *Green, P. E., & Srinivasan, V. (1990). Conjoint Analysis in Marketing: New Developments and Directions.*

---

## 🏁 Outcome

> Built a robust data-driven framework for Smart Ring product design and pricing strategy using advanced conjoint analytics — achieving a **data-backed, actionable market plan** for a potential $140M+ opportunity.


