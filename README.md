# NYC_Uber_Lyft_Predictions

# NYC Uber & Lyft Demand Forecasting

This project predicts hourly Uber and Lyft demand across New York City taxi zones using historical trip activity, weather, holidays, and time-based features.

The pipeline processes approximately **239 million NYC rideshare records** using Python and DuckDB. A LightGBM model is trained on 2.2 million aggregated zone-hour observations.

## Results

* R²: **0.949**
* RMSE: **27.15 trips per zone-hour**

## Predicted Demand Map

![Predicted Uber and Lyft trips by NYC taxi zone](NYC_Taxi_Zone_Map.png)

The interactive version is available in `NYC_Taxi_Zone_Map.html`.

## Technologies

Python, DuckDB, pandas, LightGBM, scikit-learn, GeoPandas, Plotly, and Jupyter Notebook.

## Author

[Seth Breneman](https://github.com/sbreneman)
