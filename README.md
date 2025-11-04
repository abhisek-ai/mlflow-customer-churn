# MLflow Customer Churn Prediction

## 📊 Project Overview

This project uses **MLflow** to track machine learning experiments for customer churn prediction. It demonstrates experiment tracking, model registry, and deployment workflows.

## 🚀 Quick Start

### Installation

```bash
# Clone the repository
git clone https://github.com/abhisek-ai/mlflow-customer-churn.git
cd mlflow-customer-churn

# Install dependencies
pip install mlflow scikit-learn pandas numpy matplotlib seaborn jupyter
```

### Run the Project

```bash
# 1. Run the Python script
python mlflow_customer_churn.py

# 2. View MLflow UI
mlflow ui --port=5001
```

## 📁 Project Structure

```
mlflow-customer-churn/
├── mlflow_customer_churn.py          # Main Python script
├── screenshots/                       # MLflow UI screenshots
│   ├── experiments.png
│   ├── model_registry.png
│   └── model_comparison.png
├── mlruns/                           # MLflow tracking data
└── README.md                          # This file
```

## 🎯 Features

- **Synthetic Dataset**: 5000 customer records with churn labels
- **Models Tested**: Random Forest, Gradient Boosting
- **Hyperparameter Tuning**: Grid search with 20 parameter combinations
- **Model Registry**: Version control and production deployment
- **Metrics Tracked**: AUC, Accuracy

## 📈 Results

- **Best Model**: Gradient Boosting Classifier
- **AUC Score**: ~0.89
- **Production Ready**: Model deployed to MLflow Model Registry

## 📸 Screenshots

### MLflow Experiments Tracking
All experiment runs with parameters and metrics tracked in MLflow:

![Experiments Tracking](screenshots/experiments.png)

### Model Registry
Model versioning and stage transitions (Production/Staging/Archived):

![Model Registry](screenshots/model_registry.png)

### Model Performance Comparison
Comparison of different model performances and hyperparameters:

![Model Comparison](screenshots/model_comparison.png)

## 🛠️ Technologies

- Python 3.12
- MLflow
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn

## 🔍 Key Insights

- **Feature Importance**: Monthly charges and tenure are the strongest predictors of customer churn
- **Model Performance**: Gradient Boosting outperformed Random Forest by ~3.5% in AUC
- **Hyperparameter Impact**: Learning rate and number of estimators had the most significant impact on model performance

## 📝 License

MIT License

## 👤 Author

**Abhisek**
- GitHub: [@abhisek-ai](https://github.com/abhisek-ai)