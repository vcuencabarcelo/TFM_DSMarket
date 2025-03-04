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
│── Preprocessing/
│   ├── Preprocessing_datos.ipynb  # Data cleaning and transformation
│   ├── Graficos.ipynb             # Explanation graphs of Data
│   ├── Análisis_Ventas.ipynb      # Sales data analysis 
│
|
│── MLCluster/
|   ├── Cluster_Productos.ipynb    # ML Cluster model for Products
│   ├── Cluster_Tiendas.ipynb      # ML Cluster model for Shops
|
|
│── MLTimeseries/
│   ├── TimeSeries_Forecast.ipynb  # ML TimeSeries model to forecast sells 1mo
|
|
│── BusinessDocs/
│   ├── Informe_DSMarket_retail-3.pdf  # Business-oriented documentation of results
│   ├── Presentación_DSMarket_3.pdf    # Business-oriented presentation of results
|   ├── Visualización_Ventas(BI).pdf   # PowerBI presentation of results
│
│── requirements.txt    # List of dependencies
│── README.md          # Project documentation
```

---

## Detailed Description

### 1. Data Preprocessing
- Located in the `Preprocessing/` folder, this stage includes:
  - Cleaning and handling missing values (`Preprocessing_datos.ipynb`).
  - Data visualization and exploratory analysis (`Graficos.ipynb`).
  - Sales data analysis (`Análisis_Ventas.ipynb`).

### 2. Model Development
- Implemented in `MLCluster/` and `MLTimeseries/`:
  - **Clustering Models** (`MLCluster/`):
    - Product clustering for segmentation (`Cluster_Productos.ipynb`).
    - Store clustering for regional insights (`Cluster_Tiendas.ipynb`).
  - **Time Series Forecasting** (`MLTimeseries/`):
    - Sales forecasting model for one-month predictions (`TimeSeries_Forecast.ipynb`).

### 3. Business Documentation
- Results are documented in the `BusinessDocs/` folder:
  - Detailed business report (`Informe_DSMarket_retail-3.pdf`).
  - Presentation slides for business stakeholders (`Presentación_DSMarket_3.pdf`).
  - PowerBI interactive visualization of sales data (`Visualización_Ventas(BI).pdf`).

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
