# Student Academic Risk Analysis

This project explores whether student academic risk levels can be predicted using behavioural, lifestyle, preparation, and background variables.

The analysis includes exploratory data analysis, preprocessing, multinomial logistic regression, a reduced logistic regression model, and a random forest classifier.

## Dataset

The target variable is `performance_risk_level`, with three classes:

- Low Risk
- Moderate Risk
- High Risk

Direct target-construction variables such as CGPA category, attendance percentage, stress level, and academic consistency were excluded from modelling to reduce target leakage.

## Key Findings

- Academic satisfaction, energy level, study hours, and task completion behaviours were among the strongest predictors.
- The full logistic regression model was most useful for identifying Moderate Risk and High Risk students.
- The random forest classifier achieved slightly higher overall accuracy, but improvements were modest.
- Overall model performance suggests academic risk is difficult to classify accurately using indirect survey variables alone.

## Technologies Used

- Python
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- Jupyter Notebook

## Files

- `academic_risk_analysis.ipynb` — full analysis notebook
- `hybrid_student_performance_1200.xlsx` — dataset
