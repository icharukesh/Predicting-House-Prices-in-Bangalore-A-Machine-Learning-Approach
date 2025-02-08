Project Description:

This project aims to predict home prices in Bangalore using machine learning techniques. It involves data cleaning, feature engineering, and outlier removal to build a robust predictive model.

Dataset:

The dataset used for this project is Bengaluru_House_Data.csv.
It contains 13,320 records and 9 features related to real estate properties in Bangalore.
Key features include location, size, total square feet, number of bathrooms, and price.

Project Steps:

Data Preprocessing:

Dropped unnecessary columns (area_type, society, balcony, availability).
Handled missing values by removing rows with null values.
Extracted the number of bedrooms (bhk) from the size column.
Converted total_sqft to a numerical format.

Feature Engineering:

Calculated price_per_sqft as price / total_sqft.
Grouped locations with less than 10 occurrences into a single category (other).

Outlier Detection & Removal:

Removed properties where total_sqft / bhk < 300 (considered unrealistic).
Removed outliers based on price per square foot using statistical methods.

Exploratory Data Analysis (EDA):

Plotted scatter charts for house prices in specific locations.
Compared price per square foot across different locations.

Model Training & Evaluation:

Applied machine learning models (Linear Regression, Decision Tree, etc.).
Evaluated score.

Technologies Used:
Python
Pandas, NumPy (Data Manipulation)
Matplotlib, Seaborn (Data Visualization)
Scikit-Learn (Machine Learning)
