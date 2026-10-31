# Student Score Prediction Using Machine Learning

## Project Overview
This project uses Machine Learning to predict students' final grades based on their personal information, study habits and previous academic performance.

Two machine learning algorithms are trained and compared to identify the better-performing model.

## Objectives
- Prepare and analyze a student dataset.
- Split data into training and testing sets.
- Train two machine learning models.
- Generate student grade predictions.
- Compare model performance using evaluation metrics.

## Dataset
- Dataset: Student Performance (`student-mat.csv`)
- Total records: 395
- Total columns: 33
- Target variable: G3 (Final Grade)

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Machine Learning Models
1. Linear Regression
2. Decision Tree Regression

## Model Performance

| Metric | Linear Regression | Decision Tree |
|---|---:|---:|
| MAE | 1.65 | 1.14 |
| MSE | 5.66 | 4.20 |
| R² Score | 0.72 | 0.80 |

## Key Findings
- Both models generated student grade predictions.
- Decision Tree achieved a higher R² score of 0.80.
- Decision Tree had lower MAE and MSE values.
- Decision Tree performed better on the selected test dataset.

## Project Files
- `student-mat.csv` – Student dataset.
- `Week_4_Machine_Learning.ipynb` – Machine learning notebook.
- `model_comparison.png` – Model comparison graph.
- `prediction_results.csv` – Actual and predicted grades.
- `Week_4_Model_Comparison_Report.md` – Detailed project report.

## Conclusion
This project demonstrates how machine learning can be used for student score prediction. It provided practical experience in data preparation, model training, prediction generation and model evaluation.

Based on the experiment, Decision Tree Regression performed better than Linear Regression on the selected test dataset.

**AI/ML Internship – Week 4 Project**
