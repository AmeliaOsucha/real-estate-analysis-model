# real-estate-analysis-model
# FULL REPORT: https://ameliaosucha.github.io/real-estate-analysis-model/real-estate-model.html
##  Key Features
* **Multi-Source Data Integration:** Merged and cleaned administrative spatial and economic datasets covering 380 districts.
* **Objective Variable Selection:** Applied **Hellwig’s taxonomic method** to select the optimal subset of explanatory variables and avoid multicollinearity.
* **Econometric Modeling:** Estimated an **Ordinary Least Squares (OLS) regression model** (level-log specification) to identify key price determinants.
* **Rigorous Diagnostics:** Conducted comprehensive residual verification (normality, homoscedasticity, and collinearity checks).
* **Automated Reporting:** Fully reproducible workflow generated via R Markdown.

##  Tech Stack & Libraries
* **Language:** R
* **Environment:** RStudio, R Markdown
* **Data Manipulation & Tidyverse:** `dplyr`, `readxl`, `lmtest`
* **Visualization:** `ggplot2`
* **Econometrics & Statistics:** Custom scripts for Hellwig’s method.

##  Methodology & Workflow
1. **Data Preprocessing & Cleaning:** Handling missing values, standardizing administrative identifiers for 380 counties.
2. **Taxonomic Analysis (Hellwig's Method):** Calculating development patterns and selecting the best combination of independent variables.
3. **Model Estimation:** Fitting the OLS regression model and analyzing coefficients.
4. **Diagnostic Testing:** Verifying model assumptions to ensure statistical reliability.
