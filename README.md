# Marketing A/B Testing Analysis – Ad Campaign Effectiveness

## Project Overview
This project analyzes the effectiveness of a digital advertising campaign using A/B testing. The goal is to determine whether showing users ads leads to higher conversion rates compared to a public service announcement (PSA).

Using Python and statistical hypothesis testing, the analysis evaluates user behavior and determines whether the difference in conversion rates is statistically significant.

---

## Business Problem
Marketing teams frequently test advertising strategies to determine which campaigns drive better customer conversions.

This analysis answers:

- Do ads increase user conversions?
- Is the difference statistically significant?
- What insights can improve future marketing strategies?

---

## Dataset
The dataset contains user-level marketing campaign data with the following variables:

- user_id – unique user identifier  
- test_group – Ad group or PSA (control group)  
- converted – whether the user converted (1) or not (0)  
- total_ads – total number of ads seen  
- most_ads_day – day with highest ad exposure  
- most_ads_hour – hour with highest ad exposure  

---

## Tools & Technologies
- Python
- Pandas
- Matplotlib
- Seaborn
- Hypothesis Testing
- Jupyter Notebook

---

## Key Analysis
The project includes:

- Conversion rate comparison between ad and control groups
- Visualization of ad exposure patterns
- Conversion analysis by day and hour
- Chi-square statistical test for significance

---

## Results

Conversion Rate:

Ad Group: **2.55%**  
PSA Group: **1.79%**

Lift in Conversion Rate: **43.09%**

Statistical Test:

Chi-Square Statistic: **54.01**  
p-value: **< 0.001**

---

## Key Findings
- Users exposed to ads converted at a significantly higher rate than users in the PSA group.
- The ad campaign produced a **43% increase in conversions**.
- Statistical testing confirms the difference is **highly significant**.
- The advertising strategy meaningfully improves user conversion.

---

## Conclusion
This analysis demonstrates how A/B testing helps marketing teams make data-driven decisions when evaluating advertising strategies. The results suggest that deploying the ad campaign can significantly improve conversion performance.

---

## Repository Structure

Marketing-A-B-Testing-Analysis-Ad-Campaign-Effectiveness

│  
├── Marketing_A_B_Testing.ipynb  
├── marketing_AB.csv  

├── images  
│   ├── charts
