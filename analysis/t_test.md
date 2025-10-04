# T-Test Analysis

We compared drivers with subscriptions (Premium_Channel_1) against drivers without subscriptions (Premium_Channel_0).

## Summary of Results
- Mean (with sub): ≈ 330  
- Mean (without sub): ≈ 304  
- t-statistic: 29.64 (≫ 1.96 critical value)  
- p-value: ≈ 0  

**Interpretation:**  
There is a statistically significant difference between the two groups. Subscription status is strongly associated with the metric being tested.

---

## Full T-Test Results (Embedded)

| Metric                     | Value           |
|----------------------------|-----------------|
| Mean (with sub)            | 330.141579      |
| Mean (without sub)         | 304.271452      |
| Variance (with sub)        | 20884.14619     |
| Variance (without sub)     | 18713.42646     |
| Observations (with sub)    | 47,613          |
| Observations (without sub) | 57,874          |
| Hypothesized Mean Diff.    | 0               |
| df                         | 99,292          |
| t Stat                     | 29.63667544     |
| P(T<=t) one-tail           | 1.74E-192       |
| t Critical one-tail        | 1.644868973     |
| P(T<=t) two-tail           | 3.49E-192       |
| t Critical two-tail        | 1.959987877     |
