COMP331 Final Project — Data Quality & Bias Analysis in Credit Card Fraud Data

This repository contains my COMP/STAT 331 Final Project (Option 2: Data Mining Quality & Bias Analysis) using the Credit Card Fraud dataset from Kaggle.

Project Overview

The goal is to analyze data quality and bias issues in the dataset, focusing on:

Sampling bias & representativeness

Extreme class imbalance (99.83% legitimate vs 0.17% fraud)

Labeling validity and fairness limitations

All analysis follows methods from Weeks 10–11 (CRISP-DM, data quality dimensions, bias & fairness).

Repository Structure
COMP331-Final-Project/
├── README.md
├── notebooks/
│   └── credit_card_fraud_analysis.ipynb
├── data/
│   └── creditcard.csv
├── results/
│   ├── *.png, *.csv, summary_notes.md
└── report/
    └── Stat 331 Final Report Joshua Hira.pdf

Dataset

Download from Kaggle:
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

Place creditcard.csv into the data/ folder.

How to Run

Install Python dependencies:

pip install pandas numpy matplotlib


Open the notebook:

notebooks/credit_card_fraud_analysis.ipynb


Run all cells.
All charts/tables will be saved into the results/ folder.

Author

JOSHUA HIRA
University of the Fraser Valley — COMP/STAT 331