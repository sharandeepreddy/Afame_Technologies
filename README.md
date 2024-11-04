# Afame_Technologies
# Sales Prediction Project

## Project Overview

This project involves predicting product sales based on advertising expenditure across different media channels (TV, Radio, and Newspaper). The objective is to help businesses make data-driven decisions regarding advertising budgets and optimize sales. By leveraging machine learning techniques in Python, this project forecasts future sales, aiming to maximize potential sales through informed advertising strategies.
## Data Description

The dataset used in this project includes the following features:

- **TV**: Advertising spending on TV (in thousands of dollars).
- **Radio**: Advertising spending on Radio (in thousands of dollars).
- **Newspaper**: Advertising spending on Newspaper (in thousands of dollars).
- **Sales**: Target variable representing product sales (in thousands of units).

## Project Structure

```
├── Sales.csv               # Dataset used for the project
├── sales_prediction.py      # Main script with all code
└── README.md               # Project documentation
```
## Usage

1. **Load and Explore the Data**: 
   - The script `sales_prediction.py` loads the data, performs exploratory data analysis (EDA), and visualizes the relationships between advertising expenditure and sales.
   
2. **Model Training and Evaluation**:
   - The Linear Regression model is trained on the data, and predictions are made for the test set.
   - Evaluation metrics (Mean Squared Error, Mean Absolute Error, Root Mean Squared Error, and R-squared) are computed to assess model performance.
   
3. **Running the Project**:
   - Run the script with the following command:
     ```bash
     python sales_prediction.py
     ```

4. **Optional Model**:
   - The script also provides the option to run a Random Forest Regressor to compare results with the Linear Regression model.

## Results

- **Model Performance**: The primary model (Linear Regression) provides an initial performance benchmark. Evaluation metrics indicate the accuracy and reliability of predictions.
- **Insights**: Based on correlation analysis, TV and Radio advertising tend to have a stronger impact on sales than Newspaper advertising, suggesting that budget adjustments toward these platforms may optimize sales potential.

## Future Enhancements

- **Audience Segmentation**: Integrating customer demographics to improve target audience segmentation and refine predictions.
- **Model Tuning**: Use hyperparameter tuning (e.g., GridSearchCV) to optimize model performance.
- **Additional Data**: Incorporate other factors, such as seasonal trends and market data, to improve prediction accuracy.
