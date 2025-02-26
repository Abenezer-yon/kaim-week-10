## week 10


## Task 1: Defining the Data Analysis Workflow and Understanding the Model and Data
Defining the Data Analysis Workflow
Define Project Objectives
Clearly articulate the goals of the analysis, such as forecasting Brent oil prices or understanding price volatility.
Data Collection
Gather historical Brent oil prices from reliable sources (e.g., financial databases, government reports).
Ensure data covers a sufficient time span to capture trends and seasonal patterns.
Data Preprocessing
Clean the data: Handle missing values, outliers, and inconsistencies.
Normalize or transform data if necessary (e.g., log transformation for stabilizing variance).
Exploratory Data Analysis (EDA)
Visualize data trends, seasonal patterns, and anomalies using plots (e.g., time series plots, histograms).
Calculate summary statistics to understand the distribution of prices.
Model Selection and Development
Select appropriate time series models (e.g., ARIMA, GARCH) based on the nature of the data.
Define model inputs (e.g., lagged values, moving averages) and parameters.
Model Training and Validation
Split data into training and test sets.
Fit the chosen models to the training data and validate using the test set.
Assess model performance using metrics like Mean Absolute Error (MAE) or Root Mean Squared Error (RMSE).
Make Predictions
Use the validated model to forecast future Brent oil prices.
Generate confidence intervals for predictions to quantify uncertainty.
Communicate Results
Prepare reports and visualizations for stakeholders.
Identify key findings and insights derived from the analysis.
Understanding the Model and Data
Key References and Concepts
Review literature on time series analysis and specifically on Brent oil prices.
Familiarize with economic factors affecting oil prices (e.g., supply-demand dynamics, geopolitical events).
## Time Series Models
ARIMA (AutoRegressive Integrated Moving Average):
Used for forecasting stationary time series data.
Captures trends and seasonality through differencing and lagged terms.
GARCH (Generalized Autoregressive Conditional Heteroskedasticity):
Models volatility in time series data.
Useful for understanding and predicting periods of high and low volatility in oil prices.
Data Generation Processes
Understand external factors influencing Brent oil prices, such as production levels, market demand, and global economic conditions.
Recognize that time series models like ARIMA assume that future prices depend on past values and that GARCH models account for changing volatility.
Expected Outputs and Limitations
Outputs may include forecasts of future prices, confidence intervals, and volatility estimates.
Limitations include model assumptions (e.g., linearity, stationarity) and the impact of unforeseen external events (e.g., market shocks).
Communication Channels
Utilize reports, dashboards, and presentations as main media channels for communicating results.
Ensure formats are accessible and tailored for different stakeholders (e.g., technical details for analysts, high-level insights for executives).
Assumptions and Limitations
Assumptions:
Historical price patterns will persist into the future.
The chosen models adequately capture the underlying data processes.
Limitations:
Models may not account for sudden market changes or extreme events.
Forecasts have inherent uncertainty, which must be communicated to stakeholders clearly.