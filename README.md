# Linear Mixed Models (LMMs)

LMMs in statistics are designed to analyze data that are not independent, such as nested, hierarchical, or longitudinal data, by combining **fixed effects** and **random effects**. They are used to account for variability across different grouping variables (e.g., subjects, classrooms, regions).

## Key statistics and information that LMMs provide include:

- **Fixed Effects (Estimated Coefficients):** These represent the average, systematic relationship across the entire population, similar to standard linear regression (e.g., the average effect of a drug over time).
- **Random Effects (Intercepts and Slopes):** These account for variations between clusters or individuals (e.g., how individual subject differs from the average).
- **Variance Components:** LMMs estimate the variance of the random effects (unmeasured differences between groups) and the residual variance (within-group error).
- **Covariance Structures:** For longitudinal data, LMMs can model the correlation structure, such as assuming that measurements closer in time are more correlated than those further apart.
- **Standard Errors & P-values:** LMMs provide corrected standard errors for fixed effects, preventing the inflated Type I error rates that occur when ignoring the structure of hierarchical data.
- **Marginal vs. Conditional Effects:** LMMs allow researchers to estimate both population-average (marginal) effects and subject-specific (conditional) effects.

## **Key Uses:**

- **Repeated Measures/Longitudinal Data:** Analyzing data where the same subject is measured multiple times.
- **Unbalanced Data:** Handling datasets with missing values or unequal group sizes.
- **Multilevel Analysis:** When data has hierarchical structures (e.g., students within schools).

## **Comparison with Other Methods:**

- **ANOVA:** While LMMs yield similar results to ANOVA on balanced data, they are more flexible, allowing for unequal variances and handling missing data better.
- **OLS Regression:** LMMs improve on ordinary least squares (OLS) regression by not violating the assumption of independence
