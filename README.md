# Car-accident-prediction-Dawid-Arakelyan-Capstone
Machine Learning-Powered Accident Prediction for the Automotive Insurance Industry

Car Accident Prediction by ML

This repository contains the code and pdf paper for my capstone project on car accident prediction using machine learning.

Files

There are three main files in this repository:

Code1_Data_cleaning.ipynb: This notebook contains the data cleaning process. 
It sorts the data, deals with null values and overlays, and makes the first step of processing.The data used in this notebook is called baza_final.
Link to the first data: https://docs.google.com/spreadsheets/d/1sy6ju4A-vSeJEkYa9q5PFY1CU1kJidme/edit?usp=share_link&ouid=118367656318039327908&rtpof=true&sd=true


Code2_user_metrics.ipynb: This notebook takes the output of the first notebook and performs feature engineering. 
It creates new columns and adjusts the dataset to be used for machine learning prediction.
Link to the second data: https://docs.google.com/spreadsheets/d/10-xjSpf4xGSUXS1bdu44MtLbOXW0si2Q/edit?usp=share_link&ouid=118367656318039327908&rtpof=true&sd=true

Code3_Final_testing.ipynb: This notebook contains the prediction models and visualizations for the project.
In addition to the notebooks, there is a file containing the LaTeX code and pictures used in the report.
Link to the third data: https://docs.google.com/spreadsheets/d/1W9ejOrYeS799XpIYCOaVloh0KP6uHtDz/edit?usp=share_link&ouid=118367656318039327908&rtpof=true&sd=true
Usage

The notebooks can be run in sequential order to perform the full analysis. The data is loaded from baza_final.xlsx in the first notebook and processed accordingly.
The output of the first notebook is then used as input for the second notebook, which performs feature engineering. Finally, the third notebook loads the feature-engineered data and trains several models to predict car accidents.

Conclusion

This project shows that machine learning algorithms can be effective in predicting car accidents.By using a combination
of feature engineering and several machine learning models, we were able to achieve a recall score of over 70% for our
predictions. This could potentially be used to improve road safety measures and help prevent accidents from
