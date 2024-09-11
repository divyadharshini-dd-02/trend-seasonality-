1. The original time series
2. The estimated trend component
3. The estimated seasonality component
This code uses a centered moving average for odd d and a "almost-centered" moving average for even d to estimate the trend.
 Then, it calculates seasonality by dividing the original time series by the trend estimate.
