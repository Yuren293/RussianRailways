Research practice. Case from Russian Railways.

###### Solution 1 Description :
1. Analyzed the predictability of the time series of the number of railcars in the directions of the Russian Railways
2. Conducted a series analysis for predictability, analysis of the cluster structure of the series, analysis of various predictive models, produced feature engineering and built
a pipeline for forecasting the series 
3. General conclusions and ways of solving problems for forecasting were made.

###### Solution 2 Description :
1. The original dataset was converted into a dataset describing some event model that describes events that occurred with wagons with a sampling rate of 1 hour
2. After that, the model is trained using the sliding window method. The model predicts the target value after the nth number of hours.
3. The target value is predicted 36 hours ahead for the current day. 
4. A prediction is made for 24 hours for 100 different days 
