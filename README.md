# 📊 Advertising Campaign Performance Analysis: Facebook vs. AdWords

## 🧩 Problem Statement
As a marketing agency, our objective is to maximize the return on investment (ROI) for advertising campaigns. This project analyzes two major platforms—**Facebook** and **AdWords**—to determine which one delivers better results in terms of **clicks**, **conversions**, and **cost-effectiveness**. 

By identifying the stronger performer, we can guide more efficient ad spend and improve future campaign strategies.

---

## 🎯 Research Question
Which ad platform—Facebook or AdWords—is more effective in generating conversions, achieving better click-through rates, and maintaining a lower cost per conversion over time?

---

## 🗂️ Dataset Overview
- Data collected daily over the year 2020 (365 rows)
- Two ad campaigns: Facebook and AdWords
- Key features include:
  - `Ad Views`, `Ad Clicks`, `Ad Conversions`
  - `Cost per Ad`, `CTR`, `Conversion Rate`, `CPC`
  - Campaign dates and time-based trends

---

## 🛠️ Technologies Used
- **Python** (Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn, Statsmodels)
- **Jupyter Notebook**
- **Statistical tests**: t-test, cointegration
- **Regression analysis**: LinearRegression (scikit-learn)

---

## 🔍 Key Steps & Analysis

### 1. Data Preprocessing
- Converted monetary and percentage fields from string to float
- Extracted `month` and `weekday` from the `Date` column
- Calculated cost per conversion for both platforms

### 2. Exploratory Data Analysis (EDA)
- Compared distributions of clicks and conversions for each platform
- Created grouped bar charts to visualize frequency of low vs. high conversion days
- Analyzed weekly and monthly conversion patterns

### 3. Statistical Analysis
- **Correlation**:
  - Facebook: r = 0.83 (strong positive correlation between clicks and conversions)
  - AdWords: r = 0.45 (moderate correlation)

- **Hypothesis Testing**:
  - Mean conversions: Facebook = 11.72, AdWords = 6.02
  - p-value = 4.04e-124 → Statistically significant difference
  - Conclusion: Facebook generates significantly more conversions

- **Regression Analysis**:
  - R² score = 69.59%
  - MSE = 2.87
  - Predictive model estimates conversions based on click volume

- **Trend Analysis**:
  - Highest conversions on mid-week days (Tue, Wed, Thu)
  - Best-performing months: October and December
  - Lowest CPC observed in May and November

- **Cointegration Test**:
  - p-value = 2.06e-26 → Long-term equilibrium between ad cost and conversions
  - Suggests ad budget changes proportionally impact conversions over time

---

## ✅ Key Insights
- **Facebook outperforms AdWords** in both conversion volume and efficiency.
- **Clicks on Facebook ads are highly predictive** of conversions.
- **Midweek and end-of-year periods** are optimal for campaign launches.
- **May and November** offer the best ROI based on cost-per-conversion trends.
- Strong evidence of a **long-term relationship** between ad spend and conversions.

---

## 📂 Folder Structure

