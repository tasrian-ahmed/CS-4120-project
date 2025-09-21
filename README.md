# CS-4120 Course Project – Medical Insurance Cost Prediction

## Overview
This project analyzes the **Medical Cost Personal Dataset** to tackle two tasks:
1. **Classification**: predict whether an individual falls into a high-cost or low-cost group.
2. **Regression**: predict the exact medical charges in USD.

Both classical ML models and a neural network will be implemented and compared.

## Dataset
Kaggle: https://www.kaggle.com/datasets/mirichoi0218/insurance?resource=download  
License: **CC0 Public Domain**  
See [data/README.md](data/README.md) for download steps.

## Project Structure
- `src/` – source code (data, features, training, evaluation)
- `data/README.md` – dataset download instructions
- `notebooks/` – exploratory analysis (optional)
- `models/` – saved model artifacts (optional)
- `requirements.txt` – dependencies
- `.gitignore` – excludes raw data and MLflow runs (`mlruns/`)

## Setup
```bash
pip install -r requirements.txt
