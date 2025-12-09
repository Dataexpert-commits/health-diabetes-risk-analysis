📊 Diabetes Health Risk Analysis (R Project)

This project performs an exploratory and predictive analysis of a publicly available diabetes dataset. The goal is to identify the key health factors associated with diabetes and evaluate a logistic regression model for predicting diabetes outcomes.

Project Objectives
-Conduct Exploratory Data Analysis (EDA) on health-related variables
-Visualize correlations and outcome patterns
-Train a logistic regression classifier
-Evaluate model performance using accuracy and AUC
-Present a clean, reproducible workflow in R

🧰 Technologies Used
-R
-tidyverse
-caret
-ROCR
-corrplot
-R Markdown

📂 Repository Structure
notebooks/
   └── diabetes-analysis.Rmd     # Full analysis notebook
data/
   └── .keep                     # Folder placeholder
src/
   └── .keep                     # Helper scripts (future)
README.md                         # Project documentation


📈 Key Results
-Glucose, BMI, and Age are strongly associated with diabetes outcome
-Logistic regression model achieved ~75% accuracy
-ROC curve analysis yielded AUC ≈ 0.80
-Analysis includes visualizations and interpretation

📁 Dataset
This project uses the public diabetes dataset mirrored by Plotly/Kaggle:
https://raw.githubusercontent.com/plotly/datasets/master/diabetes.csv


🚀 How to Run the Notebook
1. Install required R packages:
   install.packages(c("tidyverse", "caret", "ROCR", "corrplot", "knitr"))
2. Open the diabetes-analysis.Rmd file in RStudio
3. Run all cells or click Knit → HTML


📝 Future Improvements
. Add Random Forest and XGBoost models
. Include SHAP interpretations
. Build a small dashboard using Shiny

📬 Author

Deborah Okunola
Biostatistician/Health Data Analyst
GitHub: Dataexperts-commits









