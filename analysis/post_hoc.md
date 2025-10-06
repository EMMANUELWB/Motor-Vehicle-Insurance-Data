# Post-Hoc Analysis (Tukey-style summary)

Group averages used (from ANOVA summary):

|                  Group |     Mean |    n |
| ---------------------: | -------: | ---: |
|       Premium_Low_Risk | 141.9833 | 5085 |
|    Premium_Medium_Risk | 309.1583 | 5085 |
|      Premium_High_Risk | 323.2647 | 5085 |
| Premium_Very_High_Risk |  79.2773 |  696 |

**ANOVA within-group MS:** 12,340.32359 (df = 15,947)

# Post Hoc Analysis (Pairwise Comparisons)

This section reports the results of pairwise comparisons between the different groups (Low, Medium, High, Very High). For each comparison, we present the mean difference, standard error (SE), t statistic, p value, and 95% confidence interval (CI).

## Results Table

| Comparison          | Mean Difference |   SE |      t | p value | 95% CI (Lower) | 95% CI (Upper) |
| ------------------- | --------------: | ---: | -----: | ------: | -------------: | -------------: |
| High vs Low         |          181.28 | 2.20 |  82.28 | < 0.001 |         176.97 |         185.60 |
| High vs Medium      |           14.11 | 2.20 |   6.40 | < 0.001 |           9.79 |          18.42 |
| High vs Very High   |          243.99 | 4.49 |  54.34 | < 0.001 |         235.19 |         252.78 |
| Low vs Medium       |         -167.18 | 2.20 | -75.88 | < 0.001 |        -171.49 |        -162.57 |
| Low vs Very High    |           62.71 | 4.49 |  13.97 | < 0.001 |          53.91 |          71.51 |
| Medium vs Very High |          229.88 | 4.49 |  51.20 | < 0.001 |         221.08 |         238.68 |

---

## Interpretation

* All pairwise comparisons are statistically significant (*p* < 0.001).

* **High vs Low**: Customers in the High-Risk group pay on average 181.28 currency units more than those in the Low-Risk group, showing a substantial premium increase with risk.
* **High vs Medium**: High-Risk customers pay 14.11 units more than Medium-Risk customers. This is a smaller, but still statistically significant, difference.
* **High vs Very High**: Very High-Risk customers pay 243.99 units more than High-Risk customers, representing the largest incremental premium between adjacent risk categories.
* **Low vs Medium**: Medium-Risk customers pay 167.18 units more than Low-Risk customers.
* **Low vs Very High**: Very High-Risk customers pay 62.71 units more than Low-Risk customers.
* **Medium vs Very High**: Very High-Risk customers pay 229.88 units more than Medium-Risk customers.

### Overall Takeaway
Premiums increase consistently with policyholder risk level: Low → Medium → High → Very High.

The results strongly support that risk classification is closely associated with the amount customers pay, with the largest differences observed when comparing Very High-Risk customers to all other groups.

---

