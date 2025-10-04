# T-Test Analysis

We compared drivers with subscriptions (Premium_Channel_1) against drivers without subscriptions (Premium_Channel_0).

## Summary of Results
- Mean (with sub): ≈ 330  
- Mean (without sub): ≈ 304  
- t-statistic: 29.64 (≫ 1.96 critical value)  
- p-value: ≈ 0  

**Interpretation:**  
The mean premium for drivers with subscriptions is **statistically significantly higher** than for those without (p ≪ 0.001). However, the standardized effect (Cohen's d ≈ 0.18) is **small**, meaning the practical difference while consistent and repeatable given huge sample sizes is modest (~$26 difference on average). This suggests subscription status correlates with higher premiums, but it may not be a strong standalone driver of premium magnitude; consider controlling for confounders (vehicle value, risk type, age, channel) in follow-up models.

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
