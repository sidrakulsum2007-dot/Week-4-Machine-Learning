# Week 4 – Machine Learning Prediction Model

## 1. Project Title
**Student Score Prediction Using Machine Learning**

## 2. Objective
The objective of this project is to build machine learning models that predict students' final grades using their academic and personal information. Two machine learning algorithms were trained and compared to identify the better-performing model.

## 3. Dataset Description
The project uses the Student Performance dataset (`student-mat.csv`).

- Total records: 395
- Total columns: 33
- Target variable: G3 (Final Grade)
- Input features: Student details, study habits and previous grades.

## 4. Data Preparation
The following steps were performed:

- Loaded the dataset using Pandas.
- Checked missing values.
- Checked duplicate records.
- Separated input features (X) and target variable (y).
- Converted categorical data into numerical values using One-Hot Encoding.
- Split the dataset into 80% training data and 20% testing data.

## 5. Machine Learning Models

### Linear Regression
Linear Regression was trained to predict students' final grades. It learns the relationship between input features and numerical output values.

### Decision Tree Regression
Decision Tree Regression was trained to predict final grades by learning decision-based patterns from the dataset.

## 6. Model Evaluation

The models were evaluated using MAE, MSE and R² Score.

| Evaluation Metric | Linear Regression | Decision Tree |
|---|---:|---:|
| MAE | 1.65 | 1.14 |
| MSE | 5.66 | 4.20 |
| R² Score | 0.72 | 0.80 |

## 7. Model Comparison
The Decision Tree model performed better than Linear Regression on the selected test dataset.

- Decision Tree achieved a lower MAE of 1.14.
- Decision Tree achieved a lower MSE of 4.20.
- Decision Tree achieved a higher R² Score of 0.80.

Therefore, Decision Tree was the better-performing model in this experiment.

## 8. Prediction Results
Both trained models generated predictions for the testing dataset. The actual grades and predicted grades were saved in `prediction_results.csv`.

## 9. Conclusion
This project provided practical experience in preparing data, training machine learning models, generating predictions and evaluating model performance.

The comparison showed that Decision Tree Regression performed better than Linear Regression for this particular dataset and train-test split.

## 10. Tools and Technologies
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn