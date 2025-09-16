# rat-bat
# 🦇 Bat vs 🐀 Rat Data Analysis Project

## 📌 Overview
This project analyzes the interaction between **Egyptian Fruit Bats (Rousettus aegyptiacus)** and **Black Rats (Rattus rattus)**.  
The goal is to investigate whether rat presence influences bat risk-taking behavior, and whether seasonality affects bat foraging.

The analysis was completed using **Python** (pandas, matplotlib, seaborn, statsmodels, scipy) in Google Colab.

---

## 📊 Datasets
- **Bats Dataset (dataset1.csv)**: Contains information about bat landings, risk-taking, rewards, timing, and seasonal variables. (907 rows × 12 columns)
- **Rats Dataset (dataset2.csv)**: Contains information about rat arrivals, food availability, and interactions with bats. (2123 rows × 7 columns)

---

## ⚙️ Methods & Analysis
1. **Data Preprocessing**
   - Missing values handled with forward fill.
   - Time columns converted to datetime.
   - Basic descriptive statistics and correlations.

2. **Visualization**
   - Risk-taking distribution among bats.
   - Relationship between risk and reward.
   - Seasonal trends in bat landings.
   - Scatter plots: Rat minutes vs. food availability, Bat vs. Rat arrivals.

3. **Statistical Tests**
   - **T-test**: Risk-taking with vs. without rat presence.
   - **Chi-square Test**: Risk vs. Reward association.
   - **ANOVA**: Seasonal effects on bat risk-taking.

---

## ✅ Key Findings
- **Rat Presence**: No significant difference in bat risk-taking (p = 0.828).
- **Risk vs Reward**: Strong significant association (p < 0.001).
- **Seasonal Effects**: No significant seasonal variation (p = 0.067).

---

