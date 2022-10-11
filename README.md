# AirbnbRioDeJaneiro

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.  The code should run with no issues using Python versions 3.*.

## Project Motivation<a name="motivation"></a>

This is my first project of the nanodegree Data Scientist on Udacity, and for this project, I was interestested in using Aribnb quarterly data set to better understand:

1. What is the most expansive neighbourhood in Rio de Janeiro?
2. What time of the year has the higher rental prices?
3. What features that influence the property pricing?
4. How are the listings distributeds on Rio de Janeiro?
5. How to choose a model to try predict the price of Rio's listings?


## File Descriptions <a name="files"></a>

### [Select relevant information and basic data-cleaning](https://github.com/zaninth/AirbnbRioDeJaneiro/blob/main/1%20Relevant%20information%20and%20basic%20data%20cleaning.ipynb)

- Selection of relevant features and columns.
- Elimination of unpleasant characters and correction of data types.
- Removing neighbourhood column and renaming neighbourhood_cleansed column to neighbourhood, beacuse there was where the real data was stored.
- Cleaning the feature amenities and creating a little barchart to try out understand the amenites column. 

### [Data Understanding & Preparation](https://github.com/zaninth/AirbnbRioDeJaneiro/blob/main/2%20Data%20understanding%20and%20Data%20preparation.ipynb)

- Identifying outliers on princing and how they will affect analyses.
- Histograms of the price and the price per accommodate.
- Percentage of null values in numerical and categorical features.
- Histograms of numerical features.
- Number of data points per category in categorical features.
- Creation of the variable price for accommodation.
- Elimination of variables with more than 95% of null values.
- Filling in the null values with the median in numerical characteristics.
- Filling in the null values with the mode in categorical characteristics.
- Extract month from dates column anda preparation from Calendar data.
- Removing adjusted_price column and using only price, to better formart the model, and trying to avoid confusions.
- Detection and elimination of outliers with IQR.

### [Airbnb Model Pricing ML](https://github.com/zaninth/AirbnbRioDeJaneiro/blob/main/3%20airbnb%20Model%20Pricing%20ML.ipynb)

- Fit dummies and categorical features.
- Implementation of Linear Regression.
- Implementation of Random Forest.
- Evaluation utilizing RMSE.
- Plot of true and predicted values.

### [Business Questions](https://github.com/zaninth/AirbnbRioDeJaneiro/blob/main/4%20Business%20questions.ipynb)

- Visualize the data to interpret the room_type and their mean price for each type.
- Visualize and understand the distriution of pricing among the each room type.
- Visualize the spatial data on Rio de Janeiro Map.
- Visualize prince per month and std variation of price.
- Price difference in each room type based on superhost.

### [Expansive Neighbourhoods](https://github.com/zaninth/AirbnbRioDeJaneiro/blob/main/5%20most_expansive.ipynb)

- Exploring neighbourhoods pricing with outliers.
- Visualize price per neighbourhood on barchart.

### [Expansive Neighbourhoods without outliers](https://github.com/zaninth/AirbnbRioDeJaneiro/blob/main/6%20most_expansive_without_outliers.ipynb)

- Exploring neighbourhoods pricing without outliers.
- Visualize price per neighbourhood without outliers on barchart.

### [Notebook Complete](https://github.com/zaninth/AirbnbRioDeJaneiro/blob/main/7%20COMPLETE.ipynb)

- A complete notebook with most part of codes, not necessarly on the orderd.

## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](link do medium).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to Inside Airbnb for the data.  You can find the Licensing for the data and other descriptive information at the Inside Airbnb link available [here](http://insideairbnb.com).  Otherwise, feel free to use the code here as you would like!!


