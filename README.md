# Analysis of NYC-311 Service Request Data
Background:

311 Service Requests encompass all non-emergency requests from the city, including but not limited to noise complaints, air quality issues and reports of unsanitary conditions etc. The 311 calls in New York City (NYC) are publicly available.

311 service request dataset is available at https://data.cityofnewyork.us/Social-Services/311- Service-Requests- from-2010-to-Present/erm2-nwe9

Problem Statements and Motivation:

Analysis of 311 calls can be of great use for a wide variety of purposes, ranging from a rich understanding of the status of a city to the effectiveness of the government services in addressing such calls.

In our analysis, we want to answer following questions

1. What are different type of Service Requests(SRs)? Which is most/least frequent?

2. From which borough most SRs come from? 

3. Which SRs peaks at what time of year or time of day? 

4. How air quality issues relate to different boroughs? 

5. The agencies which are more efficient in solving SRs.

6. From which type of location we get most number of complaints?

Next thing we want to find out or predict is: 

1. Predict time required in terms of range of days to resolve a specific complaint in a specific borough.

2. A time series analysis to forecast the volume of calls to be expected on given future date.

3. Merge the 311 dataset with the Storms dataset. Compare the average response time for complaints during a storm and otherwise.

4. To do a time series analysis of the storm data to find out the weekly or daily seasonality.


The storm events dataset is available at
https://www.ncdc.noaa.gov/stormevents/choosedates.jsp?statefips=36%2CNEW+YORK
This dataset contains features such as Location, County, Date, Type, Magnitude and few features telling about the damage caused by the event.


Outcomes of Analysis:

![Complaints Distribution Across Boroughs](https://github.com/ayush159/NYC-311/blob/master/graphs/distribution.png)

![Most Common Complaints](https://github.com/ayush159/NYC-311/blob/master/graphs/most_common.png)

![Air_Quality issue distribution across NYC](https://github.com/ayush159/NYC-311/blob/master/graphs/air_quality.png)

