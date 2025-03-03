# Wine Quality Prediction

This project aims to predict the quality of wine based on various physicochemical attributes using machine learning techniques. The dataset contains information about different types of wines and their respective quality ratings. This project applies different machine learning algorithms to predict the quality score of wine, which is provided on a scale of 0 to 10.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Dependencies](#dependencies)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
  - [Preprocessing and Exploration](#preprocessing-and-exploration)
  - [Model Training](#model-training)
  - [Model Evaluation](#model-evaluation)
  - [Wine Quality Prediction](#wine-quality-prediction)
- [Model Evaluation](#model-evaluation)
- [Results](#results)
- [License](#license)

## Project Overview

Wine quality is determined by a variety of factors including acidity, sugar content, pH level, and alcohol content, among others. This dataset provides physicochemical data about wines, and the task is to predict the quality of the wine based on these features. The project applies various machine learning algorithms such as:
- Linear Regression
- Random Forest
- Support Vector Machines (SVM)
- Decision Trees
- XGBoost (Optional for better performance)

The ultimate goal is to develop a model that can accurately predict the quality of wine based on the given features.

## Dataset

The dataset used in this project is publicly available and can be found at the [UCI Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/Wine+Quality).

### Dataset Details
- **Red Wine**: 1599 instances
- **White Wine**: 4898 instances

The dataset consists of 12 features:
- **Fixed acidity**: Tartaric acid content (g/dm³)
- **Volatile acidity**: Acetic acid content (g/dm³)
- **Citric acid**: Citric acid content (g/dm³)
- **Residual sugar**: Sugar content after fermentation (g/dm³)
- **Chlorides**: Chloride content (g/dm³)
- **Free sulfur dioxide**: Free SO2 (mg/dm³)
- **Total sulfur dioxide**: Total SO2 (mg/dm³)
- **Density**: Density of the wine (g/cm³)
- **pH**: Acidity level of the wine
- **Sulphates**: Sulphate content (g/dm³)
- **Alcohol**: Alcohol content (percentage)

### Quality
The quality score of the wine is given on a scale from 0 to 10, where higher values indicate better wine quality.

## Dependencies

Before running the code, make sure to install the following libraries:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn xgboost
