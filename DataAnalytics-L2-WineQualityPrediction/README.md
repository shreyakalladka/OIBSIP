# Wine Quality Classification

## Overview

This project focuses on predicting the quality of red wine using machine learning techniques. The Wine Quality dataset is explored, preprocessed, and used to train three different classification models.

The wine quality scores are grouped into three categories, and the models are evaluated using accuracy, classification reports, and confusion matrices.

## Objectives

- Perform Exploratory Data Analysis (EDA) on the wine quality dataset
- Analyze feature distributions and correlations
- Handle wine quality class imbalance
- Create quality groups for classification
- Train multiple machine learning classifiers
- Compare model performance using evaluation metrics

## Dataset

The project uses the **Wine Quality Red Wine Dataset** (`winequality-red.csv`).

The dataset contains physicochemical properties of red wine along with a `quality` score.

### Features

- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Free sulfur dioxide
- Total sulfur dioxide
- Density
- pH
- Sulphates
- Alcohol

### Target

The original `quality` score is converted into three groups:

- **0 – Low Quality:** Quality ≤ 4
- **1 – Medium Quality:** Quality 5–6
- **2 – High Quality:** Quality > 6

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab / Jupyter Notebook

## Project Workflow

### 1. Import Libraries

The required Python libraries are imported for data analysis, visualization, preprocessing, model training, and evaluation.

### 2. Exploratory Data Analysis

EDA is performed using:

- Distribution/histogram plots
- Correlation heatmap
- Class distribution visualization

The correlation heatmap helps identify relationships between the physicochemical properties of wine.

### 3. Class Imbalance Analysis

The distribution of the original wine quality scores is analyzed using value counts and a count plot.

### 4. Feature Engineering

The original wine quality scores are grouped into three classes:

```text
Quality ≤ 4   → 0 (Low)
Quality 5–6   → 1 (Medium)
Quality > 6   → 2 (High)
