# STT465-Project

## Project Overview:
- **Objective**: Predict undercount in voting data using regression models
- **Data Source**: gavote dataset in the R-package faraway

## Methodology
- **Frequentist Approach**: Utilized **step function regression models** to assess the relationship between explanatory variables and undercount.
- **Bayesian Approach**: Implemented **Bayesian model selection and averaging** to capture uncertainty and provide posterior distributions for coefficient estimation.
- **AIC Comparison**: Evaluated model fit using **Akaike Information Criterion (AIC)** for model selection.
- **Residual Analysis**: Analyzed residuals and **Q-Q plots** to validate model assumptions (normality, homoscedasticity).
  
## Key Features
- **Frequentist Model**: 
  - Performed **stepwise regression** to determine the best subset of predictors.
- **Bayesian Model**: 
  - Applied **non-informative priors** and **model averaging** to assess model uncertainty.
  - Provided **credible intervals** for each variable's coefficient, offering a more probabilistic interpretation of the results.
  
## Model Comparison
- **AIC Comparison**: Frequentist model had the lowest AIC (-773.57), while the Bayesian model had a slightly higher score but offered **better uncertainty quantification**.
- **Interpretability**: Bayesian model showed **fewer variables**, offering a more **parsimonious** approach with robust uncertainty analysis.
