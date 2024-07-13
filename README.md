# Weather Forecasting using Time Series Analysis

## Project Overview

### Contributors:
- **Aditya Tanna (202103023)**, [202103023@daiict.ac.in](mailto:202103023@daiict.ac.in)
- **Rushi Vaghela (202103028)**, [202103028@daiict.ac.in](mailto:202103028@daiict.ac.in)
- **Jay Rathod (202103042)**, [202103042@daiict.ac.in](mailto:202103042@daiict.ac.in)

### Institution:
Dhirubhai Ambani Institute of Information & Communication Technology, Gandhinagar, Gujarat 382007, India

### Abstract
In the context of increasing global warming and unpredictable weather, accurate weather forecasting has become essential. This project focuses on forecasting temperature and humidity levels using a dataset spanning five years, capturing daily measurements of various weather metrics. By employing various time series analysis techniques, we aim to make precise predictions that can help in making informed decisions in daily life based on environmental factors.

### Dataset
The dataset, sourced from Kaggle, includes five years of hourly weather data (2012-2017) for several cities, with metrics such as temperature, humidity, wind speed, and more. For this analysis, we focused on three cities: Los Angeles, Miami, and Jerusalem, chosen for their distinct geographical and climatic conditions.

### Analysis and Methods
1. **Data Cleaning and Preparation**: Ensuring the accuracy and reliability of the data.
2. **Exploratory Data Analysis**: Identifying significant patterns and anomalies in temperature and humidity trends.
3. **Stationarity, Trend, and Seasonality Checks**: Performing stationarity checks and autocorrelation analyses to understand the patterns.
4. **Modeling with SARIMAX**: Fitting a Seasonal AutoRegressive Integrated Moving Average with eXogenous variables (SARIMAX) model to the historical data to forecast future humidity levels.

### Key Findings
- **Temperature Trends**:
  - Los Angeles: Stable pattern with moderate seasonal fluctuations.
  - Miami: Consistent high temperatures throughout the year.
  - Jerusalem: Significant seasonal variations with hot summers and cooler winters.

- **Humidity Trends**:
  - Los Angeles: Stable humidity levels due to its coastal location.
  - Miami: High humidity levels throughout the year, influenced by its tropical climate.
  - Jerusalem: Lower humidity with peaks during colder months, influenced by its higher elevation and inland position.

- **Rolling Averages**: Used to smooth out short-term fluctuations and highlight longer-term trends. Different trends were observed for each city based on their geographical locations.

- **Model Fitting and Forecasting**: The SARIMAX model was used to forecast temperature and humidity, with varying success. The model captured long-term and seasonal trends but required further refinement for more accurate predictions, especially for abrupt changes.

### Conclusion
The project successfully applied SARIMAX models to analyze and forecast weather trends. While the models provided valuable insights, they also highlighted the need for further refinement to better accommodate irregular climatic phenomena. Future research could explore integrating more dynamic models and incorporating broader datasets for improved predictions.

### Impact
The goal of this project is to offer a robust framework for weather forecasting, helping urban residents make informed decisions based on predicted temperature and humidity levels.

### Presentation Video
A presentation video detailing the project's methodology and findings can be accessed [here](https://drive.google.com/drive/folders/1-FcJN8zZe-EUhdWCUp-BPVTanrglnBWT?usp=sharing).

### References
1. D. Beniaguev, "Historical hourly weather data 2012-2017," Kaggle (2017). Available online: [Kaggle Dataset](https://www.kaggle.com/datasets/selfishgene/historical-hourly-weather-data).
