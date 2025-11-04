# MLflow Customer Churn Prediction

## 📊 Project Overview

This project uses **MLflow** to track machine learning experiments for customer churn prediction. It demonstrates experiment tracking, model registry, and deployment workflows.

## 🚀 Quick Start

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/mlflow-customer-churn.git
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
├── starter.py                          # Main Python script
├── mlruns/                            # MLflow tracking data 
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

## 🛠️ Technologies

- Python 3.12
- MLflow
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn

## 📝 License

MIT License

## 👤 Author

**Abhisek Mallick**
- GitHub: [@abhisek-ai](https://github.com/abhisek-ai)