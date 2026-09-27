# real-estate-analysis-model 
## FULL REPORT: https://ameliaosucha.github.io/real-estate-analysis-model/real-estate-model.html

# Project Snapshot (TL;DR for Recruiters)
### Main Goal: Identification and quantification of key economic determinants affecting real estate prices across districts, delivering a data-driven market valuation model.
### Methods & Workflow:
* Variable Selection: Applied Hellwig’s taxonomic method to objectively select optimal explanatory variables and avoid multicollinearity.
* Econometric Modeling: Estimated an Ordinary Least Squares (OLS) regression model using a level-log specification.
* Model Diagnostics: Conducted rigorous residual verification (normality, homoscedasticity, VIF checks) to ensure statistical reliability.
### Key Results:
* Developed a robust, fully diagnostic-checked econometric model explaining price variance.
* Implemented a fully reproducible, automated analysis pipeline using R Markdown
  
---

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
