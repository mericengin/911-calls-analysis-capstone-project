# 911 Calls Analysis

This project provides an analysis of a dataset containing 911 emergency calls made in the United States. The goal is to explore various patterns and trends within the data, such as the distribution of calls by emergency type, time, and location, as well as response times.

## Files

- `911.csv`: This file contains the dataset of 911 calls. It includes columns such as `lat`, `long`, `desc`, `zip`, `title`, and `timeStamp`, representing geographic coordinates, call description, ZIP code, emergency call title, and timestamp.
- `911_calls_analysis.ipynb`: Jupyter Notebook that performs data analysis, including data cleaning, exploration, and visualization. The analysis covers various aspects like call frequency over time, response by call type, and more.

## Dataset Overview

The dataset contains the following columns:
- `lat`: Latitude of the location of the emergency.
- `long`: Longitude of the location of the emergency.
- `desc`: A description of the emergency situation.
- `zip`: The ZIP code where the emergency occurred.
- `title`: The title or category of the emergency (e.g., Fire, Traffic, Medical).
- `timeStamp`: The date and time when the 911 call was made.

## Requirements

To run this analysis, you will need the following Python libraries:
- `pandas`: For data manipulation and analysis.
- `matplotlib`: For creating visualizations.
- `seaborn`: For advanced data visualization.

You can install the required libraries using `pip`: