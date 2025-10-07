# American Wage Determinants: A Statistical Analysis

This project investigates the key factors that influence wages in the United States using data from the [Current Population Survey (CPS)](https://www.census.gov/programs-surveys/cps.html). By applying multiple linear regression models, we analyze how education, experience, union membership, marital status, gender, race, occupation, and region impact wage outcomes.

## 📊 Project Overview
- **Purpose**: Understand wage disparities and identify the most significant predictors of income.
- **Dataset**: [CPS Wage Data (534 individuals)](https://raw.githubusercontent.com/WilfredxWZDM/WageAnalysisST362Project/refs/heads/main/wage.data.txt)
- **Techniques Used**:
  - Exploratory Data Analysis (EDA)
  - Multiple Linear Regression with log transformation
  - Outlier and influence diagnostics
  - Stepwise AIC/BIC model selection
  - Policy simulations (e.g., increasing unionization & education)

## 🔑 Key Findings
- **Education** is the strongest predictor of sustained wage growth, while experience shows diminishing returns.
- **Gender Gap**: Men consistently earn more than women, even after controlling for other factors.
- **Race Gap**: Black individuals experience lower wage returns to education compared to White and Other groups.
- **Regional Gap**: Workers in the U.S. South earn significantly less on average.
- **Union Membership**: Associated with higher wages.
- **Marriage**: Increases wages for men much more than for women.

A policy simulation showed that increasing unionization by 20% and average education by 2 years could raise average wages by **$2.51/hour**.

## 📂 Repository Contents
- `Wage Analysis - Project.Rmd` → Main R Markdown file with analysis and plots.
- `Wage Statistical Analysis Report.pdf` → Final report summarizing findings.
- `wage.data.txt` → Dataset (linked above).

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/wage-analysis.git
   cd wage-analysis
   ```
2. Open Wage Analysis - Project.Rmd in RStudio.
3. Knit the document to generate the HTML or PDF report.

📌 Notes

- The regression model explains ~46% of the variation in wages.
- Results highlight both structural inequalities and the positive impact of education and unions on wage outcomes.
- Future work could explore non-linear models and additional predictors (e.g., industry, cost of living).

✍️ Authors: Nguyen Hai Trung Pham, Wilfred William
📅 Date: July 2025

