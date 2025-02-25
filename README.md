# Covid-Data-Analysis

# Overview

This project focuses on analyzing COVID-19 data using SQL. The dataset includes global records of confirmed cases, deaths, and recoveries. The analysis covers various aspects such as missing value handling, descriptive statistics, correlations, rankings, and linear regression models.

# Technologies Used

Microsoft SQL Server

SQL Queries for Data Cleaning and Analysis

# Features

1. Data Cleaning

Checked for missing values.

Replaced NULL values with 0 to ensure consistency.


2. Descriptive Statistics

Counted total rows and identified data duration.

Calculated minimum, maximum, and sum of confirmed, deaths, and recovered cases per month.

Computed central tendency measures:

Mean: Average values for confirmed, deaths, and recovered cases.

Median: Used SQL techniques to determine the median of confirmed cases.

Mode: Found the most frequently occurring confirmed cases.


3. Dispersion Measures

Calculated variance and standard deviation for confirmed, deaths, and recovered cases.

Examined the spread of values month-wise.


4. Percentiles & Frequency

Used SQL percentile functions to understand data distribution.

Identified top 10 records based on confirmed, deaths, and recovered cases.

Compared average values with percentile values.


5. Correlation Analysis

Analyzed relationships between confirmed, deaths, and recovered cases.

Found strong positive correlations, validating data consistency.


6. Ranking & Row Numbering

Assigned row numbers based on confirmed cases.

Ranked records for better insights into case severity across locations.


7. Linear Regression Model

Built a simple linear regression model to estimate deaths based on confirmed cases.

Computed slope and intercept for predicting fatalities.


# Usage

- Clone the repository:

git clone https://github.com/yourusername/covid-data-analysis.git

- Import the dataset into SQL Server.

- Run the provided SQL queries for analysis.


# Results & Insights

The highest number of cases were recorded in India around April-May 2021.

A high correlation (0.79) exists between confirmed and death cases.

The linear regression model suggests that for every 100 confirmed cases, approximately 1.36 deaths occur.

Data showed seasonality trends, especially in December.

# Future Enhancements

Implementing data visualization using Power BI or Python.

Integrating predictive models for COVID-19 case forecasting.

Expanding the dataset for more recent updates.
