# ClimateKClusters
K-means Clustering on temperature dataset

Dataset - https://www.ncei.noaa.gov/access/monitoring/climate-at-a-glance/global/time-series/globe/land_ocean/12/2/1950-2022

The project involves using K-means clustering to analyze temperature anomalies across different regions, based on quantitative data that is converted to categorical. Clusters are formed based on temperature variance relative to a global baseline. The main outcome is a map visualization, where clusters are differentiated using color luminance, reflecting the average temperature of each cluster. This approach highlights geographical temperature patterns more effectively than using color hue. The process is applied to data spanning from 1950 to 2022, and the results are animated to show temporal changes in global temperature patterns.

Sample dataset format:

I have a temperature dataset of a particular year (say 1950) of the all the regions of the world ,
<img width="634" alt="Screen Shot 2023-12-23 at 11 28 10 PM" src="https://github.com/ramasai840/ClimateKClusters/assets/66384225/5adb6c3d-61d6-440e-8978-ef0d697c75d3">




Below is the data format of the global temperature from 1950 to 2022,


<img width="633" alt="Screen Shot 2023-12-23 at 11 28 15 PM" src="https://github.com/ramasai840/ClimateKClusters/assets/66384225/6a2b5bda-1be6-419e-b571-710e9e2af5cc">


Animation of Resultant Maps:
![kMeans](https://github.com/ramasai840/ClimateKClusters/assets/66384225/cfa580f2-9476-49fc-9d6d-1a61f2594633)

1950 Global Climate Deviations Map: Illustrated here are the outcomes of the k-means clustering analysis on the worldwide temperature deviations for 1950. Geographic coordinates are marked by dots, with their coloration signifying the cluster categorization correlated with the temperature variance. The spectrum of color from cool blue to warm red denotes the range of anomalies, blue for temperatures below, and red for temperatures above the long-term average. This clustering highlights geographic patterns in temperature changes, essential for understanding climate variations. A color gradient bar to the right serves as a key to the anomalies, and the continental outlines provide spatial context. The contrasting striped overlay aids in differentiating the areas of temperature anomalies for enhanced visual clarity.
