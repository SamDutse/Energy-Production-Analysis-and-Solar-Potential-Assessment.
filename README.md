# Energy-Production-Analysis-and-Solar-Potential-Assessment.
# Introduction
The "Renewable Energy and Weather Conditions" dataset includes information on various weather conditions, as well as the energy production of a renewable energy system.
The dataset contains columns such as; 
- "Time" (timestamp), 
- "Energy delta[Wh]" (energy production), 
- "GHI" (global horizontal irradiance), 
- "temp" (temperature), 
- "pressure", 
- "humidity", 
- "wind_speed", 
- "rain_1h", 
- "snow_1h", 
- "clouds_all", 
- "isSun", 
- "sunlightTime", 
- "dayLength", 
- "SunlightTime/daylength", 
- "weather_type", 
- "hour", and 
- "month". 
The data was likely collected over a period of time using sensors and other measuring devices, and can be used to gain insights into the relationship between weather conditions and renewable energy production. The dataset can be analyzed using various statistical and machine learning techniques to identify patterns and trends in the data, and to develop predictive models that can be used to optimize renewable energy production. 

**This SQL project involves analyzing energy consumption data and assessing solar potential.**

## SQL Concept Applied
Mostly **Data Query Language (DQL)** with use of advance concept like **CTE (common Table Expression) or WTH query** and aggregating data, fuctions used include COUNT(),SUM(), AVG(), DATEPART(),ROUND(), and CAST().

# Problem Statement
I embark on this project due to the need to understand energy consumption patterns, identify seasonal trends, and explore the relationship between energy consumption and weather factors.

# Data Source (Obtained from Kaggle)
The data was obtained from Kaggle with a total dimension of 196776


# Data Analysis
My Analysis on this dataset was to gain insight into this the four key points with reason and impact of why the query was carried.
1. Seasonal Energy Production Trends:
- Identified patterns in energy production based on the year, accumulated months, weekdays, and hours.
- Provided valuable insights for energy planning, distribution, and forecasting.

2. Energy Production and Weather Type Relationship:
- Analyzed the impact of different weather types on energy production.
- Highlighted the average and total energy production for each weather type, offering valuable insights for energy management strategies.

3. Solar Potential Analysis:
- Explored the relationship between solar radiation (irradiance) and energy production.
- Investigated the correlation between solar radiation and factors such as month, hour, temperature, and weather type, providing insights into solar energy generation potential.

4. Temperature and Energy Production Relationship:
- Examined the connection between temperature and energy production.
- Analyzed the distribution of temperature during different hours of the day and identified average energy production at various temperature levels.

# Findings and Insights
-	I Identified patterns in energy Production based on seasons (year, accumulated months, weekdays, and hours) with summer seasons having highest Production
-	Base on analysis on the impact of different weather types on energy production weather type 4 and 1 are having the highest total and average energy production respectively.
-	 I also Investigated the correlation between solar radiation and factors such as month, hour, temperature, and weather type, providing insights into solar energy generation potential the finding can be viewed when the query is runned.
-	 I Examined the connection between temperature and energy consumption which has an R square value of 0.69.
