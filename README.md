# PyBer_Analysis

## Overview

### Resources
Python 3.7.11
Data Sources: [city_data.csv](Resources/city_data.csv), [ride_data.csv](Resources/ride_data.csv)

#### Purpose
The purpose of this challenge is to analyze ride-sharing data by city type to look for trends in total rides, total drivers, total fares, average fare per ride, average fare per driver, and total fare by city type. This data will be useful when making business decisions for PyBer, the ride sharing company.

#### Process
1. Load city_data.csv and ride_data.csv into dataframes.
2. Merge the dataframes on the "city" columns.
3. Use groupby() and sum() or count() to create a summary dataframe
4. Use groupby() to create a dataframe showing the sum of fares per city type and date
5. Reset the index then create a pivot table with the date as the index, type as the columns, and fare as the values.
6. Filter the tablet to show data from 1/1/19 to 4/28/19 then convert the date column to datetime
7. Use resample() to group the data into weeks instead of days
8. Plot the weekly fares as Total Fare by City Type

The code is found here: [Pyber_Challenge.ipynb](PyBer_Challenge.ipynb)

## Results

describe difference in ride sharing data among the different city types (total rides, total drivers, total fares, average fare per ride and driver, total fare bycity type)

## Summary

include statement summarizing three business recommendations to the CEO for addressing any disparities among city types
