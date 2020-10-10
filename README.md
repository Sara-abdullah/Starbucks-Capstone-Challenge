# Starbucks-Capstone-Challenge
Udacity Data Scientist Nanodegree Capstone Project - Analyze Starbucks Capstone Challenge Dataset

# File Descriptions
There is only jupyter notebook available here to showcase work related to the predictions. Markdown cells were used to assist in walking through the thought process for individual steps. This file that runs the necessary code to obtain the final model used to predict successful transaction. Input data has been clearly marked in the notebook.

The data is contained in three files:
- portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
- profile.json - demographic data for each customer
- transcript.json - records for transactions, offers received, offers viewed, and offers completed

# Installation
To be able to run and view this project. It's recommended to have the latest versions of the followings:

- Python 3
- Jupyter Notebook
- Pandas
- Matplotlib
- sklearn
- Seaborn
- NumPy
- datetime

# Problem Statement
The problem statements I am trying to answer are here are:

What are the distributions of gender, age, and income of customers in general?
What are the distributions offer types alone and based on gender, age, and income of customers that completed the offers? 

# Metrics
Create a master dataset that takes the relevant parameters from the Clean Edition as a baseline and joining with :
"Cleaned Profile" (using Customer ID as a common key variable) to get customers' demographic information, such as age, gender, income.
"Cleaned Portfolio" (using Offer ID as the main joining variable) to get offers related information, such as offer type, channels and etc.
As customers' demographic information i.e. age and income are captured in actual value and it's not feasible to analyze based on this continuous numeric value. Therefore, binning is perform on these variables to convert it into a set of discrete buckets for further analysis.

# Results
The main findings of the code can be found at the post available here https://medium.com/@sarahalkohadir/starbucks-capstone-challenge-e4d3209e4fb3 

# Licensing, Authors, Acknowledgements
Must give credit to Udacity for the data. You can find the Licensing for the data and other descriptive information at the Udacity.
