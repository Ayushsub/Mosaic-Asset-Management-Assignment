**#Analysis of Sectoral Indices and Macroeconomic Variables**

**###Objective**
The goal of this project is to analyze the relationship between various Indian sectoral indices and macroeconomic variables
and also to evaluate the performance of sectoral indices in comparison to Market Indices.

**###Data Sources**
####Broad Market Indices: NIFTY 50 (^NSEI), NIFTY Midcap 50 (^NSEMDCP50)

####Sectoral Indices:
NIFTY Auto (^CNXAUTO)
NIFTY Financial Services (NIFTY_FIN_SERVICE.NS)
NIFTY Bank (^NSEBANK)
NIFTY FMCG (^CNXFMCG)
NIFTY IT (^CNXIT)
NIFTY Media (^CNXMEDIA)
NIFTY Metal (^CNXMETAL)
NIFTY PSU Bank (^CNXPSUBANK)
NIFTY Realty (^CNXREALTY)
NIFTY Energy (^CNXENERGY)

####Macroeconomic Data: 
Includes various economic indicators such as inflation rates, GDP growth rates, interest rates, etc., stored in Macro_indicators.csv.

**###Methodology**
####Data Download and Preparation
Download Historical Data: Use yfinance to download historical data for each index.
Clean and Align Data: Ensure all datasets have a common date range and handle missing values.
Load Macroeconomic Data: Read and process the macroeconomic data, resampling to match the frequency of the sectoral data.

####Exploratory Data Analysis
Correlation Analysis: Calculate and plot the correlation matrix between sectoral indices and macroeconomic variables.
Time Series Plots: Plot the historical data for sectoral indices and macroeconomic variables to visualize trends.

**###Modeling**
####Models Used:
Random Forest Regressor
Linear Regression
Support Vector Regressor (SVR)
K-Nearest Neighbors Regressor (KNeighbors)
XGBoost Regressor

####Training and Evaluation: 
Train each model on the data and evaluate performance using metrics such as RMSE, MAE, and R² score.

**###Performance Comparison**
Compare the performance of sectoral indices against the NIFTY 50 index using the different models to identify which sectors outperform the broad market index.

**###Results**
####Correlation Matrix
The correlation matrix between sectoral indices and macroeconomic variables is visualized using a heatmap.

####Time Series Plots

####Sectoral Indices

####Macroeconomic Variables

####Sectoral Performance Comparison
The sectoral indices are compared against the NIFTY 50 index to identify which sectors outperform the broad market.

**###Conclusion**
The results show that certain sectoral indices have stronger correlations with specific macroeconomic variables.
The performance comparison indicates which sectors outperform the NIFTY 50 index under different models.

**###Results and Performance**
The detailed performance metrics for each model and index are saved in model_performance.json. You can load and display these results using the provided functions in the notebook or scripts.
