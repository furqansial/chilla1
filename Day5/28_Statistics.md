## Choosing a Statistical method
>This willl enhance your skills:
1. Choosing a right statistical method
2. Do's and Don'ts of statistics
3. Reliable results
4. Paper revisions with proof of statistical test (WHOs)
5. Making Data Visualization
6. Interpreting Results

# **Tests and their types**

Parametric Tests| Non-Parametric Tests
---------|----------
| More Reliable Results | Less Reliable Results
| First we have to meet the assumptions | Calculate the rank of Data
| | No need to meed the assumptions

> # **Before Starting the Data Analysis**

> ## Step-1: Normality Test
Tests to be used:
1. Shapiro-wilk test
   - Specific (Reliable)
2. Kolmogorov-smirnov Test
   - General (Less Reliable)

> ## Step-2: Homogeneity Test
> The Variance of variable in data are equal \

Test to be used: Levene's Test

> ## Step-3: Purpose
> Know the purpose of your research question

> <p align='center'>Two types of purposes</p>

Comparison (Difference) | Relationship (Connection)
------------------------| -----------------------
at least groups         | find a connection
Example:                | Example:
  _male vs female                            |  _Can food Predict weight of a group of individuals
  _Control groups vs Treatment group         |  _Do fertilizer application increases crop growth?
  _Grouping individuals by color prefrences  |  We seek following here:
  | | _Connection
  | | _Correction
  | | _Causation
  | | _Prediction

> ## Step-4: Data Type
> Know the type of your data you are working with

> <p align='center'>Two types of Data</p>
Categorical | Continuous
------------|------------
Qualitative | Quantitative
No Numerical Meaning | Numerical
Represented in texts | Mostly represented in Numbers
(e.g character, factors) | (e.g Numerical variables (int, float))
(e.g True/False) | Examples:
(e.g Yes/No)    | _Amount, Number, Age, Plant Height

> ## Step-5: Statistical Tests:
> Choose a statistical test form three main families

1. Chi-Squared
   - Purpose: Comparison
   - Data: Categorical Only (chi-squared)

2. t-Test / ANOVA
    - Purpose: Comparison
    - Data: Categorical and Continous (t-Test)

3. Correlation
    - Purpose: Relationship
    - Data: Continuous only (correlation)

---
> ## <p align='center'>When and Where to use? </p>
---
### **Chi-Squared**
Types: 
1. Chi-squared test of homogeneity
2. Chi-squared test of independence

> When to use?
- Nothing effects this
- Can be used with any number of levels or groups
> you must remember the purpose and datatype

### **t-Test / ANOVA**
Typs:
1. One-sample t-Test (for one sample group with a know mean)
2. Two-sample t-Test
    - Un-paired t-Test (two-different groups)
    - Paired t-Test (sample group twice)
3. ANOVA (Analysis of Variance)(3+ levels or groups are involved)
    - One way ANOVA (Even one of group is significant you will get significant results, but doesn't tell you which one)
    - Two-way ANOVA
    - Repeated Measures of ANOVA (3+ Paired groups, scale up of paired t-Test)

### **Correlation**
Types:
1. Pearson's correlation (one-independent and one dependent variable)
2. Regression (One-Independent and one dependent variable)


**Correlation:** Tells us how closely connected two variables are? e.g. "Is food a predictor of weight gain"

**Regression** Tells us a specific mathematical equation that describes the relationship.
> This helps us to find the data points not measured yet

e.g Missing values can be predicted like this!

---

### These tests trusts you that
- Your data is Normally distributed
- Or follow a gaussian distribution

---

# **Non-Reliable Results**

> If you do not follow the assumptions and break the trusts of 3-test families, they will not happy with you

**If assumptions are not met!**

