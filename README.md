
# Project Background & Aims

Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.


## Recommendations & Conclusion

In this notebook, I have Explored the bikes data and following are the insights i have gained from this data. 

* In Winter season the Demand of Rented bike is low and High in summar.

* There is a surge of high demand in the morning 8AM and in evening 6PM as the people might be going to their work at morning 8AM and returing from their work at the evening 6PM.

* There is a High demand of bikes during sales.

* The demand is low in December January & Febuary, It is cold in these months and we have already seen in season column that demand is less in winters.

* The pattern of weekdays and weekends is different, in the weekend the demand becomes high in the afternoon. While the demand for office timings is high during weekdays, we can further change this column to weekdays and weekends.

* The Temperature, Hour & Humidity are the most important features that positively drive the total rented bikes count.

* For rented bike count Prediction we have used linear Regression model because we have regression problem here.

* Linear regression model has performed really well since the performance metrics (mse,rmse) shows lower and (r2) shows a higher value for the linear Regression.

* For the classification problem we have choosen hit sale as a target column, Hit Sale represents whether a rental had high sales or not. This target is appropriate if the problem statement involves predicting whether a rental will have high sales based on the given features.

* For Classification problem we have got amazing results with 97% accuracy.
