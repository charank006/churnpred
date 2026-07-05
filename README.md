# Churn Prediction Project (`churnpred`)

A machine learning project designed to predict customer churn. This project provides end-to-end pipelines from raw data ingestion and processing, to model training, evaluation, and serving via a web application.

## Project Structure

```
churnpred/
│
├── data/               # Project data files
│   ├── raw/            # Original, immutable data dump
│   └── processed/      # Cleaned and processed data ready for modeling
│
├── notebooks/          # Jupyter notebooks for EDA and prototyping
│
├── src/                # Source code for data pipelines, models, utilities
│
├── models/             # Trained and serialized model binaries (e.g., .pkl, .h5)
│
├── reports/            # Generated analysis reports (HTML, PDF, figures)
│
├── app/                # Web application code (e.g., FastAPI, Streamlit, Flask)
│
├── tests/              # Unit and integration tests
│
├── docs/               # Project documentation (Sphinx, Markdown, etc.)
│
├── requirements.txt    # Project dependencies
├── README.md           # Project summary and documentation
├── .gitignore          # File type ignoring rules
└── LICENSE             # MIT License
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
- **Data Processing**: Preprocess raw data by running modules within the `src/` directory.
- **Model Training**: Train models and save the serialized binaries to `models/`.
- **Evaluation**: Run Jupyter notebooks in `notebooks/` to inspect performance or check generated plots in `reports/`.
- **Web App**: Run the application located in `app/`.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
