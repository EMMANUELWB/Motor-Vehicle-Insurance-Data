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
* **High vs Low**: The High group scores on average **181.28 units higher** than the Low group, with a very narrow confidence interval, indicating a robust effect.
* **High vs Medium**: The High group is **14.11 units higher** than Medium, also significant, but this is the smallest effect size among the comparisons.
* **High vs Very High**: The Very High group clearly outperforms the High group by **243.99 units**, showing the strongest difference overall.
* **Low vs Medium**: Medium is significantly higher than Low (mean difference of **167.18 units**).
* **Low vs Very High**: The Very High group is **62.71 units higher** than Low, a sizable and significant difference.
* **Medium vs Very High**: Very High exceeds Medium by **229.88 units**, confirming a substantial gap.

### Overall Takeaway

The post hoc results reveal a **consistent, graded pattern** across groups:

* As the category moves from **Low → Medium → High → Very High**, the outcome measure increases steadily and significantly.
* These findings support the conclusion that **group level is strongly associated with the outcome**, with especially large contrasts between the Very High group and all others.

---

