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

Using the sqlite hawaii weather database code was written to retrieve the last 12 months of precipitation data and plot the results.
![alt text](https://github.com/jj2773/surfs_up/blob/main/yearly_rainfall.PNG)

A histogram of temperatures was also created from the reporting station USC00519281 which had the most temperature data points.
![alt text](https://github.com/jj2773/surfs_up/blob/main/histgram_temps_station_USC00519281.PNG)

A statistical analysis of temperatures for June and December was also calculated.
![alt text](https://github.com/jj2773/surfs_up/blob/main/June_Dec_Temp_stats.PNG)

* main point 1
* main point 2
* main point 3