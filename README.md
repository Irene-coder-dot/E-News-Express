# E-News Express A/B Testing Analysis
<img width="550" height="180" alt="e-news image" src="https://github.com/user-attachments/assets/bcde9cdb-3979-4c85-94e2-4bb7a082d803" />

## Project Overview

E-News Express, an online news platform, developed a new landing page to improve user engagement and increase subscription conversions. This project analyzes the effectiveness of the new landing page using Exploratory Data Analysis (EDA) and statistical hypothesis testing.

The objective is to determine whether the new landing page performs better than the old page in terms of:

- User engagement (time spent on page)
- Subscription conversion rate
- Performance across different language groups

---

## Business Problem

The company observed declining engagement and subscription rates on its existing landing page. To address this issue, a redesigned landing page was introduced and evaluated through an A/B test.

Key questions investigated:

1. Do users spend more time on the new landing page than on the old page?
2. Does the new landing page lead to higher subscription conversion rates?
3. Is conversion dependent on user language preference?
4. Does time spent on the new landing page differ across language groups?

---

## Dataset Description

The dataset contains information collected from an A/B test, including:

- **Landing Page Version** (Old/New)
- **Time Spent on Page** (minutes)
- **Converted** (Yes/No)
- **Language Preference** (English, French, Spanish)

---

## Tools and Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Statsmodels

---

## Methodology

### 1. Exploratory Data Analysis (EDA)

- Univariate analysis
- Bivariate analysis
- Distribution visualization
- Boxplots and comparative visualizations

### 2. Statistical Hypothesis Testing

The following tests were performed:

| Business Question | Statistical Test |
|------------------|-----------------|
| Difference in time spent between old and new pages | Independent Two-Sample t-Test |
| Difference in conversion rates | Two-Proportion Z-Test |
| Association between language and conversion | Chi-Square Test of Independence |
| Difference in engagement across language groups | One-Way ANOVA |

---

## Key Findings

### User Engagement

Users spent significantly more time on the **new landing page** compared to the old page.

- **p-value = 0.0001**
- Result: Statistically significant increase in engagement.

### Conversion Rate

The new landing page achieved a significantly higher subscription conversion rate.

- **p-value = 0.0080**
- Result: Statistically significant improvement in conversions.

### Language vs Conversion

No significant relationship was found between language preference and subscription conversion.

- **p-value = 0.213**
- Result: Conversion behavior is similar across language groups.

### Language vs Time Spent

No significant difference was found in average time spent among English, French, and Spanish users on the new landing page.

- **p-value = 0.4320**
- Result: Engagement performance is consistent across languages.

---

## Conclusion

The statistical analysis demonstrates that the **new landing page outperforms the old landing page** in both user engagement and conversion rate.

Additionally:

- Language preference does not significantly influence conversion.
- User engagement remains consistent across language groups.
- The new page performs effectively for all users regardless of language.

---

## Business Recommendations

- Adopt the **new landing page** as the default version.
- Roll out the new page across all traffic channels.
- Continue monitoring performance metrics after deployment.
- Focus future optimization efforts on:
  - Call-to-action (CTA) placement
  - Headlines and messaging
  - Subscription prompts
- Continue A/B testing to validate long-term performance improvements.

---

## Repository Structure

```
├── data/
│   └── abtest.csv
├── notebooks/
│   └── ENews_Express_Learner_Notebook.ipynb
├── images/
│   └── visualizations
├── README.md
```

---

## Project Outcome

The analysis provides strong statistical evidence that the redesigned landing page improves both engagement and subscription conversions, making it a valuable business decision for E-News Express.

---

### Connect With Me

🔗 LinkedIn: https://www.linkedin.com/in/irene-kibengo-44964356/
