# Rent-Predictions

**ANDROID-BASED HOUSE RENT PREDICTION  USING MACHINE LEARNING** 

The purpose of the project is to predict the prices of real estate rental using different machine learning regression methods on residential real estate. The model can give estimated rent values to proper decisions being taken by tenants and landlords by examining aspects like location, size, and property type. 

**Project Overview** 

The rental market is influenced by a complex interplay of geographic and structural factors. This repository provides a full end-to-end pipeline to: 

* Clean and preprocess urban housing data. 

* Perform feature engineering on location and property attributes. 

* Train and optimize regression models to minimize prediction error. 

 

**The Dataset** 

Typical features included in this analysis: 

* **Area/Square Footage**: The total size of the property. 

* **Location/City**: Categorical data representing neighborhoods or urban centers. 

* **BHK**: Number of bedrooms, hall, and kitchen. 

* **Furnishing Status**: Furnished, semi-furnished, or unfurnished. 

* **Tenant Preference**: Whether the property is listed for bachelors, families, or both. 

* **Point of Contact**: Who to contact for the listing. 

**Features & Workflow** 

**1. Data Cleaning & Feature Engineering** 

**Handling Outliers**: Removing extreme price points that skew the model (e.g., luxury penthouses vs. studio apartments). 

**One-Hot Encoding**: Converting categorical data like "City" and "Furnishing Status" into numerical format. 

**Feature Scaling**: Using StandardScaler or MinMaxScaler to normalize features for algorithms like KNN or SVM. 

**2. Exploratory Data Analysis (EDA)** 

Insightful visualizations to understand price drivers: 

* **Heatmaps**: To see correlation between square footage and rent. 

* **Bar Charts**: Comparing average rent across different cities or neighborhoods. 

* **Scatter Plots**: Visualizing the distribution of prices against area. 

**3. Machine Learning Models** 

We implemented and compared several regression algorithms: 

* **Linear Regression**: The baseline model for price prediction. 

* **Decision Tree Regressor**: To capture non-linear patterns in the data. 

* **Random Forest Regressor**: An ensemble method to improve accuracy and reduce overfitting. 

* **XGBoost Regressor**: Optimized gradient boosting for high-performance prediction. 

**4. Evaluation Metrics** 

Since this is a regression task, model performance is measured using: 

* **Mean Absolute Error (MAE)**: The average physical dollar amount of error. 

* **Root Mean Squared Error (RMSE)**: Penalizes larger errors more heavily. 

* **R-squared ($R^2$)**: Indicates how well the independent variables explain the variance in rent. 

 
