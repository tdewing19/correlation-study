# correlation-study
This is a quick guide on how to run a correlation study in R using various statistical techniques. Typically, you would run a correlation study when trying to determine if there is a significant relationship between two or more categorical variables (i.e. a person's gender and their political party). 

<p align="center">
  <img src="https://www.statology.org/wp-content/uploads/2020/12/tetra2.png"/>
</p>

This guide describes how to determine the strength of relationship between pairs of nominal categorical variables, or variables with categories without a clear rank or order. A **[PDF guide](https://github.com/tdewing19/correlation-study/blob/main/Correlation-Study-Sample.pdf)** as well as the **[source code](https://github.com/tdewing19/correlation-study/blob/main/Correlation%20Study%20Sample.Rmd)** in R are provided. The statistical techniques covered include:
- **Chi-Squared Test of Independence 🧑‍🤝‍🧑**
  * A statistical hypothesis test that uses a contingency (count) table to determine if two categorical variables are independent or dependent.
- **Fisher's Exact Test 🎣**
  * Another statistical hypothesis test that uses a contingency table to determine if two categorical variables are independent or dependent, most useful when the assumption for the chi-square test of independence that all the expected counts are sufficiently large (5 or greater) is not met.
- **Cramer's V 🖖**
  * Used to estimate the statistical correlation between two categorical variables with a value between 0 and 1 that represents the
    strength of the correlation.
