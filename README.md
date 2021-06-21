# Seattle AirBnB Open Data analysis

This repository is part of the first project "Write a Data Scientist Blog Post" of the UDACITY Nanodegree "Data Scientist"


## Description of the project

The goal is to choose a dataset, point out 3-5 main questions from a given dataset, and make a basic analysis to answer
the raised questions. 
This repository covers the technical part of the analysis. The communication of the results is part of a Medium Blog Post, see https://hoseberg.medium.com/i-pack-my-ml-and-go-to-seattle-594ab48791ed

The dataset used here is the **Seattle AirBnB Open Data dataset**, see the link below for details. This dataset cotains data about hosts and accommodations in Seattle that can be booked with AirBnB. In this project, we focus on the following questions:

* What is the best location in the city to explore Seattle?
* What is the best time to travel to Seattle?
* Can we use the host's profile to see if we choose a good host?
* Can we predict the price of an accommodation based on some key indicators that are important for you?


## About this repo

This is a Python project. The used dataset is provided by kaggle, please
follow the instructions below to get the data.

This project consists of a single Jupyter Notebook. The used libraries are the following:
* pandas (library to handle datasets, see e.g.,  https://pandas.pydata.org/)
* numpy (for n-dimensional arrays, see e.g. , https://numpy.org/)
* matplotlib (for visualization, see e.g., https://matplotlib.org/)
* seaborn (statistical data visualization library, see e.g., https://seaborn.pydata.org/)
* re (python library to handle regular expressions, see, e.g., https://docs.python.org/3/library/re.html)
* scikit-learn (Machine Learning python library, see, e.g., https://scikit-learn.org/stable/) 


## Dataset

The dataset is available from kaggle, see the following link
https://www.kaggle.com/airbnb/seattle
To make use of the dataset, the dataset has been downloaded and the .csv files are located right
next to the Jupyter Notebook.

Please check the link for the license of the dataset.


## License

The code is free for any usage. For the license of the dataset, please check the link above.


## Conclusion

For all 4 questions listed above, this repository covers statistics and ML models to answer the questions.  
Depending on the price, we pointed out the best districts to stay and the best seasons to visit Seattle. In addition, we selected a number of features and tried to use these to check if a host is good or not, however, no significant correlation between the features and host reviews could be found. Finally, we were able to find a Linear Regression model that can be used to predict the price of an accommodation.  
Please see https://hoseberg.medium.com/i-pack-my-ml-and-go-to-seattle-594ab48791ed for a detailed analysis of the questions.