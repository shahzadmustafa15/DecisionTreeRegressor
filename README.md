# Decision Tree Regressor – Multiple Linear Regression Dataset

This project implements a Decision Tree Regressor using a multiple linear regression dataset. The focus is on exploring model performance, overfitting, and pruning techniques to improve generalization.

## 📁 Dataset

- **Name:** `multiple_linear_regression_dataset.csv`
- **Type:** Supervised Regression
- **Description:** Contains numerical features used to predict a continuous target.

## 🧠 What This Project Covers

- Data preprocessing
- Model training using `DecisionTreeRegressor`
- Evaluation using R² scores
- Visualization of depth vs. performance


## 📈 Results

- **Train Score:** Ranges from 0.75 to 1.00 depending on depth
- **Test Score:** Peaks around 0.94 with appropriate pruning

## 🚀 How to Run

```bash
git clone https://github.com/shahzadmustafa15/DecisionTreeRegressor.git
cd DecisionTreeRegressor
pip install -r requirements.txt
jupyter notebook DecisionTreeRegressor.ipynb
