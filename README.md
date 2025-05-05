# Global Economy Indicators Project

This notebook explores a dataset of global economic indicators sourced from [Kaggle](https://www.kaggle.com/datasets/prasad22/global-economy-indicators). It analyzes macroeconomic variables such as GDP, GNI, sector contributions, and exchange rates across multiple countries and years, aiming to understand key drivers of economic performance.

## Dataset Overview

The dataset spans from **1970 to 2021**, covering dozens of countries and including indicators like:

- **GDP and GNI (Gross Domestic and Gross National Income)**
- **Sector-level value added (Agriculture, Manufacturing, Services, etc.)**
- **Imports/Exports**
- **Population and exchange rates**
- **Government and household expenditure**

Each row represents a country-year pair with 25+ macroeconomic variables.

## Project Goals

- Clean and preprocess the dataset for analysis
- Explore trends in global economic development
- Analyze how different sectors contribute to GDP
- Examine country-level differences using visualization and modeling
- Apply machine learning models (e.g., Linear Regression) to predict GDP growth based on sector activity

## Methods Used

- **Data Cleaning**: Whitespace trimming, renaming columns, type conversions
- **Exploratory Data Analysis (EDA)**: Correlation heatmaps, pairplots, bar charts by country/region
- **Modeling**: Linear regression models to predict GDP growth from economic indicators by country
- **Evaluation Metrics**: R² Score and RMSE per country

## Files
/Global_Economy_Indicators_Project.ipynb # Main analysis notebook
/drive/My Drive/Indicators.csv # Original CSV file (referenced via Google Drive)


## Example Insights

- Strong correlation between **manufacturing, exports**, and **GDP growth** in emerging economies
- Developed nations show higher contributions from **service sectors**
- Linear regression models performed reasonably well for many countries, though variance existed due to data quality or country-specific factors

## Requirements

- Python 3.7+
- Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

> Note: The original dataset file must be manually placed in the expected directory when running the notebook (`drive/My Drive/Indicators.csv`).

## Future Improvements

- Add time series forecasting for selected indicators
- Include regional clustering to compare country groupings
- Improve model robustness with feature engineering or ensemble methods
