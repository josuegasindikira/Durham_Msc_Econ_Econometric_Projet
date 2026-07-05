# Durham MSc Econometrics Project

This repository contains an applied econometric analysis based on Acemoglu, Johnson and Robinson (2001), *The Colonial Origins of Comparative Development*. The project studies the relationship between political institutions and economic performance using R.

The main outcome variable is `loggdp`, which measures economic performance, while `risk` is used as a measure of institutional quality. The analysis combines OLS regressions, robust standard errors, endogeneity discussion, instrumental-variable estimation and robustness checks.

## Project overview

The project addresses several econometric questions:

1. Visualising the relationship between institutional quality and log GDP per capita.
2. Estimating a baseline OLS model of `loggdp` on `risk`.
3. Comparing conventional OLS standard errors with heteroskedasticity-robust standard errors.
4. Adding geographical controls such as latitude and an Africa dummy.
5. Discussing the potential endogeneity of institutions.
6. Using log settler mortality as an instrumental variable for institutional quality.
7. Running first-stage, reduced-form and two-stage least squares regressions.
8. Performing robustness checks using malaria controls, continent dummies and sample restrictions.

## Repository structure

```text
.
├── Code/
│   └── AJR_analysis_clean_commented.R
├── Data/
│   └── AJR.xlsx
├── Project/
│   └── final_report.pdf
├── .gitignore
└── README.md
```

## Code

The main R script is located in:

```text
Code/R_Code.R
```

The script is organised according to the structure of the assignment:

- Question 1: baseline OLS and scatter plot
- Question 2: robust standard errors and Breusch-Pagan test
- Question 3: OLS with additional controls
- Question 4: endogeneity discussion
- Question 5: instrumental-variable estimation
- Question 6: robustness checks

## Methods

The empirical analysis uses:

- Ordinary Least Squares (OLS)
- Heteroskedasticity-robust standard errors
- Breusch-Pagan test
- First-stage regression
- Reduced-form regression
- Two-stage least squares (2SLS)
- Weak-instrument diagnostics
- Wu-Hausman test
- Robustness checks with additional controls and sample restrictions

## Data

The dataset used in the analysis is based on Acemoglu, Johnson and Robinson (2001). 
```
## Main reference

Acemoglu, D., Johnson, S., & Robinson, J. A. (2001).  
*The Colonial Origins of Comparative Development: An Empirical Investigation*.  
American Economic Review, 91(5), 1369–1401.

## Author

Gasindikira Josué Issa  
MSc Economics, Durham University
