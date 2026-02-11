# NLP Disaster Tweet Classification

## Portfolio Snapshot
- Score: **7.8 / 10**
- Verdict: **Keep**
- Category: NLP classification

## Project Summary
A Kaggle disaster-tweet classifier that compares a TF-IDF baseline against neural sequence models and submits predictions.

## What It Does
- Cleans and explores tweet dataset
- Trains TF-IDF + Logistic Regression baseline
- Trains BiLSTM with GloVe embeddings
- Compares LSTM, GRU, and BiLSTM variants
- Generates competition submission file

## Key Results
- Baseline TF-IDF + Logistic Regression accuracy: **0.8267**
- Baseline TF-IDF + Logistic Regression AUC: **0.8682**
- BiLSTM validation accuracy: **0.8181**
- BiLSTM validation AUC: **0.8847**

## Tech Stack
- Python, TensorFlow/Keras
- scikit-learn, NLTK
- pandas, matplotlib, seaborn

## Repository Contents
- `Kegel_NLP_Disaster.ipynb`: experiments and evaluation
- `best_model.h5`, `best_model.keras`: saved model artifacts
- `submission.csv`: output predictions

## Run Locally
1. Place Kaggle CSVs where notebook expects.
2. Install dependencies.
3. Run `Kegel_NLP_Disaster.ipynb`.

## Why This Scores Here
- Good experiment flow and clear baseline-vs-deep-model comparison
- Reproducibility and packaging can be improved beyond notebook usage

## Improvement Priorities
- Add standalone training and inference scripts
- Add config-driven experiment setup
- Add concise error-analysis section
