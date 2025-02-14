Project Overview:

This project focuses on predicting house prices in Bangalore using machine learning techniques. The goal is to build a robust predictive model by performing data cleaning, feature engineering, and outlier removal. The dataset used contains real estate data with key features such as location, size, total square feet, number of bathrooms, and price.

Dataset:

The dataset, Bengaluru_House_Data.csv, consists of 13,320 records and 9 features related to properties in Bangalore. Key features include:
Location,
Size (in BHK),
Total Square Feet,
Number of Bathrooms,
Price.

Project Steps:

1. Data Preprocessing:
Dropped unnecessary columns (area_type, society, balcony, availability).
Handled missing values by removing rows with null entries.
Extracted the number of bedrooms (bhk) from the size column.
Converted total_sqft into a numerical format for analysis.

2. Feature Engineering:
Calculated price per square foot (price / total_sqft) as a key metric.
Grouped locations with fewer than 10 occurrences into a single category (other) to reduce noise.

3. Outlier Detection & Removal:
Removed unrealistic properties where total_sqft / bhk < 300.
Eliminated outliers in price per square foot using statistical methods.

4. Exploratory Data Analysis (EDA):
Visualized house prices in specific locations using scatter plots.
Compared price per square foot across different locations to identify trends.

5. Model Training & Evaluation:
Applied machine learning models, including Linear Regression and Decision Tree.
Evaluated model performance using appropriate metrics.

Technologies Used:

Python Libraries:  Pandas, NumPy (Data Manipulation),
Matplotlib, Seaborn (Data Visualization),
Scikit-Learn (Machine Learning).
