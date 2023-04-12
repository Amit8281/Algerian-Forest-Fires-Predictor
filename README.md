![alt text](image URL)
# Algerian Forest Fires Dataset
This dataset contains weather observations and Fire Weather Index (FWI) data for Algerian forest fires during the months of June to September in the year 2012. The dataset includes the following columns:

- Date: Date in DD/MM/YYYY format
- Day, month: Month of the year, ranging from 'june' to 'september'
- Year: Year of observation, always 2012
- Temp: Temperature at noon (temperature max) in Celsius degrees, ranging from 22 to 42
- RH: Relative humidity in %, ranging from 21 to 90
- Ws: Wind speed in km/h, ranging from 6 to 29
- Rain: Total rainfall in mm for the day, ranging from 0 to 16.8
- FFMC: Fine Fuel Moisture Code index from the FWI system, ranging from 28.6 to 92.5
- DMC: Duff Moisture Code index from the FWI system, ranging from 1.1 to 65.9
- DC: Drought Code index from the FWI system, ranging from 7 to 220.4
- ISI: Initial Spread Index index from the FWI system, ranging from 0 to 18.5
- BUI: Buildup Index index from the FWI system, ranging from 1.1 to 68
- FWI: Fire Weather Index Index, ranging from 0 to 31.1
- Classes: Two classes, namely 'Fire' and 'not Fire'
### Model Evaluation Metrics
Various regression models have been applied to the dataset to predict the FWI index. The following evaluation metrics have been used to compare the performance of different models:

- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R2 Score
- Adjusted R2 Score

### The following models have been applied to the dataset:

- Linear Regressor
- Lasso Linear Regressor
- Ridge Linear Regressor
- KNN Regressor
- Decision Tree Regressor
- SVR
- Random Forest Regressor
- Extra Tree Regressor
- AdaBoost Regressor
- Gradient Boosting Regressor
- XGB Regress

### The following regression models were evaluated:

- Linear Regressor: MSE=0.50, MAE=0.48, RMSE=0.70, R2 Score=0.98, Adjusted R2 Score=0.98
- Lasso Linear Regressor: MSE=2.0, MAE=1.08, RMSE=1.41, R2 Score=0.95, Adjusted R2 Score=0.94
- Ridge Linear Regressor: MSE=0.52, MAE=0.49, RMSE=0.72, R2 Score=0.98, Adjusted R2 Score=0.98
- KNN Regressor: MSE=2.22, MAE=0.99, RMSE=1.49, R2 Score=0.94, Adjusted R2 Score=0.93
- Decision Tree Regressor: MSE=2.65, MAE=0.96, RMSE=1.62, R2 Score=0.93, Adjusted R2 Score=0.92
- SVR: MSE=0.93, MAE=0.45, RMSE=0.96, R2 Score=0.97, Adjusted R2 Score=0.97
- Random Forest Regressor: MSE=0.84, MAE=0.63, RMSE=0.92, R2 Score=0.98, Adjusted R2 Score=0.97
- Extra Tree Regressor: MSE=0.59, MAE=0.50, RMSE=0.76, R2 Score=0.98, Adjusted R2 Score=0.98
- AdaBoost Regressor: MSE=2.07, MAE=1.24, RMSE=1.44, R2 Score=0.95, Adjusted R2 Score=0.94
- Gradient Boosting Regressor: MSE=0.97, MAE=0.63, RMSE=0.98, R2 Score=0.97, Adjusted R2 Score=0.97
- XGB Regressor: MSE=1.18, MAE=0.73, RMSE=1.08, R2 Score=0.97, Adjusted R2 Score=0.96


The best performing model is **Gradient Boosting Regressor** with an RMSE of 0.98, R2Score of 0.97 and Adjusted R2 Score of 0.97. However, the Linear Regressor and Ridge Linear Regressor models also perform well with an RMSE of 0.70 and 0.72 respectively. The Lasso Linear Regressor model performs the worst with an RMSE of 1.41.

Overall, the models seem to perform relatively well in predicting the FWI index from the given dataset.
