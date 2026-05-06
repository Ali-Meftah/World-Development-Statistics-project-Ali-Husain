Problem statement 

Despite 3 decades of global development, there is a transparent divide between the life expectancy of countries with lower income, and higher income. 

Executive Summary
Using the “world development statistics”, we are able to monitor the population, life expectancy, and GNI of all countries from 1990 to 2025.
This project gives Doctors Without Borders (MSF) the insight and urgency to bridge the global health divide. This is done by pinpointing income groups that are in need, providing recommendations, and mentioning examples of successful countries that eliminated that gap.


Cleaning the data - 
Removed the NULL rows
Used melt to keep the data in a more manageable format
Used Merge to join the datasets together
Converted STR to float
dropped all the years except those from 1990 to 2025
Categorized by income

Modeling and Analysis -

Measuring the gap (analysis)
Grouping by the GNI per income group 

## Used AI for a better looking plot

Heatmap
Relationship plot (correlation)
Extracting the largest longevity gains (1990 - 2025)
Finding the top life expectancy improvers


# Table of Content 
Introduction
Problem statement
Audience
The Divide Statistics
Improvements and developements
Recommendations
References

Dataset: WDS.csv
jupyter notebook: Life-Expectancy_Gap_Project.ipynb
Source of the data was [Gapminder](https://www.gapminder.org/about/)
Slides: Health-Wealth Gap presentation Ali and Husain.
