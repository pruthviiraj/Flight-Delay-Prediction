# Predicting Flight Delays: An Exploratory Data Analysis

# Project Overview

This project aims to predict flight delays using machine learning models, which is crucial for airlines to optimize operations and for passengers to better plan their travel. The dataset used for this project contains 2008 flight data, with features such as flight numbers, airline carriers, departure and arrival delays, and other flight-related information.

**Models Used:**

Logistic Regression

Decision Tree

Deep Neural Networks (DNN)

The models were trained, tested, and evaluated based on accuracy, precision, recall, and F1-score. The Logistic Regression model outperformed others with an accuracy of 66.44%.

# Dataset

Source: Kaggle - Airline Delay Causes

Size: Over 1.9 million records from 2008, with 29 variables providing detailed flight information.

Key features:

Flight number, Carrier (airline), Departure and Arrival delays (target variables), Date, Airports, Flight Distance, etc.

# Data Processing

The data was cleaned and preprocessed using Python libraries like pandas and numpy. Key steps in the data cleaning process:

	1.	Removal of irrelevant or superfluous columns (e.g., ‘Year’, ‘Month’, ‘CancellationCode’).
 
	2.	Dropped rows with missing values in essential columns.
 
	3.	Encoding categorical variables for machine learning models.

**Correlation Analysis**

A correlation matrix was generated to identify relationships between various features, aiding feature selection.

# Model Descriptions

1. Logistic Regression

	•	A binary classification algorithm used for its simplicity and effectiveness in prediction.

	•	Accuracy: 66.4%

3. Decision Tree

	•	A versatile model that provides interpretability.

	•	Accuracy: 58%

5. Deep Neural Networks (DNN)

	•	Built using the Keras API, DNN is a powerful model capable of learning complex patterns.

	•	Accuracy: 65%

# Visualizations

**Flights per Carrier:** Bar plot showing the number of flights for each carrier.

**Average Delay per Carrier:** Bar plot visualizing which carriers have the highest average delays.

**Distribution of Arrival and Departure Delays:** Histograms used to visualize delay times and identify data skewness.

**Scatter Plot & Correlation Matrix:** Helped to explore relationships between key variables.

# Model Evaluation

The models were evaluated using various metrics:

Accuracy: Logistic Regression (66.4%), DNN (65%), Decision Tree (58%)

Precision, Recall, F1-Score: These were used to provide deeper insights into the performance, especially considering the imbalanced nature of the dataset.

# Conclusion and Future Work

Machine learning models, especially Logistic Regression, proved to be effective in predicting flight delays. However, improvements can be made:

Hyperparameter Tuning: Adjusting model settings could yield better results.

Handling Data Imbalance: Techniques like SMOTE could improve performance.

Feature Engineering: Creating new features from existing data could enhance model predictions.

Incorporating Weather Data: Integrating real-time data could provide more accurate delay predictions.

# Future Enhancements

Tackle data imbalance by using advanced techniques.

Include additional real-time features, such as weather conditions.

Experiment with ensemble methods and more complex neural network architectures.
