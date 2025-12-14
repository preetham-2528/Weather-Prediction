**Weather Prediction using ML Algorithms**

**Objective** 
To predict a specific weather condition, primarily daily temperature, for a region using historical weather data.

**Dataset**
The project utilized the Kaggle Weather Dataset, which contains 96,453 instances and 12 features, including Temperature (C), Humidity, Wind Speed (km/h), and Precip Type.


**Data Processing**

Missing values in Precip Type were handled by filling them with the mode.

New features like year, month, day, and dayofweek were engineered from the date feature.

Outliers in features such as Humidity, Temperature, Wind Speed, and Pressure were addressed by replacing them with lower and higher boundaries.


Numerical features were standardized using StandardScaler.


**Models & Performance**

Two regression models were trained and evaluated: Linear Regression and Random Forest Regressor.

Linear Regression performed poorly, achieving an R² score of approximately 66% (0.6604).

Random Forest Regressor significantly outperformed the linear model, achieving a high R² score of approximately 97% (0.9720).


**Conclusion** 
The Random Forest Regressor was the superior model, as it was better suited to capture the non-linear relationships and complex patterns present in the weather data compared to the Linear Regression model.
