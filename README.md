# Unemployment Analysis in India (2000–2023)

## Project Overview
This project explores unemployment trends in India from 2000 to 2023 using Exploratory Data Analysis (EDA), statistical visualization, and a Multilayer Perceptron (MLP) regression model.

## Objectives
- Analyze unemployment trends over time.
- Explore relationships between unemployment and economic indicators.
- Identify distributions and potential outliers.
- Develop and evaluate an MLP regression model.

## Dataset
The dataset contains 24 annual observations and 17 columns covering unemployment and economic indicators. The data were collected from World Bank indicators.

## Tools and Technologies
- Python
- Google Colab
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- TensorFlow and Keras

## Methodology
1. Data collection and quality checks
2. Exploratory data analysis and visualization
3. Chronological training, validation, and test split
4. Feature standardization
5. MLP regression model development
6. Model evaluation and permutation feature importance

## Model Results
The simpler MLP achieved:
- **MAE:** 0.7277
- **RMSE:** 0.8484
- **R²:** 0.1615

The test set contains only three observations, so the results are preliminary and should not be considered evidence of reliable forecasting performance.

## Repository Contents
- `Unemployment_Analysis_EDA.ipynb` — Project notebook

## Limitations
The dataset contains only 24 annual observations. The small validation and test sets limit the reliability and generalizability of the model evaluation.

## Future Scope
Future work can include additional observations, more economic indicators, comparisons with statistical baselines, and more robust time-series validation.
