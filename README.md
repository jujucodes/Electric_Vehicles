# Electric_Vehicles

Model type | Features | Training Set Model Score | Testing Set Model Score | RMSE | Data Types
--- | --- | --- | --- | --- | ---
Linear Regression | Month | 0.0089 | -0.196 | 530.2 | datetime
Linear Regression | Year | 0.4537 | -5.57 | 1242.74 |datetime
Linear Regression | Month, Year | 0.4609 | -5.3 | 1217.01 | datetime
Ordinary Least Squares | Month, Year, Diff | 0.65 | __ | __ | float
Linear Regression | prev_day | 0.423 | 0.319 | 400.1 | float
Linear Regression | prev_day, diff | 1.0 | 1.0 | 1.676 | float
Ordinary Least Squares | lag 1 | 0.113 | __ | __| float
Ordinary Least Squares | lag 1 – lag12 | 0.454 | __ | __| float
Linear Regression | lag _1 – lag_12 | 0.081| 0.195 | 434.88 | float
Linear Regression | prev_day, diff, lag _1 – lag_12 | 1.0| 1.0 |5.066e -13 | float
