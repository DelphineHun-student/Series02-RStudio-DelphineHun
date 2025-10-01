# README – Series02 Analysis

## 1. Introduction
This project explores the effect of treatment and lifestyle factors on health-related variables, using datasets provided in the course.  
The goal was to practice basic statistical analysis: from descriptive statistics to hypothesis testing, and to report results in a scientific style.

---

## 2. Dataset
- Files used: `NonUse.csv`, `PrePost.csv`,  `snore.txt`  
- Main variables:  
  - Anthropometric data (e.g., weight, sex)  
  - Lifestyle factors (smoking, drinking)  
  - Clinical/experimental outcomes (snoring status, performance before/after)

---

## 3. Descriptive Statistics
- Computed **mean, median, variance, standard deviation**.  
- Tested **normality** using the Shapiro–Wilk test.  
- Produced summary tables and visualizations (boxplots, histograms, QQ-plots).

---

## 4. Statistical Testing
### a) Turn-taking dataset (PANU, SANU, EENU)
- Spearman correlations to assess associations.  
- Linear regressions with regression equations reported (e.g., PANU ~ SANU).  

### b) Snoring dataset
- Tested stereotypes such as:  
  - *Are snorers fatter?* → Wilcoxon test (weight ~ snorer).  
  - *Do women smoke less?* → Chi-square (smoking ~ sex). 
  - ...
- Visualizations: boxplots and barplots

### c) Treatment dataset (Before vs After)
- Normality of differences tested with **Shapiro–Wilk**.  
- Applied **paired t-test** (if normal), **Wilcoxon signed-rank test** or **Chi-square**.  
- Visualized effect with boxplots and line plots.

---

## 5. Results Reporting
- Results expressed with clear sentences, e.g.:  
  *“A paired t-test revealed that performance was significantly higher after treatment compared to before (t(7) = –5.40, p = 0.001).”*  
- Non-significant results explicitly reported, e.g.:  
  *“No significant difference in weight was found between snorers and non-snorers (p > 0.05).”*

---
## 6. References

- https://www.khanacademy.org/math/statistics-probability/summarizing-quantitative-data
- https://www.statisticshowto.com/probability-and-statistics/statistics-definitions/variance/
- https://www.khanacademy.org/math/statistics-probability/modeling-distributions-of-data
- https://en.wikipedia.org/wiki/Statistical_hypothesis_testing
- https://www.scribbr.com/statistics/statistical-tests
- https://www.scribbr.com/frequently-asked-questions/assumptions-of-statistical-tests/
- https://www.scribbr.com/statistics/nonparametric-tests/
- https://www.scribbr.com/statistics/p-value/
- https://www.scribbr.com/statistics/type-i-and-type-ii-errors/
- https://www.scribbr.com/statistics/paired-t-test-vs-unpaired-t-test/
- https://statistics.laerd.com/spss-tutorials/testing-for-normality-using-spss-statistics.php
