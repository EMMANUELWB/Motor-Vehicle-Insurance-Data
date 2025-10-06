# Chi-Square Test Analysis

Tested the relationship between **risk categories** and a **Yes/No outcome** (**Second_driver**).

---

## Full Chi-Square Table


| Type_Risk | No | Yes | Grand_Total | Expected_Value_No | Expected_Value_Yes | Difference_No | Difference_Yes | Contributions_No | Contributions_Yes |  
|-----------|----|-----|-------------|-------------------|--------------------|---------------|----------------|------------------|-------------------|  
| High      | 70656 | 12282 | 82938 | 72679.15271 | 10258.84729 | -2023.152711 | 2023.152711 | 1818.798669 | 50190.67944 |  
| Low       | 8496 | 1 | 8497 | 7445.98086 | 1051.01914 | 1050.01914 | -1050.01914 | 0.000117689 | 7443.980995 |  
| Medium    | 12437 | 765 | 13202 | 11569.00545 | 1632.994549 | 867.9945491 | -867.9945491 | 44.32851083 | 10089.59104 |  
| Very High | 850 | 0 | 850 | 744.8609781 | 105.1390219 | 105.1390219 | -105.1390219 | 0 | 744.8609781 |  
| **Total** | **92439** | **13048** | **105487** |  |  |  |  | **1863.127297** | **68469.11245** |  




---

## Test Results

* **Chi-Square statistic (χ²):** 70,332.24
* **Degrees of freedom (df):** 4
* **p-value:** ≈ 0 (from `=CHISQ.DIST.RT(70332.24, 4)`)

---

## Interpretation

There is a highly significant association between policyholder risk level and the presence of a second driver on the policy. The probability of observing this pattern by chance is essentially zero, strongly rejecting the null hypothesis of independence.

* High-Risk and Very High-Risk policyholders show the largest contributions to the association, suggesting that these groups are more likely to have a second driver (or contribute disproportionately to the chi-square statistic due to low or high counts).

* Lower-risk categories (Low and Medium) show fewer second drivers than expected under independence.

## Why This Matters

* The presence of a second driver is not evenly distributed across risk levels.

* Risk level is strongly tied to the likelihood of having a second driver, which can inform policy pricing, underwriting, and risk assessment strategies.

* Understanding this relationship helps the insurer identify patterns in coverage and potential risk exposure.
