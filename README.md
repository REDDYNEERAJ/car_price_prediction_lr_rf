Used Car Price Prediction

This project predicts the resale price of used cars based on a dataset from Kaggle. It includes exploratory data analysis (EDA), feature engineering, data preprocessing, and machine learning modeling using Linear Regression and Random Forest Regressor.

Dataset

The dataset contains details of used cars, including:

Name

Location

Year of Manufacture

Kilometers Driven

Fuel Type

Transmission

Owner Type

Mileage

Engine

Power

Seats

New Price

Selling Price (Price)

Features Engineering

Extracted manufacturer from car names.

Converted Year to car age.

Extracted numeric values from Mileage, Engine, and Power.

Handled missing values in Mileage, Engine, Power, and Seats.

Dropped irrelevant columns: Name, Location, New_Price.

Data Processing

Converted categorical columns (Manufacturer, Fuel_Type, Transmission, Owner_Type) into dummy variables.

Standardized numerical features using StandardScaler.

Models

Linear Regression

R² Score: ~0.70

Random Forest Regressor

R² Score: ~0.88 (best performing model)

Libraries Used

pandas, numpy – data manipulation

matplotlib, seaborn – visualization

sklearn – preprocessing, model training, evaluation

datetime – handle year-to-age conversion

How to Run

Clone the repository:

git clone https://github.com/yourusername/used-car-price-prediction.git


Install required packages:

pip install -r requirements.txt


Run the notebook:

jupyter notebook Used_Car_Price_Prediction.ipynb

Results

Random Forest Regressor achieved the best prediction performance with an R² score of 0.88.

Model can be used to predict the resale price of a car given its specifications.
