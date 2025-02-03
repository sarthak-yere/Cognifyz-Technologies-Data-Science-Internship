# Cognifyz-Technologies-Data-Science-Internship
Data Science Internship - Restaurant Dataset Analysis
This repository contains the work I completed during my Data Science internship, where I analyzed a restaurant dataset. The analysis spanned multiple tasks, from basic data exploration and preprocessing to predictive modeling. Below are the tasks I completed and the corresponding steps involved.

Table of Contents
Project Overview
Level 1: Data Exploration & Preprocessing
Level 2: Advanced Analysis
Level 3: Predictive Modeling & Visualization
Technologies and Tools Used
Installation Instructions
How to Run the Code
Acknowledgements

Project Overview
During my internship, I worked on a dataset of restaurant information and performed various data science tasks. The goal was to extract insights, analyze relationships, and build predictive models. The tasks ranged from data preprocessing to advanced predictive modeling, and they helped me gain hands-on experience in data exploration, feature engineering, and machine learning.

Level 1: Data Exploration & Preprocessing

Task 1: Data Exploration and Preprocessing
Dataset Exploration: Analyzed the dataset to identify the number of rows and columns.
Handling Missing Values: Checked for missing values in each column and applied appropriate strategies to handle them.
Data Type Conversion: Converted columns to the appropriate data types, such as changing date columns to datetime format or numerical columns to float.
Target Variable Analysis: Explored the distribution of the target variable ("Aggregate rating") to identify any class imbalances.

Task 2: Descriptive Analysis
Statistical Measures: Calculated basic statistical measures (mean, median, standard deviation, etc.) for numerical columns.
Categorical Variable Exploration: Explored categorical variables like "Country Code," "City," and "Cuisines" to understand their distributions.
Top Cuisines and Cities: Identified the top cuisines and cities based on the highest number of restaurants.

Task 3: Geospatial Analysis
Location Visualization: Visualized the locations of restaurants on a map using latitude and longitude data.
City and Country Distribution: Analyzed the distribution of restaurants across different cities and countries.
Location vs. Rating: Investigated any potential correlation between the restaurant’s location (e.g., city or country) and its aggregate rating.

Level 2: Advanced Analysis

Task 1: Table Booking and Online Delivery
Service Availability: Determined the percentage of restaurants that offer table booking and online delivery.
Rating Comparison: Compared the average ratings of restaurants that offer table booking vs those that don’t.
Online Delivery by Price Range: Analyzed the availability of online delivery among restaurants with different price ranges.

Task 2: Price Range Analysis
Most Common Price Range: Identified the most common price range among all the restaurants.
Average Rating by Price Range: Calculated the average rating for each price range.
Best Color for Highest Rating: Identified the color corresponding to the highest average rating among different price ranges.

Task 3: Feature Engineering
Additional Features: Extracted additional features such as the length of restaurant names or addresses.
New Features Creation: Created new binary features like "Has Table Booking" and "Has Online Delivery" by encoding categorical variables.

Level 3: Predictive Modeling & Visualization

Task 1: Predictive Modeling
Regression Model: Built a regression model to predict the aggregate rating of a restaurant based on various available features.
Model Evaluation: Split the dataset into training and testing sets, evaluated model performance using appropriate metrics (e.g., RMSE, MAE).
Algorithm Comparison: Experimented with different algorithms (e.g., Linear Regression, Decision Trees, Random Forest) and compared their performance.

Task 2: Customer Preference Analysis
Cuisine vs. Rating: Analyzed the relationship between the type of cuisine and the restaurant's rating.
Popular Cuisines: Identified the most popular cuisines based on the number of votes.
Cuisines with Higher Ratings: Investigated if certain cuisines tend to receive higher ratings.

Task 3: Data Visualization
Distribution of Ratings: Created visualizations (e.g., histograms, box plots) to represent the distribution of ratings.
Cuisine/City vs. Rating: Compared the average ratings of different cuisines and cities using appropriate visualizations (e.g., bar plots, violin plots).
Feature vs. Rating: Visualized the relationship between various features (e.g., price range, table booking) and the target variable (aggregate rating).

Technologies and Tools Used
Programming Languages: Python
Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, GeoPandas, Folium, plotly
Data Handling: Jupyter Notebooks
Version Control: Git, GitHub
Other Tools: Excel, Google Colab

Installation Instructions:
To run the code in this repository, follow these steps:

1.Clone the repository to your local machine:
git clone https://github.com/yourusername/repositoryname.git
2.Navigate to the project directory:
cd repositoryname
3.Install the required dependencies using pip:
pip install -r requirements.txt
If requirements.txt is not available, you can manually install the necessary libraries, such as:
pip install pandas numpy matplotlib seaborn scikit-learn geopandas folium xgboost

How to Run the Code
1.Open the Jupyter Notebooks or Python scripts in your preferred IDE (e.g., VS Code, JupyterLab).
2.Run the cells or the script in sequence to execute the tasks.

Acknowledgements
Thanks to Cognifyz Technologies for providing the internship opportunity and mentorship throughout the project.


