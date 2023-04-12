Multiple linear regression involves predicting the value of a variable based on the values of other variables. The model assumes a linear relationship between the output variable and the predictor variables.

Autoregressive models assume a linear relationship between the value of a variable at time t and its past values at times t−1,t−2,...,t−p,...,2,1,0. The autoregressive equation for a lag order p is yt=c+β1yt−1+β2yt−2+...+βpyt−p+ϵt, where ϵt is the error term.

For an AR(1) model, β1=0 indicates random data, β1=1 and c=0 indicates a random walk, and β1=1 and c≠0 indicates a random walk with a drift. Autoregressive models are typically used for stationary time series where −1<β1<1.

A pure Moving Average (MA) model represents a time series as yt=m+ϵt+ϕ1ϵt−1+ϕ2ϵt−2+...+ϕqϵt−q, where ϕq is the residual error at time t.

To make a non-stationary time series stationary, differencing is the most commonly used method. ARIMA models take into account all three mechanisms mentioned above and represent a time series as 
            yt=α+β1yt−1+β2yt−2+...+βpyt−p+ϵt+ϕ1ϵt−1+ϕ2ϵt−2+...+ϕqϵt−q.
# Time-series-forecasting-python
