# ThinkML-TML-11

# Team Details
- Name of the Team - TML-11
- Members
  - Krish Jain (Team Leader) 
      - SE E&CS TCET
      - Contact info: 1032220170@tcetmumbai.in
  - Sourajeet Sahoo
      - SE E&CS TCET
      - Contact info: 
1032220162@tcetmumbai.in

# Introduction 
  
  Problem Statement - Build a model to predict the weather condition text (Sunny, Rainy, etc.) based on current temperature, wind speed, pressure, and humidity. Metrics: Accuracy, Confusion Matrix.

The objective of this project is to build a machine learning model capable of predicting weather conditions based on key atmospheric parameters such as temperature, wind speed, pressure, and humidity. The model aims to classify weather conditions into categories such as Sunny, Rainy, etc.
Weather conditions such as Sunny, Rainy, Cloudy, or Snowy are determined by a combination of factors including temperature, wind speed, pressure, and humidity. By leveraging historical weather data, we aim to train a predictive model that can classify current weather conditions based on these parameters.
Our goal is to develop a reliable and efficient model that can contribute to improving weather forecasting accuracy, ultimately benefiting various industries and enhancing the overall quality of life.

# Dataset Description

Our dataset contains historical weather records from various locations across 196 countries. The data covers a wide range of atmospheric parameters and weather conditions, providing insights into past weather patterns and trends.
Here is the breakdown of all the Features present in our Dataset

- country: Name of the country where the weather data was recorded.
- location_name: Name of the location within the country where the weather data was recorded. (Mostly Capitals of the Country)
- latitude
- longitude
- timezone
- last_updated_epoch: Time when the weather data was last updated in epoch format (seconds since January 1, 1970).
- last_updated: Time when the weather data was last updated in human-readable format.
- temperature_celsius: Temperature in degrees Celsius.
- temperature_fahrenheit: Temperature in degrees Fahrenheit.
- condition_text: Description of the weather condition (e.g., Sunny, Rainy, Partly cloudy). (Target Variable)
- Wind speed in miles per hour and kilometers per hour.
- wind_degree: Wind direction in degrees.
- wind_direction: Wind direction in compass direction (e.g., ENE for East-Northeast).
- Atmospheric pressure in millibars and inches of Mercury.
- Precipitation amount in millimeters and inches.
- humidity: Relative humidity as a percentage.
- cloud: Cloud cover as a percentage.
- feels_like_celsius: "Feels like" temperature in degrees Celsius.
- feels_like_fahrenheit: "Feels like" temperature in degrees Fahrenheit.
- Visibility in kilometers and miles.
- uv_index: UV index.
- Gust speed in miles per hour and kilometers per hour.
- Air quality measurement for Carbon Monoxide, Ozone, Nitrogen Dioxide, Sulphur Dioxide, PM2.5 particulate matter, PM10 particulate Matter
- air_quality_us-epa-index: Air quality index based on US EPA standards.
- air_quality_gb-defra-index: Air quality index based on UK DEFRA standards.
- Time of Sunrise, Sunset, Moonrise, Moonset
- moon_phase: Current phase of the moon.
- moon_illumination: Illumination percentage of the moon.

Weight Correlation:
https://docs.google.com/spreadsheets/d/1-4wqP3Ghzi-b3OlvsEeVuWAYrJDk3iTY/edit?usp=drivesdk&ouid=108445299528396807744&rtpof=true&sd=true

General Data:
https://docs.google.com/spreadsheets/d/1-HOKUIZgKkhfbySmf7sPmb7O9Pmmbx2G/edit?usp=drivesdk&ouid=108445299528396807744&rtpof=true&sd=true

![image](https://github.com/krjofficial/ThinkML-TML-11/assets/98098201/caa871e3-bc8a-45c5-9903-234cdb443225)
![image](https://github.com/krjofficial/ThinkML-TML-11/assets/98098201/ce306734-d6ca-47e7-a451-1493bf774db5)


# Approach

**An overview:**
1. Understanding Machine Learning Fundamentals
2. Data Analysis and Problem Statement Examination
3. Exploration of Classification Models
4. Adoption of RapidMiner for Model Development

By combining what we learned in theory with hands-on practice, we developed a strong approach to solve our weather prediction challenge. We started by learning the basics of machine learning and then studied our data and problem carefully. After realizing that our task fits into a classification problem, we explored different types of classification methods.
We then used RapidMiner to actually build our model.

# Results 

We have considered the first 1000 rows from our dataset for training.
Upon analyzing our data and experimenting with various classification models, we observed distinct performance differences among the models evaluated.

**Initial Assessment:**
Models like Naive Bayes, Decision Trees, and Random Forest showed lower accuracy initially.

Naive Bayes(Intial trial):
https://docs.google.com/spreadsheets/d/1-SSmurgyxJ_3cmwg_03Gh-nt1kpPH67g/edit?usp=drivesdk&ouid=108445299528396807744&rtpof=true&sd=true

On the other hand, Generalized Linear Model (GLM) and Deep Learning stood out with better accuracy.
![image](https://github.com/krjofficial/ThinkML-TML-11/assets/98098201/817ad7a1-4977-462c-876c-09bb02f233d3)


**Further Comparison:**
To confirm our findings, we directly compared GLM and Deep Learning.
GLM had an accuracy of 67.3%, while Deep Learning performed better with 69.3% accuracy.
![image](https://github.com/krjofficial/ThinkML-TML-11/assets/98098201/98f87642-f4d5-4612-9c43-0adcbc728ff7)

Accuracy: 
![image](https://github.com/krjofficial/ThinkML-TML-11/assets/98098201/b888d09c-2243-4ad4-ac8f-4cf0eb6ceb49)

Confusion Matrix:
![image](https://github.com/krjofficial/ThinkML-TML-11/assets/98098201/ac8aff6f-4efd-4164-9763-99ba6a487d05)

**Conclusion:**
Our analysis revealed that Deep Learning was the most effective model for predicting weather conditions accurately. Although we aimed to improve accuracy further using Jupyter Notebook, time constraints prevented us from completing this task. Nonetheless, these results highlight the potential of Deep Learning in addressing weather prediction challenges, paving the way for future advancements.

# References

https://www.youtube.com/watch?v=yN7ypxC7838

https://www.youtube.com/watch?v=nKW8Ndu7Mjw

https://youtu.be/TyvYZ26alZs?si=8QCgJDxSRemSAz34

https://youtu.be/2sff9uQZw8Q?si=YaU1Xp4W8Gaqelz5

https://youtu.be/IzcX9bTJLj8?si=ZC-0zWyxnXlwv4a0

https://youtu.be/zpIX09VdvYo?si=JRcU31yfFo1q1OqV

https://towardsdatascience.com/weather-forecasting-with-machine-learning-using-python-55e90c346647

Documentation and Tutorials available in the Rapidminer Studio.





