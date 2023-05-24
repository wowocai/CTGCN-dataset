# CTGCN-dataset

We establish a refined and real-world dataset to support the prediction model of pavement deterioration. The research data is from the regional road network in Shanghai, where a total of 1,093 pavement data points are sampled. The dataset contains data on weather, traffic volume on the road networks, maintenance projects on pavement, and pavement performance during January 2021 and March 2022. In order to study the time lag of impact factors on pavement, all variables of research samples are processed into time series variables. 

The dataset includes pavement performance data, traffic volume data, maintenance data and weather data(the highest temperature, the lowest temperature and moisture) during 100 days of 1093 data points.
The structure of data is 600 X 1094. 
Each colume represents 6 variables for 100 days of one data point in certain pavement region.
Each row represents value of a property(factor) in a certain day of 1093 data points.
The first colume represents the property and time step(start from 0). For example, the traffic volume in second day(the third time step) is named as traffic2.

