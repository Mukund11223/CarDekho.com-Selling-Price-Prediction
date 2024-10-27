# CarDekho.com-Selling-Price-Prediction
Used Car Price Prediction

Problem Statement

This project aims to predict the selling price of used cars based on their features. The dataset is sourced from cars listed on CarDekho.com in India. By building a predictive model, we provide new sellers with price suggestions based on current market conditions.

Table of Contents

	•	Problem Statement
	•	Data Collection
	•	Data Preprocessing
	•	Exploratory Data Analysis (EDA)
	•	Model Training and Selection
	•	Evaluation Metrics
	•	Technologies Used

Data Collection

The dataset was collected by web scraping CarDekho’s website, containing information on used cars sold in India. It comprises:

	•	Rows: 15,411
	•	Columns: 13

Data Preprocessing

To prepare the data for analysis and modeling, we conducted several preprocessing steps:

	1.	Handling Missing Values: Checked and managed any missing data.
	2.	Removing Duplicates: Ensured data consistency by removing duplicate entries.
	3.	Data Type Check: Verified and adjusted data types as necessary.
	4.	Feature Encoding: Applied One Hot Encoding to categorical columns with a low number of unique values and where categories were not ordinal.
One Hot Encoding is used to convert categorical variables into a format suitable for machine learning algorithms, thereby enhancing the model’s prediction accuracy.
	5.	Feature Scaling: Scaled features to ensure all variables contribute proportionately to the predictions.

Exploratory Data Analysis (EDA)

An in-depth EDA was conducted to understand data distributions, correlations, and insights. This helps identify patterns and trends within the dataset.

Model Training and Selection

The following regression algorithms were explored for training the model:

	•	Random Forest Regressor
	•	Linear Regression
	•	Ridge Regression
	•	Lasso Regression
	•	K-Nearest Neighbors Regressor
	•	Decision Tree Regressor

Evaluation Metrics

Models were evaluated using the following metrics:

	•	R² Score: Indicates the proportion of variance explained by the model.
	•	Mean Absolute Error (MAE): Measures the average magnitude of errors.
	•	Mean Squared Error (MSE): Indicates the average squared error.

Technologies Used

	•	Python for programming
	•	scikit-learn for machine learning algorithms
	•	Pandas, NumPy for data manipulation
	•	Matplotlib, Seaborn for data visualization
