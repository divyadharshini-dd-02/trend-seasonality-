1. The original time series
2. The estimated trend component
3. The estimated seasonality component
This code uses a centered moving average for odd d and a "almost-centered" moving average for even d to estimate the trend.
 Then, it calculates seasonality by dividing the original time series by the trend estimate.
First import necessary library
using def function for estimate trend and estimate seasonality, Y is input dataset form kaggel ,that data which have trend and seasonality.

assuming the d,  if optization of d , if d is even or off, d-1,d,d+1.
plt the graph
