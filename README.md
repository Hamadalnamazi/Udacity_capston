# Udacity_capston

## A closer look into the data of West Nile Virus of Chicago

Table of Contents:

1.The Libraries

2.My Project Motivation

3.File Descriptions

4.Summary Of The Results

5.Acknowledgements

## The Libraries
The project was implemented using Anaconda distribution of Python 3.0. Moreover I have used the following python libraries:


1.Matplotlib
2.NumPy
3.Pandas
4.Seaborn
5.Sklearn
6.re
7.xgboost


## My Project Motivation

West Nile virus is most commonly spread to humans through infected mosquitos. Around 20% of people who become infected with the virus develop symptoms ranging from a persistent fever, to serious neurological illnesses that can result in death.

In 2002, the first human cases of West Nile virus were reported in Chicago. By 2004 the City of Chicago and the Chicago Department of Public Health (CDPH) had established a comprehensive surveillance and control program that is still in effect today.

Every week from late spring through the fall, mosquitos in traps across the city are tested for the virus. The results of these tests influence when and where the city will spray airborne pesticides to control adult mosquito populations.

Given weather, location, testing, and spraying data, this competition asks you to predict when and where different species of mosquitos will test positive for West Nile virus. A more accurate method of predicting outbreaks of West Nile virus in mosquitos will help the City of Chicago and CPHD more efficiently and effectively allocate resources towards preventing transmission of this potentially deadly virus. 

## File Descriptions

The Jupyter notebook showcases the analysis done in order to explore the dataset, the data prepartion and wrangling as well as the building of prediction models in order to answer the questions above. The notebook contains markdown cells to help with documentation of the steps as well as to communicate findings based on each analysis.

For reference an HTML version of the notebook is also available.

Lastly, the folder contains the dataset from Kaggle (https://www.kaggle.com/c/predict-west-nile-virus/data). It contains 4 files:

1. & 2. train.csv, test.csv - the training and test set of the main dataset. The training set consists of data from 2007, 2009, 2011, and 2013, while in the test set you are requested to predict the test results for 2008, 2010, 2012, and 2014.

3. spray.csv - GIS data of spraying efforts in 2011 and 2013.
4. weather.csv - weather data from 2007 to 2014. Column descriptions in noaa_weather_qclcd_documentation.pdf

## Summary Of The Results

The main findings of the code can be found at the post available here.

## Acknowledgements
This competition is sponsored by the Robert Wood Johnson Foundation. Data is provided by the Chicago Department of Public Health.
https://www.kaggle.com/c/predict-west-nile-virus/data
