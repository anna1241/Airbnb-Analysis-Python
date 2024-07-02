# Airbnb Analysis Python

## Overview

In this analysis, we explored a dataset of Airbnb listings in New York City to gain insights into various aspects of the rental market. Our key findings and insights are detailed below.

## Key Findings

1. **Price Distribution**: The distribution of prices shows that the majority of listings fall within the $100-$300 range. This indicates that budget-friendly options are readily available for travelers.

2. **Accommodates**: The average number of guests that a listing can accommodate is 3.3 people. This suggests that Airbnb is a suitable option for both solo travelers and small groups.

3. **Review Activity**: The time series plot of reviews over time reveals a steady increase in review activity, indicating the growing popularity of Airbnb in New York City.

4. **Top Neighborhoods**: The top 10 neighborhoods with the highest number of listings include popular tourist destinations such as Midtown, Harlem, and Brooklyn.

5. **Review Scores**: The distribution of review scores shows that a significant portion of listings have received high ratings, suggesting overall positive experiences for guests.

6. **Feature Importance**: The Random Forest model identified the most important features for predicting price, including the number of bedrooms, bathrooms, accommodates, and review scores. These findings can be utilized by hosts to optimize their listings and improve their chances of securing bookings.

## Limitations

1. **Data Quality**: The dataset contained missing values and inconsistencies, which required careful preprocessing and cleaning.

2. **Model Accuracy**: While the Random Forest model achieved a reasonable accuracy of 84%, there is still room for improvement. Further exploration of different models and hyperparameter tuning could potentially enhance the predictive power.

3. **External Factors**: The analysis did not consider external factors such as seasonality, events, or economic conditions, which could influence the rental market.
