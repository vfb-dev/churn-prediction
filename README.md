# Telecom Customer Churn Prediction

A model that predicts customer churn probability using logistic regression implemented with Scikit-learn.

## Run

From the project root:

```bash
python -m pip install notebook pandas numpy matplotlib seaborn scikit-learn
python -m jupyter notebook
```

Run all notebook cells. The dataset is included in the project.

## Model

The model processes customer data, performs feature engineering, and splits the dataset into training, validation, and test sets. It uses numerical and categorical customer features to train a logistic regression classifier.

The model outputs churn probabilities, estimating how likely each customer is to leave the telecom service. The final cells demonstrate individual customer predictions and churn probability analysis.

## Author

vfb-dev - Building intelligent systems