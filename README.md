# Airpassenger_prediction
textbf{Situation}: This was an in-class competition where we had to predict airplane load for particular flights for an airplane, demand forecasting.

Task: The goal of the competition was to reach the lowest RMSE and the main challenge came from the very small initial data set. We only had access to the date, departure, arrival, and weather data of the flights. The initial benchmark with this data and a random forest was 0.6 RMSE, a competitive RMSE was 0.3. The key objectives were data retrieval, feature engineering and modeling. 

Problems: We hit a wall for performance at 0.35 RMSE and could either try and build an even more complexes models or focus more on feature engineering and retrieval.

Innovative/Data-driven: Became innovative with our transformations. Two main ideas were using number of days to holidays and the other was target encoding connection between cities.

Result: We achieved an RMSE 0.25, second in the rankings, but what set us apart got us the highest overall grade for the project was the fact that our model had a training and prediction time 20 times shorter than the top ranked group, 250s vs 5000s, because we prioritized feature engineering and quality data rather than overly complex and heavy models. This in the end was much better suited to the business context for the airlines.
