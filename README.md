USED CAR PRICE PREDICTION

This project predicts the resale price of used cars using machine learning. The workflow includes exploratory data analysis (EDA), feature engineering, data preprocessing, and training models such as Linear Regression and Random Forest Regressor.

DATASET
The dataset includes the following features:
- Name
- Location
- Year of Manufacture
- Kilometers Driven
- Fuel Type
- Transmission
- Owner Type
- Mileage
- Engine
- Power
- Seats
- New Price
- Selling Price (Price)

FEATURE ENGINEERING
- Extracted Manufacturer from car Name.
- Converted Year to Car Age.
- Extracted numeric values from Mileage, Engine, and Power.
- Handled missing values in Mileage, Engine, Power, and Seats.
- Dropped irrelevant columns: Name, Location, New_Price.

DATA PROCESSING
- Converted categorical columns (Manufacturer, Fuel_Type, Transmission, Owner_Type) into dummy variables.
- Standardized numerical features using StandardScaler.

MODELS
1. Linear Regression
   - R² Score: ~0.70

2. Random Forest Regressor
   - R² Score: ~0.88 (best performing model)

LIBRARIES USED
- pandas, numpy : Data manipulation
- matplotlib, seaborn : Visualization
- sklearn : Preprocessing, model training, evaluation
- datetime : Convert year to age

HOW TO RUN
1. Clone the repository:

   git clone https://github.com/yourusername/used-car-price-prediction.git
   
2. Run the notebook:

   jupyter notebook Used_Car_Price_Prediction.ipynb

RESULTS
- Random Forest Regressor achieved the best performance with R² score of 0.88.
- The model can predict resale prices of used cars based on their specifications.
