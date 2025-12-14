# 🚢 Titanic Survival & Economic Risk Analysis

> **Project Highlight:** An inflation-adjusted analysis revealing that the "Fare" variable was a high-fidelity proxy for extreme wealth stratification ($50,000+ per suite).

---

### 💰 The "Money Shot": Economic Context & Inflation
*While most Titanic analyses treat `Fare` as a standard numerical feature, I hypothesized that it represented a distinct socio-economic barrier.*

I implemented a custom inflation adjustment (CPI Factor ~32x) to map 1912 ticket prices to **2024 purchasing power**.

#### 💡 Key Findings:
1. **The $50,000 Ticket:** The most expensive 1st Class suite cost the equivalent of **$50,000+ USD** today. This aligns perfectly with modern ultra-luxury cruise pricing.
2. **Wealth = Survival:** The model confirmed that `Fare` was not just a continuous variable but a strict proxy for **VIP Rescue Priority**. The survival rate didn't just scale linearly; it spiked at the "Ultra-Wealthy" threshold.

*(See the **Economic Context** section in the notebook for the full calculation and inflation logic.)*

---

### 📄 Executive Summary
**Goal:** To build a classification model to predict passenger survival, while using domain research (economic history) to validate feature importance.
**Result:** Identified the **"Wealth Advantage"**, a distinct negative correlation between Pclass and Survival. Passengers in **1st Class** had the highest probability of survival, while those in **3rd Class** faced the highest risk.

---

### 📊 Exploratory Data Analysis (EDA) Insights
Beyond the economic context, the data revealed:
* **Survival Imbalance:** The tragedy resulted in significantly more non-survivors, creating an imbalanced dataset for modeling.
* **Age & Class Correlation:** 1st Class passengers were generally older, whereas 3rd Class contained more young adults and families.
* **Family Size:** Solo travelers had a lower survival rate compared to those traveling with small families (size 2-4).

---

### 🛠️ Technical Implementation
* **Language:** Python 3
* **Libraries:** Pandas, Seaborn, Matplotlib, Scikit-Learn
* **Key Techniques:**
    * **Feature Engineering:** Inflation adjustment, Family Size grouping, Title extraction.
    * **Imputation:** Handling missing 'Age' values based on Pclass medians.
    * **Visualization:** Log-scaled fare distributions and correlation heatmaps.

---

### 📂 Project Structure
* [**Titanic_Visualization-GazaliAhmad.ipynb**](./Titanic_Visualization-GazaliAhmad.ipynb): The complete analysis notebook, including the inflation logic and final conclusions.

---

### 👤 Author
**Gazali Ahmad**
*Data Analyst | Systems Analyst Background*
[LinkedIn Profile](https://www.linkedin.com/in/gazaliahmad)
