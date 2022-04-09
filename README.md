# Starbucks_Capstone

## Project Overview
This capstone project is using data provided by Udacity as part of the Data Scientist Nanodegree course. It contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. Starbucks sends out an offer to users of the mobile app. Some users might not receive any offer during certain weeks, and not all users receive the same offer.

More analysis can be found over the [blog post](https://medium.com/@grewalshagan94/how-effective-are-the-starbucks-offers-11a871dc0fd0).

### Table of Contents
1. [Project Motivation](#project-motivation)
2. [Data](#data)
3. [Installation](#installation)
4. [Strategy Followed](#strategy-followed)
5. [Licensing](#licensing)

## Project Motivation
In my capstone project, i am basing my work on the starbucks data.
I aim to answer following 2 business questions:
- 1. What proportions of the users complete the offers based on their age and gender
- 2. What kind of offers should be sent more to the users.


## Data
The data provided consists of 3 datasets:
- Offer portfolio, which consists of the attributes of each offer (portfolio.json)
- Demographic data for each customer (profile.json)
- Transactional records of events occurring on the app (transcript.json)

## Installation
The project requires the installation of Ananconda distribution of python. The code available in the Starbucks_Capstone_notebook.ipynb should work fine without any issues on python version 3.*.

Following are the libraries used for the project:
- numpy
- pandas
- json
- sklearn.model_selection (train_test_split)
- sklearn.metrics (classification_report, accuracy_score, f1_score)
- sklearn.ensemble  (RandomForestClassifier)
- matplotlib.pyplot

## Strategy Followed
I have followed the following steps to execute the various algorithms to provide business insight.
- Importing Libraries and Data Loading
- Data Exploration
- Data Cleaning
- Data analysis
- Conclusions for Business Actions

## Licensing
The data was provided by udacity itself.
