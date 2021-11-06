# Surfs Up

## Overview
Invester support is needed for openinging a surf shop which also offers ice cream in Oahu Hawaii.  Data analytics was needed to confirm suitable weather would provide the customer demand year around.  The weather information was provided in a SQLite file from nine reporting stations.

## Results
The following python libraries were utlized for this study:

| Libaries      | Usage                            | 
| ------------- |:--------------------------------:|
| SQLAlqehmy    | Mapping SQLite file to an Object | 
| Pandas        | Creating Dataframes              | 
| Datetime      | Date filtering                   | 
| Matplotlib    | Plotting Results                 | 
| Flask         | Web browser query of weather     | 


Using the sqlite hawaii weather database code was written to retrieve and plot a year of precipitation data.
![alt text](https://github.com/jj2773/surfs_up/blob/main/yearly_rainfall.PNG)


A statistical analysis of precipitation data was calculated.

![alt text](https://github.com/jj2773/surfs_up/blob/main/rainstats.PNG)

A histogram of temperatures was also created from the reporting station USC00519281.  
This station had the most temperature data points.
![alt text](https://github.com/jj2773/surfs_up/blob/main/histgram_temps_station_USC00519281.PNG)


A statistical analysis of temperatures for June and December was also calculated.
![alt text](https://github.com/jj2773/surfs_up/blob/main/June_Dec_Temp_stats.png)


* Average precipitation amounts of around .18 inches are expected which would provide ample good weather for surfing.
* From the Temperature Histogram most recordings are between 70 and 80 degrees thus facilitating ice cream sales.
* Summer and Winter temperature variations are nearly the same for this area offering year around business.

## Summary
In summary the weather in Oahu Hawaii is perfect conditions for surfing and ice cream sales due to the year around warm temperatures and many days of low precipitation.  To access specific weather queries a webpage was created for the clients using Flask.  A query using your browser will return specific weather data in a date range in the general format of "**/api/v1.0/temp/<startdate>/<enddate>".  Where the dates are in a string format of '2016-06-01' for example.  Two additional queries that would be beneficial are the precipitation amounts for June and December specifically.