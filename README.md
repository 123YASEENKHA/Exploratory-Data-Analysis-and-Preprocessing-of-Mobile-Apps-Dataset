# Exploratory-Data-Analysis-and-Preprocessing-of-Mobile-Apps-Dataset
This project conducts EDA and preprocessing on a mobile apps dataset using Python. Exploring features like ratings, reviews, categories, sizes, installs, and prices, it includes importing libraries, data checking, cleaning, handling missing values, outliers, and encoding categorical columns.
Overview:
This project performs Exploratory Data Analysis (EDA) and preprocessing on a mobile apps dataset using Python. The dataset encompasses various features like ratings, reviews, categories, sizes, installs, and prices. The analysis involves essential tasks such as data cleaning, handling missing values, outliers, encoding categorical columns, and preparing the dataset for model building.

Project Structure:

Import Libraries and Read Dataset:
Utilized Pandas, NumPy, Seaborn, and Matplotlib.
Loaded the dataset into a Pandas DataFrame.

Data Exploration:
Checked first/last few samples, shape, and info of the data.

Familiarized with different features.
Summary Statistics:
Examined summary statistics and identified columns for model building.

Handling Duplicates:
Checked and dropped duplicate records.

Handling Invalid Categories:
Checked unique categories of the 'Category' column.
Dropped invalid categories.
Handling Missing Values and Creating 'Rating_category':

Dropped missing values in the 'Rating' column.
Created a new column 'Rating_category' based on ratings.

Distribution of 'Rating_category':
Checked the distribution of the newly created column.Handling Outliers in 'Reviews':
Converted 'Reviews' to numeric data type.
Handled outliers using log transformation.

Treating 'Size' Column:
Treated non-numeric data and converted the column.

Treating 'Installs' Column:
Cleaned unwanted characters and converted the column.

Treating 'Price' Column:
Removed unwanted characters and converted the column.
Dropping Redundant Columns:
Dropped redundant columns for analysis.

Encoding Categorical Columns:
Applied Label Encoding to categorical columns.
Segregating Target and Independent Features:
Separated target ('Rating_category') and independent features.

Splitting the Dataset:
Split the dataset into training and testing sets.
Usage:
Clone the repository.
Run the notebook sequentially for EDA and preprocessing.
Explore the detailed steps and insights into the dataset.

Requirements:
Python 3.x
Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn.

Contributor:
ABDUL YASEEN.
Feel free to contribute and use this project for further analysis!
