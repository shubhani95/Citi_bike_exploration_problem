# Citi Bike Exploration Problem

# Company Overview:
Citi Bike is a leading bike-sharing program that offers a flexible and reliable rental service in New York City, providing a convenient and eco-friendly transportation option for residents and visitors. Citi Bank first published its data for the public in 2013, facilitating analysis, development, visualisation and other applications. The data for this project can be accessed through the following URL: [Citi Bike NYC System Data](https://citibikenyc.com/system-data) and [Data Repository](https://s3.amazonaws.com/tripdata/index.html).

The data repository contains detailed trip data, including information on bike usage, station locations, and temporal patterns. For our analysis, we will use the data from May 2024, as it provides the most recent information on crucial trends and patterns. The data includes:

  Ride ID
  Rideable type
  Started at
  Ended at
  Start station name
  Start station ID
  End station name
  End station ID
  Start latitude
  Start longitude
  End latitude
  End Longitude
  Member or casual ride


# Project Overview: 
 In this problem, we are tasked with analysing data from Citi Bike rental company to provide insights and recommendations to optimise their operations. The company aims to understand better how bikes should be distributed among various stations and determine the optimal stock levels required to meet demand efficiently.
 
The primary goal of this analysis is to:
1. Perform Exploratory Data Analysis (EDA): Understand the available data, identify patterns, and derive insights related to bike usage.
2. Predictive Modelling: Develop a machine learning model Random Forest Regressor to predict bike demand at different stations and times.
3. Optimisation: Propose strategies to optimise the distribution of bikes across stations and manage stock levels using LinProg, ensuring that supply meets demand efficiently.
4. Recommendations: Provide actionable insights and recommendations that the company can implement to improve its operational efficiency and enhance user satisfaction.

# Repository Content:
This repository contains critical resources to help Citi Bike allocate resources and optimise based on provided metrics. Below is an overview of the contents, along with a detailed explanation of each:

# 1. citibike_exploration.ipynb
This Jupyter Notebook tackles the Bike Rental Data Science Challenge by performing Exploratory Data Analysis (EDA) to understand and visualize patterns in bike usage. It then develops a predictive model using a Random Forest Regressor to accurately forecast bike demand at various stations and times. Finally, the notebook proposes optimization strategies using Linear Programming (LinProg from scipy.optimize) to efficiently manage bike distribution and stock levels, ensuring that supply meets demand with minimal shortages or excess inventory. The solution leverages Python libraries like pandas, numpy, matplotlib, seaborn, scikit-learn, and scipy. The best way to run the Jupyter Notebook is to create a conda env with all these libraries and use that env. Refer to this page for creating and managing conda env: https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#activating-an-environment.

# 2. citi_bike_sj.pdf
This presentation summarizes the comprehensive analysis and solutions developed for the Bike Rental Data Science Challenge. We begin with an Exploratory Data Analysis (EDA) that uncovers key patterns and trends in bike usage, providing valuable insights into factors influencing demand. We then present a predictive model built using a Random Forest Regressor, which accurately forecasts bike demand across various stations and times, helping to anticipate user needs. Finally, we outline optimization strategies designed to efficiently distribute bikes and manage stock levels, ensuring a balance between supply and demand. The proposed solutions aim to minimize shortages and reduce excess inventory, ultimately improving the overall efficiency of bike rental operations. The results and actionable recommendations are presented to guide decision-making and drive operational improvements.

# 3. 202405_citibike_tripdata_5.csv.zip
Dataset: The dataset contains several key metrics that can be used for analysis, development, and visualisation. The analysis and insights provided in the code notebook and report PDF are based on this dataset.



