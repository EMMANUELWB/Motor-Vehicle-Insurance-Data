# ANOVA: Single Factor
## Summary

| Groups                | Count | Sum     | Average      | Variance      |
|-----------------------|-------|---------|--------------|---------------|
| Premium_Low_Risk      | 5085  | 721985  | 141.9832842  | 5011.102199   |
| Premium_Medium_Risk   | 5085  | 1572070 | 309.1583088  | 11714.67458   |
| Premium_High_Risk     | 5085  | 1643801 | 323.2647001  | 21954.20136   |
| Premium_Very_High_Risk| 696   | 55177   | 79.27729885  | 204.5057285   |

## ANOVA

| Source of Variation | SS          | df    | MS           | F           | P-value | F crit       |
|---------------------|-------------|-------|--------------|-------------|---------|--------------|
| Between Groups      | 124704674.9 | 3     | 41568224.98  | 3368.487436 | 0       | 2.605465959  |
| Within Groups       | 196791140.3 | 15947 | 12340.32359  |             |         |              |
| Total               | 321495815.3 | 15950 |              |             |         |              |

Interpretation
The F statistic (3368.49) is much larger than the F critical value (2.61).
The p-value = 0, which is less than 0.05.
Therefore, we reject the null hypothesis.

This means there is a statistically significant difference between the average premiums across the different risk levels (Low, Medium, High, Very High).
