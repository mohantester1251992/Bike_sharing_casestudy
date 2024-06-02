
# Bike Sharing Demand Prediction

## Project Overview
This project involves building a multiple linear regression model to predict the demand for shared bikes. The goal is to help the bike-sharing provider, BoomBikes, understand the factors affecting bike demand and prepare for the post-pandemic market. The analysis will provide actionable insights to optimize operations and meet customer demand effectively.

## Case Study Goal
BoomBikes has contracted a consulting company to understand the factors on which the demand for shared bikes depends. Specifically, they want to know:
- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe bike demand.

## Dataset
The dataset used in this project contains daily bike rental counts along with various features such as weather conditions, seasonal information, and other relevant factors. The dataset includes the following columns:
- instant: Record index
- dteday: Date
- season: Season (1:spring, 2:summer, 3:fall, 4:winter)
- yr: Year (0: 2018, 1:2019)
- mnth: Month (1 to 12)
- holiday: Whether the day is a holiday (1) or not (0)
- weekday: Day of the week
- workingday: Whether the day is a working day (1) or not (0)
- weathersit: Weather situation (1: Clear, 2: Misty, 3: Light Snow/Rain, 4: Heavy Rain/Snow)
- temp: Temperature in Celsius
- atemp: Feeling temperature in Celsius
- hum: Humidity
- windspeed: Wind speed
- casual: Count of casual users
- registered: Count of registered users
- cnt: Total rental bikes (casual + registered)


## Steps Followed
1. **Data Exploration and Cleaning:**
   - Loaded and inspected the dataset.
   - Conducted exploratory data analysis (EDA) to understand the relationships between variables.
   - Preprocessed the data, including encoding categorical variables and handling missing values.

2. **Model Building:**
   - Split the data into training and testing sets.
   - Built a multiple linear regression model to predict bike demand.

3. **Model Evaluation:**
   - Evaluated the model using R-squared and RMSE metrics.
   - Conducted residual analysis to validate the assumptions of linear regression.

4. **Insights and Conclusions:**
   - Identified significant features affecting bike demand.
   - Provided actionable insights for the business to optimize their operations and meet customer demand.

## Key Findings and Conclusion
- The most significant variables impacting bike demand are year, temperature, and feeling temperature.
- The model demonstrates a good fit with the data, explaining approximately 80% of the variance in bike demand on the test set.
- By understanding these factors, BoomBikes can strategically plan their operations, increase their fleet during high demand periods, and improve marketing efforts during favorable weather conditions.



## Contact
For further information, please contact mohan.s at mohantester1251992@gmail.com.
