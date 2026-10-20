# Bike Sharing Data Analysis

## About the Project

This is a small data analysis project where I explored bike rental data to understand when people rent bikes the most and how different weather conditions might affect rentals.

I worked with the hourly bike sharing dataset and used Python to explore the data, find patterns and create graphs.

## Dataset

I used the Bike Sharing Dataset from the UCI Machine Learning Repository.

Dataset: [UCI Bike Sharing Dataset](https://archive.ics.uci.edu/dataset/275/bike+sharing+dataset)

For this project, I used `hour.csv`, which contains 17,379 rows and 17 columns.

## Tools Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook (VS Code)

## What I Did

- Loaded the dataset and explored its columns.
- Checked for missing values and duplicate rows.
- Compared average bike rentals at different hours.
- Compared working days and non-working days.
- Created a line graph to understand hourly rental patterns.
- Analysed rentals under different weather conditions.
- Created scatter plots to investigate wind speed and bike rentals.

## What I Found

**1. Working Days vs Non-Working Days**

On working days, bike rentals were higher around 8 AM and 5–6 PM. This might be because people use bikes to travel to and from work.

On non-working days, the highest average rentals were around 1 PM.

**2. Weather Conditions**

I found that bike rentals were generally higher in good weather and lower in bad weather.

However, the worst weather category had only 3 observations, so I cannot make a strong conclusion based on that result.

**3. Wind Speed**

I checked the relationship between wind speed and bike rentals using scatter plots.

I noticed that there was no very clear