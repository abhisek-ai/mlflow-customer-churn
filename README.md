# MLflow Customer Churn Prediction

## Project Overview

This project uses **MLflow** to track machine learning experiments for customer churn prediction. It demonstrates experiment tracking, model registry, and deployment workflows.

## Quick Start

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

## Project Structure

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

## Features

- **Synthetic Dataset**: 5000 customer records with churn labels
- **Models Tested**: Random Forest, Gradient Boosting
- **Hyperparameter Tuning**: Grid search with 20 parameter combinations
- **Model Registry**: Version control and production deployment
- **Metrics Tracked**: AUC, Accuracy

## Results

- **Best Model**: Gradient Boosting Classifier
- **AUC Score**: ~0.89
- **Production Ready**: Model deployed to MLflow Model Registry

## Screenshots

### MLflow Experiments Tracking
All experiment runs with parameters and metrics tracked in MLflow:
<img width="1920" height="1080" alt="Screenshot 2025-11-03 at 10 11 09 PM (2)-1" src="https://github.com/user-attachments/assets/e0250d55-6788-453d-9d00-c4f6ef6fb248" />

### Model Registry
Model versioning and stage transitions (Produ<img width="1920" height="1080" alt="Screenshot 2025-11-03 at 10 11 40 PM (2)-1" src="https://github.com/user-attachments/assets/01da174d-dcc4-45c2-b83b-04e2de743953" />
ction/Staging/Archived):

<img width="1920" height="1080" alt="Screenshot 2025-11-03 at 10 05 27 PM (2)-1" src="https://github.com/user-attachments/assets/a3d46839-885a-4d88-b3c6-06072e1f8942" />

## Technologies

- Python 3.12
- MLflow
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn

## Key Insights

- **Feature Importance**: Monthly charges and tenure are the strongest predictors of customer churn
- **Model Performance**: Gradient Boosting outperformed Random Forest by ~3.5% in AUC
- **Hyperparameter Impact**: Learning rate and number of estimators had the most significant impact on model performance

## License

MIT License

## Author

**Abhisek Mallick**
- GitHub: [@abhisek-ai](https://github.com/abhisek-ai)
