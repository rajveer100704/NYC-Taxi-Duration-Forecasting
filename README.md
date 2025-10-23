# NYC Taxi Duration Forecasting

**Predicting taxi trip durations in NYC using PySpark & MLlib on the full 2016 dataset.**

---

## Project Overview
This project focuses on building scalable machine learning pipelines to predict taxi trip durations in New York City. Leveraging **PySpark** and **MLlib**, the solution handles large datasets efficiently, implements feature engineering, and achieves fast, accurate predictions using distributed computing.

Key highlights:
- Large-scale dataset processing (1-year NYC taxi trips, 2016)
- Feature engineering including pickup/dropoff location, distance, time, and trip-specific features
- Scalable ML pipelines using PySpark MLlib (Regression models)
- Model evaluation and performance optimization
- Resume-ready showcase of **Big Data, PySpark, MLlib, and Predictive Modeling skills**

---

## Folder Structure
NYC-Taxi-Duration-Forecasting/


├── data/
│
├── raw/                 # Original datasets (CSV)

│   ├── processed/           # Cleaned / preprocessed data

│
├── notebooks/

│   └── NYC_Taxi_Analysis.ipynb   # EDA and initial experiments

│
├── src/

│   ├── data_preprocessing.py      # Data cleaning & feature engineering

│   ├── model_training.py          # MLlib model training scripts

│   ├── model_evaluation.py        # Evaluation metrics and validation

│   └── utils.py                   # Helper functions

│
├── requirements.txt               # Python dependencies

├── .gitignore

├── README.md

└── LICENSE
