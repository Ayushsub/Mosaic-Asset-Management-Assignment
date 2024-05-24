<h1>Analysis of Sectoral Indices and Macroeconomic Variables</h1>

<h2>Objective</h2>
The goal of this project is to analyze the relationship between various Indian sectoral indices and macroeconomic variables
and also to evaluate the performance of sectoral indices in comparison to Market Indices.

<h2>Data Sources</h2>
<h3>Broad Market Indices:</h3> NIFTY 50 (^NSEI)<br> NIFTY Midcap 50 (^NSEMDCP50)

<h3>Sectoral Indices:</h3>
NIFTY Auto (^CNXAUTO)<br>
NIFTY Financial Services (NIFTY_FIN_SERVICE.NS)<br>
NIFTY Bank (^NSEBANK)<br>
NIFTY FMCG (^CNXFMCG)<br>
NIFTY IT (^CNXIT)<br>
NIFTY Media (^CNXMEDIA)<br>
NIFTY Metal (^CNXMETAL)<br>
NIFTY PSU Bank (^CNXPSUBANK)<br>
NIFTY Realty (^CNXREALTY)<br>
NIFTY Energy (^CNXENERGY)<br>

<h3>Macroeconomic Data:</h3>
Includes various economic indicators such as inflation rates, GDP growth rates, interest rates, etc., stored in Macro_indicators.csv.

<h2>Methodology</h2>
<h3>Data Download and Preparation</h3>
Download Historical Data: Use yfinance to download historical data for each index.<br>
Clean and Align Data: Ensure all datasets have a common date range and handle missing values.<br>
Load Macroeconomic Data: Read and process the macroeconomic data, resampling to match the frequency of the sectoral data.

<h3>Exploratory Data Analysis</h3>
Correlation Analysis: Calculate and plot the correlation matrix between sectoral indices and macroeconomic variables.<br>
Time Series Plots: Plot the historical data for sectoral indices and macroeconomic variables to visualize trends.

<h2>Modeling</h2>
<h3>Models Used:</h3>
Random Forest Regressor<br>
Linear Regression<br>
Support Vector Regressor (SVR)<br>
K-Nearest Neighbors Regressor (KNeighbors)<br>
XGBoost Regressor<br>

<h3>Training and Evaluation:</h3>
Train each model on the data and evaluate performance using metrics such as RMSE, MAE, and R² score.

<h2>Performance Comparison</h2>
Compare the performance of sectoral indices against the NIFTY 50 index using the different models to identify which sectors outperform the broad market index.

<h2>Results</h2>
<h3>Correlation Matrix</h3>
The correlation matrix between sectoral indices and macroeconomic variables is visualized using a heatmap.<br>
<p align="center">
  <img src="https://github.com/Ayushsub/Mosaic-Asset-Management-Assignment/blob/main/Correlation%20Matrix%20between%20Sectoral%20Indices%20and%20Macroeconomic%20Variables.png?raw=true">
</p><br><br>

<h3>Sectoral Indices Over Time</h3>
<p align="center">
  <img src="https://github.com/Ayushsub/Mosaic-Asset-Management-Assignment/blob/main/Sectoral%20Indices%20Over%20Time.png?raw=true">
</p><br><br>

<h3>Macroeconomic Variables</h3>
<p align="center">
  <img src="https://github.com/Ayushsub/Mosaic-Asset-Management-Assignment/blob/main/individual%20plots%20for%20each%20macroeconomic%20variable.png?raw=true">
</p><br><br>

<h3>Sectoral Performance Comparison</h3>
The sectoral indices are compared against the NIFTY 50 index to identify which sectors outperform the broad market.

<h2>Conclusion</h2>
The results show that certain sectoral indices have stronger correlations with specific macroeconomic variables.<br>
The performance comparison indicates which sectors outperform the NIFTY 50 index under different models.

<h2>Results and Performance</h2>
The detailed performance metrics for each model and index are saved in model_performance.json. You can load and display these results using the provided functions in the notebook or scripts.
