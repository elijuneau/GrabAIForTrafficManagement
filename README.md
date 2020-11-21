ORIGINAL PROBLEM STATEMENT:https://github.com/yingjia-liu/Msft-Grab-FRS

WHERE THIS CAME FROM: https://www.kaggle.com/mahadir/grab-traffic-demand-forecasting

WHAT WAS CHANGED: Imported a couple more modules and improved on the graphs (especially the first and second ones.)

DATASET HERE: https://github.com/yingjia-liu/Msft-Grab-FRS/blob/master/Traffic_Management/Traffic_Management_Problem_Statement.md

# GrabAIForTrafficManagement
Grab Traffic Demand Forecasting

Traffic Demand Dataset:
Data Schema (Field & Description):

- geohash6: geohash is a public domain geocoding system which encodes a geographic location into a short string of letters and digits with arbitrary precision. You are free to use any geohash library to encode/decode the geohashes into latitude and longitude or vice versa.(Examples:https://github.com/hkwi/python-geohash)
- day: the value indicates the sequential order and not a particular day of the month
- timestamp: start time of 15-minute intervals in the following format: <hour>:<minute>, where hour ranges from 0 to 23 and minute is either one of (0, 15, 30, 45)
- demand: aggregated demand normalised to be in the range [0,1]
The dataset can be downloaded here (140MB CSV file).

Problem Statements:
The challenge targets to improve the traffic condition for road network in Southeast Asia by leveraging Grab booking demand data, which hinders mobility and economic growth. Problem statements including:

Which areas have high / low traffic demand?
How does regional traffic demand change according to day / time?
Forecast the travel demand for next 15min / 1hour and predict areas with high travel demand
