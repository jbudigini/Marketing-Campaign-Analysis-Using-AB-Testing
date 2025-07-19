# 📊 Marketing Campaign Performance Analysis: Facebook vs. AdWords

## Project Overview
This project involves conducting A/B testing to evaluate the performance of two marketing campaigns: Facebook Ads and Google Adwords for an online retail business. The primary goal is to determine which campaign is more effective in driving user engagement and conversions, helping the company optimize its marketing strategies.

A/B testing is a methodology used to experiment and compare two versions of a marketing approach to identify the better performing option based on metrics such as conversion rate, click-through rate, and overall revenue.

## 🧩 Problem Statement
As a marketing agency, our objective is to maximize the return on investment (ROI) for advertising campaigns. This project analyzes two major platforms **Facebook Ads** and **AdWords** to determine which one delivers better results in terms of **clicks**, **conversions**, and **cost-effectiveness**. 

---

## 🗂️ Dataset Overview
- Data collected daily over the year 2020 (365 rows)
- Two ad campaigns: Facebook and AdWords
- Key features include:
  - `Ad Views`, `Ad Clicks`, `Ad Conversions`
  - `Cost per Ad`, `CTR`, `Conversion Rate`, `CPC`
  - Campaign dates and time-based trends

---

## 🛠️ Tools and Technologies 
- **Python**: For data analysis and hypothesis testing.
- **Pandas**: Used for data manipulation.
- **SciPy**: For conducting statistical hypothesis tests.
- **Matplotlib/Seaborn**: For data visualization.
- **Jupyter Notebook**: For developing and presenting the analysis.
- **Statistical tests**: t-test, cointegration


---

## 🔍 Analytical Approach

**1. Data Cleaning**: Preparing the dataset by handling missing values and formatting inconsistencies.

**2. Exploratory Data Analysis (EDA)**: 
- Visualizing user behavior and campaign performance.
- Comparing the conversion rates and click-through rates across Facebook Ads and Google Adwords.

**3. Hypothesis Testing**:
- **Null Hypothesis (H0)**: Facebook Ads and Google Adwords perform equally.
- **Alternative Hypothesis (H1)**: One campaign performs better than the other.
- Perform statistical tests (e.g., t-tests) to assess the significance of any performance differences between the campaigns.

**4. Conclusion**: Identify which campaign is more effective based on statistical evidence.

---

## 📑 Key Findings

**Conversion Performance:**  
- Facebook Ads generated a significantly higher number of conversions compared to AdWords.  
- Hypothesis testing confirmed this difference is statistically significant (p-value ≪ 0.05).  
- Facebook consistently delivered high-conversion days (10–15+ conversions), while AdWords conversions remained mostly below 10.

**Cost Efficiency:**  
- Facebook had a lower average cost per conversion across multiple months.  
- May and November were the most cost-effective months, while February and March had the highest CPC.

**User Engagement:**  
- Facebook Ads showed a strong correlation (r = 0.83) between clicks and conversions, indicating reliable conversion performance as engagement increases.  
- AdWords showed only a moderate correlation (r = 0.45), suggesting other factors may affect its conversion outcomes.

**Long-Term Impact:**  
- Cointegration analysis confirmed a long-term equilibrium relationship between Facebook ad cost and conversions, indicating that changes in ad spend have a stable, proportional effect on conversion volume over time.

---




