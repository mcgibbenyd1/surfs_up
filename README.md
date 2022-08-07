# surfs_up

## Project Overview
W. Avy, and investor, is looking to back a venture for you of a Surf n' Shake shop serving surfboards and ice cream. He had a concern of weather playing a factor for year round sales and he is looking to you to help with analyzing a weather dataset on the Hawaiin island you plan to set up the venture on. 

## Resources
- Data Source: hawaii.sqlite
- Software:Python 3.7.6, jupyter-notebook 6.0.3, Anaconda 4.13.0, Pandas, Numpy, SQLAlchemy 1.3.13 

## Challenge Overview
W. Avy likes your analysis, but he wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

## Challenge Results
- From the Analysis of the June temperatures, as you can see below in the dataframe, the average temperature is around 75 degrees with a maximum temperature observed during the observations being 85 degrees and 64 being the minimum. 

<p align="center">
Summary Statistics for June Temperatures
</p>

<p align="center">  
<img src="https://github.com/mcgibbenyd1/surfs_up/blob/main/June_temps.png" width="20%"/>
</p>

- From the Analysis of the December temperatures, as you can see below in the dataframe, the average temperature is around 71 degrees with a maximum temperature observed during the observations being 83 degrees and 56 being the minimum. 

<p align="center">
Summary Statistics for December Temperatures
</p>

<p align="center">
<img src="https://github.com/mcgibbenyd1/surfs_up/blob/main/December_Temps.png" width="20%"/>
</p>   

- Comparing the the sets of data, there are more data point observed for the June monthes but overall the temperatures are consistent between the two monthes of observation with Decemeber showing a slightly lower temperature throughout the month than June.                                                         

## Overall Summary
Provide a high-level summary of the results and two additional queries that you would perform to gather more weather data for June and December.  
- The temperature in Hawaii in the monthes of June and December stays around or above 70 degrees based on a single weather stations recordings. Which could provide for the perfect combination of surfing and ice cream.

Two additional queries that could aid in understanding weather data for the June and December monthes:
1. Understand the elevation and locational data of the recording stations in the 'station' table to understand if the data is skewed on one side of the island. 
2. Precipitation between different stations and amount of rain recieved on specific days. 
  
