# Churn Prediction Project (`customer-churn-prediction`)

A machine learning project designed to predict customer churn. This project provides end-to-end pipelines from raw data ingestion and processing, to model training, evaluation, and serving via a web application.

## Project Structure

```
customer-churn-prediction/
│
├── app/                  # Web application code (e.g., FastAPI, Streamlit, Flask)
│
├── data/                 # Project data files
│   ├── raw/              # Original, immutable data dump
│   └── processed/        # Cleaned and processed data ready for modeling
│
├── models/               # Trained and serialized model binaries (e.g., .pkl, .joblib)
│
├── notebooks/            # Jupyter notebooks for EDA and prototyping
│   ├── 01_data_understanding.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_eda.ipynb
│   ├── 04_feature_engineering.ipynb
│   └── 05_modeling.ipynb
│
├── reports/              # Generated analysis reports (HTML, PDF, figures)
│
├── src/                  # Source code for data pipelines, models, utilities
│   ├── data_loader.py
│   ├── data_cleaning.py
│   ├── feature_engineering.py
│   ├── preprocessing.py
│   ├── train.py
│   ├── evaluate.py
│   ├── predict.py
│   └── utils.py
│
├── tests/                # Unit and integration tests
│
├── README.md             # Project summary and documentation
├── requirements.txt      # Project dependencies
└── .gitignore            # File type ignoring rules
```

## Getting Started

### 1. Prerequisites
- Python 3.8 or higher
- Git

### 2. Setup
Clone this repository and set up a virtual environment:
```bash
git clone <repository-url>
cd churnpred
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

### 3. Usage
- **Notebooks**: Run the Jupyter Notebooks in the `notebooks/` directory sequentially from `01` to `05` for EDA, feature engineering, and model exploration.
- **Source Pipelines**: Run script modules in `src/` to execute data ingestion, preprocessing, training, or prediction pipelines.
- **Web App**: Run the web API application in `app/`.
