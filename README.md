Air Quality Data Analysis (India)

This project performs exploratory data analysis (EDA) on air pollution data from multiple Indian cities using Python.
The goal is to analyze pollution trends, compare air quality across cities, and visualize relationships between different pollutants.

Air pollution is a major environmental and public health issue, and data analysis helps identify patterns that may support better environmental monitoring and decision-making.

Dataset

The dataset contains daily air quality measurements for several Indian cities.
It includes pollutant concentration values and Air Quality Index (AQI) information.

Main Columns
Column	Description
City	Name of the city
Date	Date of measurement
PM2.5	Fine particulate matter (most harmful pollutant)
PM10	Coarse particulate matter
NO, NO₂, NOx	Nitrogen oxide pollutants
NH₃	Ammonia concentration
CO	Carbon monoxide
SO₂	Sulfur dioxide
O₃	Ozone
AQI	Air Quality Index
AQI_Bucket	Air quality category
Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

These libraries were used for data manipulation, statistical analysis, and visualization.

Project Structure
air-quality-data-analysis
│
├── data
│   └── city_day.csv
│
├── images
│   ├── top_polluted_cities.png
│   ├── pm25_yearly_trend.png
│   ├── pollution_correlation.png
│   ├── pm25_distribution.png
│   └── top_aqi_cities.png
│
├── air_quality_analysis.ipynb
└── README.md
Exploratory Data Analysis

The project includes several analyses to better understand pollution patterns.

1. Top Polluted Cities (PM2.5)

A comparison of cities with the highest average PM2.5 pollution levels, highlighting areas with severe air quality issues.

2. PM2.5 Pollution Trend

A time-series analysis showing how PM2.5 pollution changes across years.

3. Pollution Correlation

A heatmap visualization showing relationships between pollutants such as PM2.5, PM10, NO₂, SO₂, and others.

This helps identify pollutants that may share common emission sources.

4. PM2.5 Distribution

A histogram showing the distribution of PM2.5 values across the dataset.

This helps understand typical pollution ranges and extreme pollution events.

5. Cities with Highest AQI

A comparison of cities with the highest Air Quality Index values, which represent overall air pollution severity.

Key Insights

Certain metropolitan cities consistently show higher PM2.5 pollution levels.

Several pollutants demonstrate moderate to strong correlations.

Pollution levels vary across time and between different cities.

How to Run the Project
1. Install required libraries
pip install pandas numpy matplotlib seaborn
2. Run the notebook

Open:

air_quality_analysis.ipynb

Run all cells to reproduce the analysis and visualizations.

Future Improvements

Possible extensions for this project include:

Seasonal pollution analysis

City-wise pollution trends

Predictive modeling for pollution forecasting

Interactive dashboards for pollution monitoring

Author

Rithika Lakshmi Padala

B.Tech Information Technology
