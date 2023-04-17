# sf-housing-premium-prediction
Project Authors- Vaaridhi Mathur, Yu Zhang, and Rohith Reddy

## Project Overview

The goal of this project is to determine the price premium for the zip codes in San Francisco County. We also want to determine how price varies with other factors such as size, number of rooms, parking availability, etc. To achieve this, we have developed linear regression models. We selected variables based on business relevance and initial exploratory data analysis (EDA). We tried various models with functional transformations (log-lin and log-linear) and interaction terms. For example, we considered the interaction between no. of beds and floor space, age, floor space, etc. In addition to this, our aim is also to predict house prices in various districts in San Francisco. We have created Random Forest, Gradient Boosting, and Neural Network models for the same. We have compared the mean absolute percentage error (MAPE) for them to determine which can be used for business by various stakeholders.

## Results

The linear regression model showed that zip code 94014 had the lowest coefficient, so we used it as the base and adjusted the coefficients of other zip codes. This allows us to compare the price premiums easily. We observed that people are paying a premium of $1.8Mn to live in zip code 94123 (Presidio) compared to zip code 94014 for a similar configuration of the house (i.e., the same number of bedrooms, bathrooms, floor space, etc.). This insight can be seen in the below visualization. 

Overall, our findings provide valuable insights for real estate professionals and potential buyers looking to understand housing premiums in a given zip code by easily drawing a contrast between the property prices in different zip codes. It also helps real estate firms make more accurate property valuations by identifying variables that influence variation in price, for example - views, parking, number of rooms, and floor space. 
