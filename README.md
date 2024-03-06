
# Immo-Eliza-MAS-FN-Analysis

![image](Report/image.png)

## Description
The Immo Eliza Data Analysis project focuses on analyzing a dataset of properties including houses and apartmments for sale from the website Immoweb. It involves cleaning the dataset, performing exploratory data analysis, and creating visualizations to gain insights into the properties and their characteristics.## 

## Installation
To run the project, you need to install the required libraries. You can click on the badge links to learn more about each library and its specific version used in this project. You can install them manually using pip install <library name> or just running pip install -r requirements.txt.

. Install the required libraries:

   - [![python version](https://img.shields.io/badge/python-3.x-blue)](https://python.org)
   - [![Pandas Version](https://img.shields.io/badge/pandas-2.x-green)](https://pandas.pydata.org/)
   - [![NumPy Version](https://img.shields.io/badge/numpy-1.x-orange)](https://numpy.org/)
   - [![Matplotlib Version](https://img.shields.io/badge/Matplotlib-3.x-red)](https://matplotlib.org/)
   - [![Seaborn Version](https://img.shields.io/badge/seaborn-0.x-yellow)](https://seaborn.pydata.org/)
   - [![sklearn Version](https://img.shields.io/badge/sklearn-0.x-grey)](https://scikit-learn.org/stable/)

## The dataset
It includes about 39000 properties scrapped from ImmoWeb: [Immoweb](https://www.immoweb.be) 

## Data Cleaning 
The cleaning phase is very important: without a good cleaning, our analysis could be badly influenced by outliers. 

-	Removing duplicates and empty rows
-	Removing the rows without price as a dependent variable
-	Exploring columns with some functions, and replacing or imputing missing values if needed. 
-	Removing the outliers (error, incorrect or absurd)
-	Removing some useless columns due to their high rate of *None* value. 

## Data analysis 
This is where the fun starts! 🥳

Three people know more than one.

To get the most out of our data, and to allow each of us to get experience manipulating Pandas and Seaborn, we decided to work separately. One group worked on the house data and one group on the apartment data. Later we reviewed our work and merged the results.

Our target: The Price.
The price is the target of this challenge, as our goal is to create a machine-learning model to predict prices on Belgium's sales.

Correlation between variables?
To identify the correlation, we used this heatmap:
![image](Report/heatmap_apartment.png)

![image](Report/heatmap_house.png)


*Observations*
The Price is mainly correlated with the Number of rooms, living area and energy consumption. 
The Number of rooms and living areas seem mainly correlated with each other.

## Contributors

Team members are Afaf, Miguel Bueno, Nasrin, Shweta Jain, and Fabienne.

## Timeline
This analysis took form in five days.
