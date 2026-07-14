# Multiple Linear Regression House Price Prediction

This project demonstrates the implementation of Multiple Linear Regression using Python and Scikit-learn to predict house prices using both numerical and categorical features.

It is part of my Machine Learning learning journey and focuses on understanding how multiple variables contribute to predictions while building complete machine learning workflows.

## Project Overview

The objective of this project is to build a regression model capable of predicting house prices based on several independent variables.

The project covers the entire workflow, including data exploration, preprocessing, model training, evaluation, visualization, and predicting unseen samples.

## Dataset

### Numerical Features

* Median Income
* House Age
* Average Rooms
* Average Occupancy

### Categorical Feature

* Region (Urban, Suburban, Rural)

### Target Variable

* House Price

## Machine Learning Workflow

1. Import Libraries
2. Load the Dataset
3. Perform Exploratory Data Analysis (EDA)
4. Visualize the Data
5. Analyze Feature Correlations
6. Split Features and Target
7. Perform Train-Test Split
8. Build a Data Preprocessing Pipeline
9. Train the Multiple Linear Regression Model
10. Evaluate the Model
11. Visualize Predictions
12. Predict New Samples

## Multiple Linear Regression

Multiple Linear Regression extends Simple Linear Regression by using multiple input variables.

The model follows the equation:

y = w₀ + w₁x₁ + w₂x₂ + ... + wₙxₙ

Where:

* y = Predicted value
* w₀ = Intercept (bias)
* w₁ ... wₙ = Feature coefficients
* x₁ ... xₙ = Input features

Each feature contributes to the final prediction according to its learned coefficient.

## Data Preprocessing

This project uses Scikit-learn's `ColumnTransformer` and `Pipeline` to build an end-to-end machine learning workflow.

### Numerical Processing

* StandardScaler

### Categorical Processing

* OneHotEncoder

### Pipeline Components

* ColumnTransformer
* Pipeline
* LinearRegression

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

## Model Evaluation

The model was evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* R² Score

The notebook also includes:

* Correlation Heatmap
* Distribution Plots
* Actual vs Predicted Visualization
* Predictions on New Samples

## Results and Insights

### Results

* The model achieved a strong R² score and successfully captured the relationship between the input features and house prices.
* Predictions closely matched the actual values in the test set.
* The preprocessing pipeline handled both numerical and categorical features efficiently.

### Insights

* Multiple features contribute differently to the final prediction.
* Categorical variables must be encoded before training regression models.
* Combining preprocessing and model training in a Scikit-learn Pipeline improves code organization and reproducibility.
* Data preprocessing plays an important role in building reliable machine learning models.

## Key Learning Outcomes

Through this project, I practiced:

* Multiple Linear Regression
* Data preprocessing
* Handling categorical variables
* One-Hot Encoding
* Feature Scaling
* Scikit-learn Pipelines
* Regression evaluation metrics
* Building end-to-end machine learning workflows

## Repository Structure

```text
.
├── multiple_linear_regression.ipynb
├── README.md
└── dataset.csv
```

## Future Improvements

* Compare Multiple Linear Regression with other regression algorithms.
* Apply feature engineering techniques.
* Experiment with Ridge and Lasso Regression.
* Explore Cross Validation techniques.

## Conclusion

This project strengthened my understanding of how machine learning models use multiple variables to make predictions. It also introduced me to building scalable and reusable workflows using Scikit-learn Pipelines.

## Author

This repository is part of my Machine Learning portfolio. I am continuously building hands-on projects to strengthen my understanding of AI, Data Science, and Machine Learning through practical implementation.
