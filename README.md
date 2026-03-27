# training-materials

Companion materials for the Intro to Data Science training session.

## Contents

- **new-starter-training.ipynb** — A guided notebook that walks through building a binary
  classification model on tabular data, from initial exploration through to a
  Kaggle submission. Designed to be uploaded to Kaggle and run against the
  [Predicting Loan Payback](https://www.kaggle.com/competitions/playground-series-s5e11)
  competition (Playground Series S5E11).

## What the notebook covers

1. Data loading and exploratory analysis
2. Visualisation of feature distributions and correlations
3. Building a rules-based baseline model
4. Categorical encoding and feature scaling
5. Train/test splitting and evaluation metric selection
6. Training a Logistic Regression model
7. Training a LightGBM model
8. Hyperparameter tuning with cross-validation
9. Training a final model and generating a competition submission file

## Usage

1. Go to the [competition page](https://www.kaggle.com/competitions/playground-series-s5e11) and join the competition
2. Create a new Kaggle Notebook attached to the competition
3. Upload `new-starter-training.ipynb` and run through the cells, filling in the `# TODO` sections as you go

## Requirements

If running locally rather than on Kaggle, you'll need:
```
pip install pandas numpy matplotlib seaborn scikit-learn lightgbm
```
