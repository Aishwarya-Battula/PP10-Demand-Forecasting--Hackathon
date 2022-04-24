# PP10-Demand-Forecasting--Hackathon

It is a delivery company which operates in multiple cities delivering to the warehouses in these cities.
The client wants you to help the company with demand forecasting for upcoming weeks to the warehouses so that they can plan to deliver required amount of stock to the particular warehouse.

The weekly_forecast as well daily_forecast data is missing in the test set. Also, the train set was missing weekly_forecast for a few IDs.

Steps:
1) Obtain weekly_forecast for IDs that are missing it in the train data
2) Obtain daily_forecast on test data
3) Obtain weekly_forecast on test data

Obtained Results: Random Forest regressor(n_estimators=15) has been used for predictions on the test data based on the Mean Absolute Error(MAE) and R2 score of 0.93 obtained during cross validation.
