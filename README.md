# Logistic-regrssion-Rock_vs_Mine
# README

## Project Overview

This project aims to classify objects as either "Rock" or "Mine" using sonar signals. The classification model is built using logistic regression and trained on the sonar dataset.

## Files in the Repository

- **`Rock_vs_Mine.ipynb`**: A Jupyter notebook that contains the data processing, model training, and evaluation steps.
- **`sonar.all-data.csv`**: The dataset used in this project, consisting of sonar signals with 60 features and a target label indicating the object's type ("Rock" or "Mine").

## Data

The dataset (`sonar.all-data.csv`) contains 208 samples and 61 columns:
- **Columns 0-59**: Sonar signal features, representing amplitude values at different frequencies.
- **Column 60**: The target label, where "R" indicates a Rock and "M" indicates a Mine.

## Workflow

1. **Data Loading**: The sonar dataset is loaded into a Pandas DataFrame without headers.
2. **Exploratory Data Analysis**:
   - The first few rows of the dataset are previewed.
   - The dataset's shape is checked.
   - Summary statistics are computed.
   - The distribution of the target labels is examined.
   - The mean values of the features grouped by target label are calculated.
3. **Data Preparation**:
   - Features (`X`) and target labels (`y`) are separated.
   - The dataset is split into training and testing sets with a 90/10 ratio.
4. **Model Training**:
   - A logistic regression model is initialized and trained on the training data.
5. **Model Evaluation**:
   - The model's accuracy is calculated on both the training and testing sets.
6. **Prediction**:
   - The model is used to make a single prediction based on a sample input, determining whether the object is a "Rock" or a "Mine."

## Usage

To use the notebook:
1. Load the `Rock_vs_Mine.ipynb` notebook in Jupyter.
2. Run each cell sequentially to process the data, train the model, and evaluate its performance.
3. Modify the `input_data` in the last cell to test the model with new data points.

---
