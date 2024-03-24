# Project-Economics
# Economic Data Analysis and Stock Market Performance

This project focuses on analyzing various economic indicators and their relationships with stock market performance, particularly the S&P 500 index. The analysis combines data from multiple sources, including government agencies and Yahoo Finance, to provide insights into the interplay between macroeconomic factors and stock market returns.

## Project Structure

The project is organized into the following sections:

1. **Data Extraction and Preprocessing**: This section includes code to extract data from multiple Excel files containing economic indicators such as GDP, federal interest payments, inflation rates, unemployment rates, and federal debt. The data is cleaned, merged, and transformed into a single CSV file for further analysis.

2. **Exploratory Data Analysis (EDA)**: This section includes visualizations and statistical analyses to understand the trends, patterns, and relationships between various economic indicators over time. It includes correlation matrices, scatter plots, and time-series plots.

3. **Regression Analysis**: This section employs multiple linear regression models to analyze the relationships between economic indicators and key variables such as federal interest payments, GDP, and S&P 500 annual returns. It includes model summaries, coefficient interpretations, and forecasting.

4. **Scenario Analysis**: This section explores hypothetical scenarios, such as a recession, and evaluates the potential impact on economic indicators like federal interest payments and S&P 500 returns. It includes visualizations and quantitative analyses of the scenario outcomes.

5. **Sectoral Analysis with Yahoo Finance**: This section incorporates stock data from Yahoo Finance for selected companies across different sectors (e.g., technology, energy). It analyzes the relationships between stock performance metrics (such as 52-week highs and lows) and economic indicators, providing insights into sector-specific dynamics.

6. **Principal Component Analysis (PCA)**: This section employs PCA to reduce the dimensionality of the dataset and identify the most significant principal components that explain the variance in the data. It includes visualizations and interpretations of the principal components.

7. **Time Series Analysis and Forecasting**: This section explores time series modeling techniques, such as ARIMA and VAR models, to forecast economic indicators and stock market returns. It includes model summaries, diagnostic tests, and forecasts for future periods.

## Dependencies

The project relies on several Python libraries for data manipulation, analysis, and visualization. The key dependencies are:

- pandas
- numpy
- matplotlib
- seaborn
- statsmodels
- scikit-learn
- yfinance

## Getting Started

To run this project, follow these steps:

1. Clone the repository or download the project files.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Navigate to the project directory.
4. Open the Jupyter Notebook or Python script files and run the code cells or scripts in the desired order.

## Data Sources

The project utilizes the following data sources:

- Federal Reserve Economic Data (FRED) for economic indicators such as GDP, federal interest payments, inflation rates, unemployment rates, and federal debt.
- Yahoo Finance for historical stock data of selected companies.

## Contact

If you have any questions or suggestions regarding this project, please feel free to contact the project maintainer at [insert email address].
