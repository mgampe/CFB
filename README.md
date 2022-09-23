# CFB
College football predictions using Machine Learning

This document outlines the set up for running historic_model_comparison.ipynb

historic_model_comparison.ipynb is a script for training, testing, optimizing, and comparing 5 different ML algorithms. Depending on your machine, it may take anywhere from 15 minutes to an hour to run. To significantly reduce the amount of time, you may comment out the Support Vector Machine cells.

python version: 3.8.2 64 bit

Data requirements: Provided with the code
cfb_15_21_train_wide.csv,
cfb_15_21_test_wide.csv,
w4_data.csv,
w4_not_yet_played.csv,
week4_matchups.csv

Imports/Dependencies: Please ensure you have the following installed before running the notebook:
numpy, 
pandas,
seaborn,
sklearn,
matplotlib,
tensorflow
