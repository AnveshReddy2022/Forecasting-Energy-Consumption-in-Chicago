# Forecasting Energy Consumption in Chicago

## Project Overview
This project tackles the challenge of optimizing energy consumption in Chicago's residential areas, particularly focusing on single-family homes. Utilizing a data-driven approach, the aim is to decode patterns and relationships in energy usage to foster sustainability and inform targeted urban planning efforts. The dataset, sourced from data.gov, provides a comprehensive view of energy metrics across the city, enabling a detailed exploration of consumption patterns.

## Data Source
The analysis leverages an OpenData dataset from [data.gov](https://data.cityofchicago.org/Environment-Sustainable-Development/Energy-Usage-2010/8yq3-m6wp/data), specifically focusing on energy usage data for the year 2010 in Chicago. This dataset includes a variety of metrics such as electricity and gas usage, housing unit occupancy, demographics, and building characteristics, comprising 67,051 records across 73 features.

## Repository Contents
- `Data/`: Contains the dataset used in the analysis.
- `Notebooks/`: Jupyter notebooks detailing the EDA and machine learning process.
- `Scripts/`: Python scripts for data cleaning and preprocessing.
- `Visualizations/`: Interactive visualizations created using Python libraries to better understand the data and model outcomes.
- `Documentation/`: Detailed reports and presentations outlining the methodologies and key findings.

## Exploratory Data Analysis (EDA)
The EDA segment of this project identifies significant features affecting total energy consumption and examines the seasonal variation in energy use. Insights drawn from the analysis help pinpoint critical periods and factors influencing consumption, aiding in the design of more effective energy conservation strategies.

## Machine Learning Analysis
The project employs several regression models to predict total energy consumption:
- **Linear Regression**: Establishes a baseline for prediction accuracy.
- **Polynomial Regression**: Captures non-linear dependencies better than linear models.
- **Ensemble Models**: Including Decision Tree, Random Forest, and Gradient Boosting models to improve prediction robustness and accuracy.

Each model is evaluated based on its predictive performance, with a focus on R-squared, MAE, and MSE metrics.

## How to Navigate This Repository
- **Begin with EDA**: Start by exploring the `Notebooks/` for a deep dive into the exploratory data analysis.
- **Review Machine Learning Models**: Continue to the machine learning notebooks to understand model building and evaluation.
- **Check Visualizations**: Engage with interactive visualizations to visualize predictions and insights.
- **Read Documentation**: For a comprehensive understanding, review the project reports in the `Documentation/` folder.

