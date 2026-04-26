# Student-Placement-Prediction
Machine learning project predicting student placements using Classification and Regression Analysis

## Project Overview
This project predicts whether a student will be placed based on academic and personal attributes using machine learning models and how much will be their package.

## Dataset
- Source: Kaggle - Student Placement Prediction Dataset 2026

## Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib / Seaborn

## Models Used
- Random Forest
- XGBRegressor

## Results
- Best Model RMSE: 1.0132
- Key Insights:
  - Coding skill score had the highest importance (0.21)
  - Students with >2 internships had 30% higher placement rates
```text
Project Structure
Student-Placement-Prediction/
├── data/ # (empty – dataset is loaded from Kaggle)
├── notebooks/
│ └── placement_prediction.ipynb # walk‑through notebook
├── Loading data and data cleaning/
├── Exploratory Data Analysis (EDA)
  └── Univariate Analysis
  └── Bivariate Analysis
  └── Correlation Analysis
├── Classification Model
  ├── Train
  └── Evaluation
├── Regression Model
  └── Train and Evaluation
├── LICENSE
├── README.md
```

License

CC0: Public Domain

## Initialize Git (local)

Inside `Student-Placement-Prediction/`, run:

```bash
git init
git add .
git commit -m "Initial commit: Student placement prediction project"
