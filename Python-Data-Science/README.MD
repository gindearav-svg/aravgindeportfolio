# NCAA Team Success Prediction

An end-to-end data analytics and machine learning project analyzing 4,249 NCAA
basketball team records from 2013–2025. Working with a partner, I developed
predictive models to identify which team performance metrics most strongly
predict total wins.

## Objective

Determine whether team efficiency and performance metrics can reliably predict
a team's total wins and identify the factors most strongly associated with success.

# Dataset

- 4,249 NCAA team records
- 24 features
- 2013–2025 seasons
- Source: Kaggle

## Workflow

### Data Preparation
- Cleaned missing values
- Evaluated outliers using the IQR method
- Prepared categorical and numerical features

### Exploratory Data Analysis
- Univariate distributions
- Bivariate relationships
- Correlation analysis
- Multivariate analysis
- Conference-level comparisons

### Machine Learning
Built and compared two regression models:

- Linear Regression
- Random Forest Regression

Used Scikit-Learn's `ColumnTransformer`, `OneHotEncoder`, and `StandardScaler`
for feature preprocessing.

### Model Evaluation

Models were evaluated using:

- R²
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

Random Forest hyperparameters were also tuned to evaluate whether a more complex
model could improve predictive performance.

## Key Findings

- Linear Regression achieved an R² of approximately 0.97 and outperformed the
  Random Forest model.
- Adjusted offensive and defensive efficiency were among the strongest
  predictors of total wins.
- The results suggest that a relatively simple linear model can capture much
  of the relationship between team efficiency and season success.

## Business Application

The analysis demonstrates how predictive models can be used to identify the
performance metrics most associated with success and potentially inform resource
allocation and performance improvement decisions.
