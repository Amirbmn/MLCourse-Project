🏠 Iranian Housing Price Prediction
This project builds a machine learning model to estimate housing prices in Iran. 
The target variable Total represents the full property value, derived from down payment and monthly rent.
 Key preprocessing steps include removing extreme outliers (top/bottom 1%) and applying log transformation to handle skewed price distribution. 
Feature engineering created 20+ new features such as Building_Age, Area_per_Room, Floor_Ratio, Is_Ground, Is_Top, and interaction features like Area_Elevator and Area_Parking. 
Categorical variables (city, district, etc.) were encoded using target encoding with smoothing (α=10) to capture price relationships while preventing overfitting.
 A Random Forest Regressor with 300 trees and max_depth=20 was trained on 80% of the data. The model achieved an R² score of 0.81.
 Feature importance analysis showed that Area, Area_Squared, and City are the strongest predictors. Technologies used: Python, pandas, numpy, and scikit-learn.
