# PyBer-Analysis

## Project Overview

We have been tasked with using the Pandas and Matplotlib libraries to perform analysis and visualization for a ridesharing company, PyBer. The ridesharing data needs to be split by city type (urban, suburban, or rural). We need to determine the total rides, total drivers, total fares, and average fares by ride/driver and create a new DataFrame for these summary statistics. We also need to plot the total weekly fares for each city type on a line graph.

## Results

![Summary.PNG](analysis/Summary.PNG)

As seen above, there are some stark differences between the three city types. Urban cities have by far the highest total rides, drivers, and fares. Meanwhile, rural areas have the highest average fare per ride and average fare per driver. This is intuitive because there are fewer drivers in rural areas so they likely charge much more. Rides in rural areas are also probably longer on average.

![PyBer_fare_summary.png](analysis/PyBer_fare_summary.png)

This line graph shows the total fares for each city type for every week in January through April. Urban cities clearly bring in the most money, followed by suburban cities and then rural areas.

## Summary

One suggestion for addressing disparities between the city types would be to lower the average fares for rural areas in order to get more people using the service. Another suggestion would be to place/hire more drivers in rural areas as that could also drive the price down. But perhaps the most important suggestion would be to focus on the service in urban cities because that is where over 60% of fares are collected and by far the most rides are taken in urban cities. 
