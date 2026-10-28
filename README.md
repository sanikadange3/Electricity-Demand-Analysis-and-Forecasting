# Electricity Demand Analysis and Forecasting

## Project Overview

This project analyzes household electricity consumption data and forecasts future electricity demand using Python, statistical analysis, regression, and time-series forecasting techniques.

## Objectives

* Analyze household electricity consumption patterns.
* Clean and preprocess the dataset.
* Perform exploratory data analysis and visualization.
* Apply regression and time-series analysis.
* Forecast future electricity consumption.
* Evaluate forecasting models using MAE and RMSE.

## Dataset

The project uses the **Individual Household Electric Power Consumption** dataset.

* **Records:** 2,075,259
* **Columns:** 9
* **Time period:** December 2006 to November 2010
* **Data frequency:** Approximately one reading per minute
* **Source:** UCI Machine Learning Repository

The dataset contains date, time, active power, reactive power, voltage, current intensity, and three sub-metering measurements.

## Technologies Used

* Python
* JupyterLab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Statsmodels

## Methodology

1. **Data Collection:** Load the household electricity consumption dataset.
2. **Data Preprocessing:** Handle missing values, duplicates, and data types.
3. **Resampling:** Convert minute-level readings into hourly and daily data.
4. **Exploratory Data Analysis:** Calculate descriptive statistics and visualize consumption trends.
5. **Regression Analysis:** Apply Linear Regression to examine consumption trends.
6. **Time-Series Analysis:** Use ACF, PACF, and the Augmented Dickey-Fuller test.
7. **Forecasting:** Apply Holt-Winters Exponential Smoothing and ARIMA.
8. **Evaluation:** Compare forecasting performance using MAE and RMSE.

## Results

* Successfully loaded 2,075,259 records with 9 columns.
* Processed the dataset into 34,211 hourly records.
* Handled missing values, leaving no missing values in the processed numerical columns.
* Identified 734 potential outliers using the IQR method.
* Calculated average hourly active power consumption of approximately **1.092 kW**.
* Calculated average daily energy consumption of approximately **26.20 kWh**.
* Prepared the data for electricity consumption forecasting.

*Forecasting accuracy results should be added after evaluating the models on the test dataset.*

## Installation

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels jupyter
```

## How to Run

1. Clone or download this repository.
2. Install the required libraries.
3. Download the dataset from the UCI Machine Learning Repository.
4. Place the dataset in the project folder.
5. Open JupyterLab:

```bash
jupyter lab
```

6. Open the project notebook and run the cells sequentially.

## Applications

* Household electricity consumption analysis
* Electricity demand forecasting
* Energy usage planning
* Identification of consumption patterns
* Data-driven energy management

## Conclusion

This project demonstrates how data analysis and time-series forecasting can be used to understand household electricity consumption and estimate future demand. The findings can support better energy planning and efficient electricity management.

## Author

**Sanika Dange**

## License

This project is intended for educational and academic purposes.
