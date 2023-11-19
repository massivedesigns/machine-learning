<img width="1256" alt="banner1" src="https://github.com/massivedesigns/images-in-readme/assets/42479736/ca981244-6b59-4f81-bf5c-88ad93323883">

# Cancer Mortality Rate Prediction

## Overview

This project focuses on predicting cancer mortality rates using machine learning techniques. The dataset includes various features related to cancer and demographic information.

## Files and Structure

- `Final Cancer data Regression.ipynb`: Jupyter Notebook containing the main code for data preprocessing, analysis, and modeling.
- `README.md`: This file.
- `cancer_data.csv`: Dataset file containing cancer and demographic information.
- `prerequisites.txt.txt`: List of required libraries for the project.

## Libraries Used

- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Statsmodels

## Instructions

1. Install the required libraries using `pip install -r prerequisites.txt`.
2. Open and run the `Final Cancer data Regression.ipynb` notebook to execute the code sequentially.

## Data Preprocessing

- **Handling Missing Values**: Missing values are handled appropriately.
- **Normalization**: Certain features are normalized to ensure consistent scales.
- **Skewness Correction**: Skewed features are transformed to improve model performance.
- **Train-Test Split**: The dataset is split into training and testing sets for model evaluation.

## Skewness Transformation

- `avgDeathsPerYear`, `avgAnnCount`, `popEst2015`, `PctBachDeg25_Over`, `PctOtherRace`, and `BirthRate` are log-transformed or squared to address skewness.

## Model Training and Evaluation

- **Linear Regression**: A linear regression model is used for predicting cancer mortality rates.
- **R-squared Score**: The model achieves an R-squared score of approximately 0.70.
- **RMSE Score**: The RMSE score for model evaluation is approximately 13.51.

## Results

- Scatterplot: Visualization of predicted vs. actual cancer mortality rates.

## Author

Onyedika Aralu 
