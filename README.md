# ClimateKClusters
K-means Clustering on temperature dataset

Dataset - https://www.ncei.noaa.gov/access/monitoring/climate-at-a-glance/global/time-series/globe/land_ocean/12/2/1950-2022

The project involves using K-means clustering to analyze temperature anomalies across different regions, based on quantitative data that is converted to categorical. Clusters are formed based on temperature variance relative to a global baseline. The main outcome is a map visualization, where clusters are differentiated using color luminance, reflecting the average temperature of each cluster. This approach highlights geographical temperature patterns more effectively than using color hue. The process is applied to data spanning from 1950 to 2022, and the results are animated to show temporal changes in global temperature patterns.

Sample dataset format:

I have a temperature dataset of a particular year (say 1950) of the all the regions of the world ,

Year	Latitude	Longitude	Anomaly
1950	-87.5	2.5	-0.06
1950	-87.5	7.5	-0.3
1950	-87.5	12.5	-0.32
1950	-87.5	17.5	-0.35
1950	-87.5	22.5	-0.36


Below is the data format of the global temperature from 1950 to 2022,


Year	Anomaly
1950	-0.08
1951	-0.14
1952	0.03
1953	0.05
1954	0.10


