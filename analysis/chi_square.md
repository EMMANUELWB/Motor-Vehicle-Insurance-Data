# Chi-Square Test Analysis

We tested the relationship between **risk categories** and a **Yes/No outcome** (e.g., claims or subscriptions).

---

## Full Chi-Square Table


| Type_Risk | No | Yes | Grand_Total | Expected_Value_No | Expected_Value_Yes | Difference_No | Difference_Yes | Contributions_No | Contributions_Yes |  
|-----------|----|-----|-------------|-------------------|--------------------|---------------|----------------|------------------|-------------------|  
| High      | 70656 | 12282 | 82938 | 72679.15271 | 10258.84729 | -2023.152711 | 2023.152711 | 1818.798669 | 50190.67944 |  
| Low       | 8496 | 1 | 8497 | 7445.98086 | 1051.01914 | 1050.01914 | -1050.01914 | 0.000117689 | 7443.980995 |  
| Medium    | 12437 | 765 | 13202 | 11569.00545 | 1632.994549 | 867.9945491 | -867.9945491 | 44.32851083 | 10089.59104 |  
| Very High | 850 | 0 | 850 | 744.8609781 | 105.1390219 | 105.1390219 | -105.1390219 | 0 | 744.8609781 |  
| **Total** | **92439** | **13048** | **105487** |  |  |  |  |  | **68469.11245** |  



---

## Test Results

* **Chi-Square statistic (χ²):** 70,332.24
* **Degrees of freedom (df):** 4
* **p-value:** ≈ 0 (from `=CHISQ.DIST.RT(70332.24, 4)`)

---

## Interpretation

There is a **highly significant association** between the categorical variables analyzed. The probability of observing this result by chance is effectively zero, which strongly rejects the null hypothesis of independence.
