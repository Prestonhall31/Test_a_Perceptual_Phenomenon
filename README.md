# Statistics: The Science of Decisions Project

## Introduction

This project involves analyzing a dataset related to the Stroop effect, a psychological phenomenon that explores the interference in the reaction time of a task. In this analysis, we aim to answer questions about the Stroop effect, perform statistical tests, and draw conclusions based on the dataset.

## Questions and Hypotheses

**Question 1**: What is our independent variable? What is our dependent variable?

- Independent Variable: Congruent or Incongruent condition.
- Dependent Variable: Time to complete the test.

**Question 2**: What is an appropriate set of hypotheses for this task? What kind of statistical test do you expect to perform? Justify your choices.

- Null Hypothesis (H0): The Stroop effect does not exist, meaning there is no difference between congruent and incongruent conditions.
- Alternative Hypothesis (H1): There is a Stroop effect, and the mean difference between the time required to read the two lists is greater than zero.

I will perform a two-tailed t-test for this dataset to compare the means of the two groups and determine if there is a statistically significant difference.

## Descriptive Statistics

I have performed basic descriptive statistics on the dataset:

- Sample Size: 24 for both Congruent and Incongruent conditions.
- Mean Response Time: 14.05 seconds (Congruent) and 22.02 seconds (Incongruent).
- Median Response Time: 14.36 seconds (Congruent) and 21.02 seconds (Incongruent).
- Standard Deviation: 3.56 seconds (Congruent) and 4.80 seconds (Incongruent).

## Visualizations

I have provided visualizations to show the distribution of the sample data:

- Histograms display the response time distribution for both Congruent and Incongruent conditions.
- A comparison graph shows the response time distributions for both conditions, highlighting the difference in means.

## Statistical Test

I performed a two-tailed t-test with a confidence level of 95% and 23 degrees of freedom. Here are the results:

- t-critical value: 1.7139
- Point estimate for the difference of means: 7.97
- Standard deviation of the differences: 4.8648
- t-statistic: 8.02

Since the t-statistic of 8.02 is greater than the critical value of 1.7139, we reject the null hypothesis. This confirms the existence of the Stroop effect, indicating that it takes less time to complete the congruent task compared to the incongruent task.

## Conclusion

In conclusion, the analysis of the Stroop effect dataset supports the presence of the effect, aligning with the expectations. The statistical test results show a significant difference in response times between congruent and incongruent conditions, providing empirical evidence for the phenomenon.
