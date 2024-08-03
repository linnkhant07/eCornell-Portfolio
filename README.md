# Global Happiness Prediction Model

## Overview

This project aims to predict the happiness levels of countries based on various socio-economic features using a Linear Regression model. The primary goal is to understand how different factors like GDP, social support, health, and other metrics impact the overall happiness score (Life Ladder) of a country. The model can be used to simulate different scenarios and help policymakers, NGOs, and researchers in making data-driven decisions to enhance global well-being.

## Dataset

The dataset used for this project includes the following features:
- `Life Ladder`: Happiness score or life ladder index (target variable).
- `Log GDP per capita`: Logarithm of GDP per capita.
- `Social support`: Social support score.
- `Healthy life expectancy at birth`: Average number of years a newborn is expected to live in good health.
- `Freedom to make life choices`: Freedom score.
- `Generosity`: Generosity score.
- `Perceptions of corruption`: Perceived corruption score.
- `Positive affect`: Positive emotional affect score.
- `Negative affect`: Negative emotional affect score.
- `Democratic Quality`: Quality of democracy score.
- `Delivery Quality`: Quality of government service delivery.
- `Standard deviation of ladder by country-year`: Standard deviation of the happiness score.
- `Standard deviation/Mean of ladder by country-year`: Ratio of standard deviation to mean.
- `GINI index (World Bank estimate), average 2000-15`: GINI index for income inequality.

## Getting Started

### Prerequisites

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

You can install the necessary packages using pip:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

### Running the Model

1. **Data Preparation**: Load and preprocess the data. Handle missing values and prepare features for modeling.

2. **Model Training**: Train a Linear Regression model on the prepared data. Optionally, you can also train Ridge and Lasso Regression models to compare their performance.

3. **Model Evaluation**: Evaluate the model using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R2). Perform cross-validation to assess the model’s performance.

4. **Prediction**: Use the trained model to predict happiness scores for new data or simulated scenarios.

## Usage

To use the model, follow these steps:

1. **Prepare Your Data**: Ensure your dataset is in the correct format and contains the necessary features and target variable as described. Place your dataset file in the appropriate directory.

2. **Run the Model**: Execute the provided Python script or Jupyter notebook. This will load the dataset, preprocess the data, train the model, and evaluate its performance.

3. **Predict New Data**: After training, use the model to make predictions on new or simulated data. Modify the `X_new` variable in the code to include the new data features and use the trained model to predict happiness scores.

## Contributing
Feel free to fork this repository, create a pull request, or open an issue if you have suggestions or improvements.


## License
This project is licensed under the MIT License - see the LICENSE file for details.
