# Airline-Revenue

## Project Overview
    This predicts the annual revenue generated in airlines based on route performance data 
that include average fare , distance travelled , number of passengers , region and route
specifically. It also analyse correlation among route characteristics that influence the
airline revenue.

## Objectives
1. Exploring the dataset thoroughly
2. Clean and preprocess data 
3. Perform Exploratory Data Analysis ( EDA )
4. Build a Linear Regression Model 
5. Evaluate the model using appropriate metrics
6. Analysing the model performance and insights

## Dataset
-> Number of observation :
-> Number of features
-> Target vriable : Annual revenue in USD
-> Features include :
    - Year
    - Route
    - Origin 
    - Destination
    - Distance ( in km)
    - Region
    - Airlines
    - Annual Passengers ( in millions )
    - Average fare ( in USD )
    - weekly frequency
    - Annual revenue ( in millions USD ) 

## Technologies used
- Python
- Jupyter notebook
- Numpy 
- Pandas
- Matplotlib
- Scipy
- Scikit - learn

## Project Workflow
1. import libraries
2. Load dataset and profiling
3. Data cleaning and Preprocessing
4. Exploratory Data Analysis
5. Train Test split
6. Model training and prediction
7. Model evaluation
8. Visualization of results

## Metrics for model evaluation
1. Mean Absolute Error ( MAE )
2. Mean Squared Error ( MSE )
3. Root Mean Squared Error ( RMSE )
4. r2 score

## Results
    This linear regression model archieved an r2 score of 0.8511, 
this indicates approximately 85% of the variance in airline revenue
hence there much relationship captured between target variables and 
predicted variables.

    The Mean Absolute Error (MAE) is 97.46 which inicates the difference 
in from the actual revenue as 97.5 millions USD and using the same target variables,the
Root Mean Squared Error (RMSE) of 126.66 million USD  shows the model has errors but still
in general the model managed to maintain good predictive performance.

## Repository structure
AIRLINE-REVENUE/
    .gitignore
    LICENSE
    README.md
    requirement.txt
    revenue_prediction.ipynb
    route_performance.csv


## Future improvement
1. Building an interactive dashboard
2. Comparing this linear regression algorithm with other advanced methods
3. Collecting more route data for better generalization

## Author
Eliudi Elphace Tonda