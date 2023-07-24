# AirQualityIndex
Delhi Air Quality Index calculation, EDA and Regression models

<b>Dataset Link:</b> https://www.kaggle.com/datasets/deepaksirohiwal/delhi-air-quality

• Developed an algorithm to calculate the Air Quality Index (AQI) for hourly pollutant values and assigned corresponding labels based on established guidelines.
• Constructed a predictive model using the Random Forest Regressor algorithm to accurately forecast the AQI, leveraging insights gained from exploratory data analysis (EDA) and comprehensive dataset preprocessing techniques.
• Evaluated the performance of the predictive model on previously unseen data, achieving an impressive accuracy rate of 82% and demonstrating its robustness and reliability.

# Addition of calculated AQI to dataset
![image](https://github.com/Anagha0202/AirQualityIndex/assets/53923590/c4a5c645-6a8c-4263-8b3c-7daec786cc52)

# Addition of AQI labels based on AQI values
![image](https://github.com/Anagha0202/AirQualityIndex/assets/53923590/83fdfa4c-d81b-485f-8677-d6dac01f875c)

# AQI distribution 
![image](https://github.com/Anagha0202/AirQualityIndex/assets/53923590/efec72f3-6c7a-4aba-99a0-eae51e36b51f)
</br>The majority of the data points have AQI's between 0 and 150 which means that the livability condition is between Good and Unhealthy for sensitive groups.

# EDA
![image](https://github.com/Anagha0202/AirQualityIndex/assets/53923590/5f487b49-0ff6-424d-ae4b-de36398796aa)
</br>The concentration of CO in the atmosphere is greater during the weekdays of winter and autumn as compared to the weekends in those seasons, because a lot less number of trains and cars are running on weekends to commute people to and from their work.
</br>Summer and Monsoon have similar concentrations of CO during the weekdays and the weekends.
</br>As compared to other seasons, Monsoons are rightly the least polluted ones which makes sense because a lot of pollution matter are washed away from the atmosphere, flowing away the rain into the ground.

![image](https://github.com/Anagha0202/AirQualityIndex/assets/53923590/501307c6-8ae4-45c9-b11f-356cb06e9f8c)
</br>The air quality index reaches a peak during the 3:00 PM hour of the day. One of the primary reasons is the increased vehicular traffic till 3:00 PM and from then the Air quality index keeps reducing as there traffic go down.

![image](https://github.com/Anagha0202/AirQualityIndex/assets/53923590/4bdf7686-847f-4aff-b08c-355ac3f888a9)
</br>NO2 and SO2 are not directly related to CO. However, the presence of NO2 and SO2 in the air can indirectly affect the levels of CO in the atmosphere.

# Feature Importance
![image](https://github.com/Anagha0202/AirQualityIndex/assets/53923590/abd81404-c3e3-4857-b0bb-cb5db3b1961f)

# Accuracy of RandomForrestRegressor
There were 2907 number of labels correctly predicted in the test dataset out of 3643 instances, with an error scope of 16.<br>
Accuracy Percentage :  79.79687071095252


