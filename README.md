# Final Project - Data Science & AI Master's Program

## Overview
This repository contains the final project for the Master's program in Data Science & AI. The project is structured into three main components:

1. **Data Preprocessing**: Cleaning, transforming, and preparing data for modeling.
2. **Model Development**: Training and evaluating machine learning models.
3. **Business Documentation**: Interpreting results and providing insights for decision-making.

---

## Repository Structure

```
TFM_DSMarket/
│── data/
│   ├── raw/             # Original, unprocessed datasets
│   ├── processed/       # Cleaned and transformed datasets
│   ├── external/        # Additional external data sources
│
│── notebooks/
│   ├── 01_data_preprocessing.ipynb  # Data cleaning and transformation
│   ├── 02_feature_engineering.ipynb  # Feature selection and creation
│   ├── 03_model_training.ipynb       # Model selection and training
│   ├── 04_evaluation.ipynb           # Model evaluation and performance analysis
│
│── src/
│   ├── preprocessing.py   # Data preprocessing scripts
│   ├── modeling.py        # Model training and evaluation scripts
│   ├── utils.py           # Utility functions
│
│── reports/
│   ├── business_report.pdf  # Business-oriented documentation of results
│   ├── model_performance/   # Visualizations and metrics for model evaluation
│
│── requirements.txt    # List of dependencies
│── README.md          # Project documentation
```

---

## Detailed Description

### 1. Data Preprocessing
- Located in the `data/` folder, this stage includes:
  - Cleaning and handling missing values.
  - Normalization and standardization.
  - Feature selection and transformation.
  - Integration of external data sources.

### 2. Model Development
- Implemented in `notebooks/` and `src/`:
  - Various machine learning models are trained and compared.
  - Feature engineering techniques are applied.
  - Model selection and hyperparameter tuning are performed.
  - Evaluation metrics and visualization of model performance.

### 3. Business Documentation
- Results are documented in the `reports/` folder:
  - Business insights and recommendations.
  - Visualization of key findings.
  - Comparison of different models and their impact on decision-making.

---

## Installation & Usage
To set up the project environment, install dependencies:
```bash
pip install -r requirements.txt
```

To run the preprocessing scripts:
```bash
python src/preprocessing.py
```

To train models:
```bash
python src/modeling.py
```

---

## License
This project is licensed under the MIT License - see the `LICENSE` file for details.
