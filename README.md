# GDP Prediction Model

## Overview
The GDP Prediction model predicts the Gross Domestic Product (GDP) per capita of countries based on various socio-economic indicators. The model uses **Linear Regression** and **Random Forest Regression** techniques to predict GDP per capita for different countries and years. Several visualizations are also included to help better understand the data and predictions.

## Abstract
This project predicts the GDP per capita using historical data that includes various socio-economic factors such as life expectancy, mortality rates, alcohol consumption, education levels, and more. The models used for prediction are **Linear Regression** and **Random Forest Regression**. Various visualizations, including animated scatter plots, faceted scatter plots, choropleth maps, and others, are created to analyze and interpret the data.

## Methodology
1. **Data Cleaning**: Rows with missing or irrelevant values were dropped using the `drop()` method.
2. **Data Preprocessing**: The dataset was split into features (`X`) and target (`y`). The data was then divided into training and testing sets using `train_test_split()`. The features were normalized using **StandardScaler**.
3. **Model Training**: Both **Linear Regression** and **Random Forest Regression** models were used to predict GDP per capita.
4. **Model Evaluation**: The models were evaluated using the following metrics:
    - RMSE (Root Mean Squared Error)
    - MSE (Mean Squared Error)
    - MAE (Mean Absolute Error)
    - R² (R-squared)

## Results

The **Linear Regression** model performed well, achieving an RMSE of 3.159 on training data and 3.094 on testing data, with an R² of 0.907 and 0.905, respectively, indicating strong predictive accuracy. In comparison, the **Random Forest Regression** model showed excellent performance on the training data with an R² of 0.952 but had a reduced performance on testing data (R² of 0.729), suggesting potential overfitting.**

## Visualizations

Visualizations included an **Animated Scatter Plot**, **Faceted Scatter Plot**, **Violin Plot**, and **Bar Charts** to analyze the relationship between GDP per capita and other factors. The **Choropleth Map** and **Scatter Geo** visualizations provided geographical insights, while **Pie Charts** and **Box Plots** showcased distributions. The **3D Scatter Plot** helped visualize multiple features' impact on GDP.

## Conclusion
The project successfully builds a predictive model for GDP per capita using both **Linear Regression** and **Random Forest Regression**. The **Random Forest** model performed well on training data but had a larger error on testing data. In contrast, the **Linear Regression** model showed consistent and reliable results. The visualizations provided useful insights into the factors that influence GDP per capita.

## Future Work
- Explore additional features or factors that could improve prediction accuracy.
- Experiment with other machine learning models such as **Gradient Boosting** or **XGBoost** to further enhance prediction performance.
- Fine-tune the **Random Forest** model to improve testing data performance.
