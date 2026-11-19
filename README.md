# Meta-Analysis-XAI-Shading
A Data-Driven Meta-Analysis of External Shading Performance on Daylight, Glare, and Energy: An Explainable Machine Learning Approach Across 5 Major Climates
# Meta-Analysis of External Shading Performance (XAI Approach)

This repository contains the Python code used for the data analysis and Explainable Machine Learning (XAI) modeling in the following manuscript:

**Title:** A Data-Driven Meta-Analysis of External Shading Performance on Daylight, Glare, and Energy: An Explainable Machine Learning Approach Across 5 Major Climates

## Overview
This project integrates a unified database of 178 configurations from 6 empirical studies. The analysis is divided into two main phases:
1. **Statistical Analysis:** One-way ANOVA and Pearson Correlation matrices.
2. **Machine Learning & Interpretability:** 
   - A Ridge Regression baseline for predicting Energy Use Intensity (EUI).
   - An XGBoost model trained on a larger dataset for Annual Sunlight Exposure (ASE).
   - **SHAP (SHapley Additive exPlanations)** analysis to interpret the non-linear feature importance.

## Repository Structure
- `Meta_Analysis_Code.ipynb`: The main Google Colab notebook containing the data extraction, statistical analysis, machine learning models, and SHAP visualizations.
- `final_database.csv`: The unified database (178 rows) extracted from 6 peer-reviewed studies.

## Requirements
The code is written in Python 3 and requires the following libraries:
`pandas`, `numpy`, `scipy`, `matplotlib`, `seaborn`, `scikit-learn`, `xgboost`, `shap`.

## Usage
You can open the `.ipynb` file directly in Google Colab. Make sure to upload the `final_database.csv` to the Colab environment before running the cells.
