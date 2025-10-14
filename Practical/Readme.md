🧾 README
Project Title

Faculty Tenure and Demographic Analysis

Overview

This notebook performs statistical and visual analysis to explore relationships between tenure status and various demographic variables (visible minority status, age, gender, evaluation score). It simulates a dataset of 200 faculty members and applies basic statistical methods to test hypotheses and visualize patterns.

Key Objectives

Determine if tenure status differs based on visible minority status.

Analyze how age varies with tenure status.

Identify which type of visualization best represents the age distribution.

Explain the difference between pyplot.bar and pyplot.barh while visualizing gender distribution.

Calculate the median evaluation score for tenured professors.

📊 Conclusion

Tenure vs. Visible Minority:
The Chi-square test evaluates whether tenure status significantly differs between visible minorities and non-minorities. Depending on the p-value, we can conclude if there’s statistical evidence of bias or not.

Age and Tenure Relationship:
The analysis of mean and standard deviation reveals that tenured professors generally have higher average ages, reflecting the natural career progression before tenure.

Visual Representation:
A boxplot effectively illustrates the age distribution across tenure groups, highlighting medians, quartiles, and outliers.

Gender Distribution:
The plt.bar() chart provides a clear count of gender representation. (Note: plt.barh() would produce a horizontal version of the same graph.)

Evaluation Scores:
The median evaluation score of tenured professors provides an insight into their performance distribution and can be compared with untenured staff in further analysis.
