# Simple House Price Prediction

## Project Overview
This project predicts house prices using a Linear Regression model and the California Housing dataset. It demonstrates a basic supervised machine learning regression workflow.

## Objective
To train a Linear Regression model, predict house values, and evaluate its performance using regression metrics.

## Dataset
- **Name:** California Housing Dataset
- **Source:** [Scikit-learn California Housing Dataset](https://scikit-learn.org/stable/datasets/real_world.html#california-housing-dataset)
- **Records:** 20,640
- **Features:** 8 input features and 1 target column

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Input and Target
- **Input feature:** `MedInc` (median income)
- **Target variable:** `MedHouseVal` (median house value in units of $100,000)

## Methodology
1. Load and inspect the dataset.
2. Check missing values and duplicate records.
3. Select the input feature and target variable.
4. Visualize the relationship between income and house value.
5. Split the data into 80% training and 20% testing sets.
6. Train a Linear Regression model.
7. Generate predictions and evaluate performance.
8. Visualize actual versus predicted values.
9. Predict a new house value.

## Model Results
- **Intercept:** 0.4446
- **Coefficient:** 0.4193
- **MAE:** 0.6299
- **MSE:** 0.7091
- **RMSE:** 0.8421
- **R² Score:** 0.4589

## Example Prediction
For a median income feature of 5.0, the model predicts a house value of approximately $254,128.98.

## Limitations
The model uses only one input feature. Actual house values also depend on location, house characteristics, and other factors. The predictions are estimates, not guaranteed market prices.

## How to Run
1. Open the notebook in Google Colab.
2. Run the cells from top to bottom.
3. View the predictions, evaluation metrics, and visualizations.

## Conclusion
This project demonstrates how Linear Regression can be used for house price prediction and how regression metrics help evaluate model performance.
