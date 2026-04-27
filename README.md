# Quantification of Credit Risk

A comprehensive statistical analysis project distinguishing inference from prediction in credit default modeling using bootstrap resampling, Bayesian estimation, and predictive modeling techniques.

## Repository Structure

```
Credit-Default-Inference-Prediction/
│
├── data/
│   ├── raw/
│   │   └── default_of_credit_card_clients.xls    # Original dataset
│   └── processed/
│       └── cleaned_default_data.csv               # Cleaned dataset for analysis
│
├── notebooks/
│   ├── problem_formulation.ipynb                  # Problem definition and research questions
│   ├── data_cleaning.ipynb                        # Data preprocessing pipeline
│   ├── data_exploration.ipynb                     # Exploratory data analysis
│   ├── likelihood_mle.ipynb                       # Likelihood functions and MLE
│   ├── frequentist_inference.ipynb                # Confidence intervals and hypothesis testing
│   ├── bayesian_estimation.ipynb                  # Prior specification and posterior inference
│   ├── resampling_simulation.ipynb                # Bootstrap and Monte Carlo methods
│   ├── prediction_evaluation.ipynb                # Predictive modeling with double bootstrap
│   ├── regularization.ipynb                       # Ridge/Lasso regularization
│   └── inference_vs_prediction.ipynb              # Comparative analysis
│
├── requirements.txt                                # Python dependencies
└── README.md                                       # Project documentation
```

## Reproduction Instructions

### 1. Create and activate a virtual environment

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the notebooks

Launch Jupyter and execute notebooks:

```bash
jupyter notebook
```


## Key Features

- **Resampling Methods**: Standard bootstrap, Monte Carlo simulation, and double bootstrap implementation
- **Predictive Modeling**: Logistic regression with stratified train/test split and 5-fold cross-validation
- **Evaluation Metrics**: Precision-Recall AUC (PR-AUC) for imbalanced classification
- **Class Imbalance Handling**: Class-weighted models and proper evaluation metrics
- **Reproducibility**: Seeded random number generation and dependency management
