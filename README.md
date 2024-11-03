# Star Classification Using Supervised Machine Learning Models

This project focuses on classifying stars into various types using supervised machine learning algorithms based on their physical and astronomical attributes. By comparing multiple models, this project seeks to find the best-performing algorithm for accurate star type classification.

## Project Overview

The dataset used for this project contains star attributes such as temperature, luminosity, radius, and color, which are critical for analyzing stellar characteristics. Four supervised machine learning models were selected and compared to determine their effectiveness in classifying stars accurately.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Methodology](#methodology)
  - [Data Preprocessing](#data-preprocessing)
  - [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
  - [Model Selection](#model-selection)
  - [Model Evaluation](#model-evaluation)
- [Results](#results)
- [Conclusion](#conclusion)

## Introduction

With advancements in machine learning, we can leverage data to classify celestial bodies and better understand their evolution. This project employs supervised learning techniques, including K-Nearest Neighbors, Decision Tree, Random Forest, and Logistic Regression, to classify stars based on various features.

## Dataset

The dataset is sourced from [Kaggle](https://www.kaggle.com/datasets/deepu1109/star-dataset) and contains information on star attributes, such as:
- **Temperature (K)**: Surface temperature in Kelvin
- **Luminosity (L/Lo)**: Luminosity relative to the Sun
- **Radius (R/Ro)**: Radius relative to the Sun
- **Absolute Magnitude (Mv)**: Intrinsic brightness
- **Star Type**: Target variable for classification
- **Star Color** and **Spectral Class**: Features related to star classification

## Methodology

### Data Preprocessing
- **Handling Missing Data**: Checked for and addressed any missing values.
- **Data Encoding**: Used Label Encoding for categorical features to transform them into numeric format.
- **Feature Engineering**: Analyzed feature correlations and removed low-correlated features to improve model accuracy.
- **Data Splitting**: Split data into training and testing sets in a 70-30 ratio for model validation.

### Exploratory Data Analysis (EDA)
- Visualized relationships between features, examining correlations and distributions.
- Plotted scatter and bar charts to understand the target distribution and feature interactions.

### Model Selection
Four models were evaluated for their suitability for the classification task:
1. **K-Nearest Neighbors (KNN)**
2. **Decision Tree Classifier**
3. **Random Forest Classifier**
4. **Logistic Regression**

### Model Evaluation
The models were assessed based on accuracy, precision, recall, and F1-score. Cross-validation was used to improve model reliability and reduce overfitting.

## Results

- **Decision Tree**: Highest accuracy at approximately 95%.
- **Random Forest**: Close performance with an accuracy of around 94%.
- **Logistic Regression**: Moderate performance with 80% accuracy.
- **KNN**: Lowest accuracy at around 60%.

The Decision Tree and Random Forest models performed best, indicating their robustness for this dataset.

## Conclusion

This project highlights the effectiveness of ensemble and tree-based methods in classifying stars. The Decision Tree and Random Forest models were the most suitable for this task, accurately capturing complex relationships among star attributes. The findings could serve as a foundation for further stellar classification research and machine learning applications in astronomy.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/star-classification-ml.git
   ```
