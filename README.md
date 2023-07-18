# Introduction
[Dataset](https://archive.ics.uci.edu/dataset/492/metro+interstate+traffic+volume) contains hourly Minneapolis-St Paul, MN traffic volume for westbound I-94, including weather and holiday features from 2012-2018.
Traffic is recorded at MN DoT ATR station 301, roughly midway westbound between Minneapolis and St Paul, MN, and not for the entire highway.

# Analysis Goals
To find indicators of heavy traffic

# Indicators studied 
- Day and Night traffic volume
- Daytime indicators average traffic volume by month (including outlier July)
- Daytime indicators average traffic volume by year
- Daytime indicators average traffic volume by day of week
- Daytime indicators average traffic volume by time of day
- Numerical weather indicators and its correlation with average traffic volume
- Categorical weather indicators average traffic volume

# Analysis tools
- Pandas dataframe and series operations
- Matplotlib visualisations
- Python Datetime modules and datetime class attributes such as hour, dayofweek, month, year
- Python correlation method 

# Conclusion
Two types of indicators of heavy traffic was identified as below:

**Time indicators**
- The traffic is usually heavier during warm months (March–October) compared to cold months (November–February).
- The traffic is usually heavier on business days compared to the weekends.
- On business days, the rush hours are around 7 and 16.

**Weather indicators**
- Shower snow
- Light rain and snow
- Proximity thunderstorm with drizzle
