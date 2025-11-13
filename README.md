# A/B Testing Analysis: Marketing Campaign Performance (Python + Bayesian Modeling + Power BI)

This project evaluates the effectiveness of a new marketing campaign strategy ("Test") against the existing strategy ("Control") using Python, Frequentist hypothesis testing, Bayesian A/B testing, and a fully interactive Power BI dashboard.

The goal was to determine whether the Test campaign delivered better conversion performance and higher ROI, and whether it should be deployed at scale.

---

### 📌 Project Summary

I performed a full end-to-end analysis covering:

1. Data cleaning and feature engineering

2. Frequentist hypothesis testing (t-tests for continuous metrics)

3. Bayesian A/B testing using a Student-t model for conversion rates

4. Probability simulation of Test outperforming Control

5. Performance funnel analysis: Cost efficiency metrics (CPC, CPA, CTR, CVR)

6. Executive dashboard with side-by-side comparisons

---

### Final Conclusion:
The Test campaign has only ~7% probability of outperforming Control in conversion rate, despite spending 15% more.
It is not commercially viable, and the company should continue using the Control strategy until a redesigned Test is launched.

---

### 📊 Tools & Techniques Used
#### Python

1. Pandas for data wrangling

2. NumPy for numerical operations

3. SciPy for hypothesis testing

4. custom code for Bayesian simulation

5. Matplotlib for visualizations


   <img width="900" height="700" alt="python" src="https://github.com/user-attachments/assets/438ff202-6a5a-4fb0-b4c3-8943ae4d2668" />


#### Statistical modeling:

1. Frequentist t-tests

2. Bayesian Student-t model for continuous conversion rates

3. Posterior probability simulation

<img width="900" height="700" alt="python2" src="https://github.com/user-attachments/assets/d92fcc69-b924-48e4-8ebb-c9fd7da98268" />


#### Power BI

1. KPI cards (CPA, CTR, CPC, Purchases, Impressions, Conversion Rate)

2. Funnel visualization (Impressions → Purchases)

3. Spend comparison chart

4. Lift % analysis

5. Test vs Control dashboards for executives

<img width="1000" height="800" alt="power_bi2" src="https://github.com/user-attachments/assets/e585362c-e390-4348-aed3-236faa6a9b66" />


---

### 📈 Key Findings

1. Test spent 15% more than Control

2. Test CPA worse by ~11%

3. Conversion rate –12% lower in Test

4. Bayesian posterior simulation shows only 7% probability that Test would outperform Control

5. Test produced more clicks but fewer purchases → lower quality traffic

6. Control campaign is more cost-efficient and delivers better ROI

---

### 📌 Business Impact

This project demonstrates how statistical rigor prevents poor marketing investment decisions. The insights help the business:

1. Avoid scaling an underperforming strategy

2. Protect ROI by identifying spend inefficiency

3. Understand funnel drop-offs clearly

4. Make decisions based on probability, not guesswork
