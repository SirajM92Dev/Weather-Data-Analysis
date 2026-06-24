# Weather Data Analysis Project

## Overview
This project performs Exploratory Data Analysis (EDA) on weather time-series data using Python. The objective is to clean raw weather data, engineer useful features, analyze patterns, and visualize important insights.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Project Workflow

### 1. Data Loading
- Imported weather dataset using Pandas.
- Explored the structure and dimensions of the dataset.

### 2. Data Cleaning
Performed preprocessing steps:
- Checked missing values.
- Handled missing numerical values using mean imputation.
- Handled missing categorical values using mode imputation.
- Converted date values into proper datetime format.

### 3. Feature Engineering
Created additional features to improve analysis:
- Extracted year from date.
- Extracted month from date.
- Extracted day name.
- Created temperature categories:
  - Cold
  - Normal
  - Hot

### 4. Statistical Analysis
Analyzed:
- Average temperature
- Minimum and maximum temperature
- Dataset statistics
- Correlation between numerical features

### 5. Data Visualization
Created visualizations for:
- Temperature trends over time
- Wind speed and temperature relationship
- Weather condition distribution
- Temperature category analysis

## Project Structure

```
Weather-Data-Analysis/
│
├── weather_data.csv
├── weather_data_analysis.ipynb
├── analyzed_weather_data.csv
└── README.md
```

## Key Insights
- Identified temperature trends across time.
- Analyzed weather condition frequency.
- Studied relationships between weather attributes.

## Author
Siraj Muhammad
AI/ML Enthusiast | Python Developer | Data Science Learner
