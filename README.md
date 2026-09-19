# Weather Dataset Analysis

A Python-based data analysis project that explores and analyzes weather data using Pandas.

## 📌 Project Overview

This project performs exploratory data analysis on a weather dataset. It examines weather conditions, wind speed, visibility, missing values, and other useful information to understand patterns in the dataset.

## 📊 Dataset

The dataset contains weather-related information including:

- Weather conditions
- Wind Speed (km/h)
- Visibility (km)
- Other weather attributes

## 🔍 Analysis Performed

The project includes:

- Loading and inspecting the weather dataset
- Displaying the first few records
- Checking dataset shape and information
- Identifying missing values
- Finding unique weather conditions
- Counting occurrences of different weather conditions
- Finding the number of `Clear` weather records
- Finding records with wind speed of exactly 4 km/h
- Renaming the `Weather` column to `Weather Condition`
- Calculating average visibility
- Counting `Snow` weather records
- Finding records where wind speed is above 24 km/h and visibility is 25 km
- Counting `Fog` weather records

## 🛠️ Technologies Used

- Python
- Pandas
- Google Colab

## 📈 Key Operations

The project demonstrates practical Pandas operations such as:

- `read_csv()`
- `head()`
- `shape`
- `info()`
- `isnull()`
- `unique()`
- `value_counts()`
- Filtering with conditions
- `rename()`
- `mean()`

## 🚀 Future Improvements

- Perform detailed exploratory data analysis
- Create visualizations using Matplotlib and Seaborn
- Analyze relationships between weather parameters
- Build a machine learning model for weather prediction
