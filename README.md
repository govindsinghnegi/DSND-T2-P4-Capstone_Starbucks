## Motivation
This is a Capstone project done as a requirement from Data Science Nano Degree, offered by Udacity. 
Goal of this project is to analyse Starbucks open source datasets and extract insights out of
it. The provided data set contains simulated data that mimics customer behavior on the Starbucks 
rewards mobile app. Using the data sets following questions would be answered: 
* What are the main features responsible for a successful offer ?
* Given a set of features, can we predict if the offer would be a success ?

## Pre-requisites
```
python3
pandas
sklearn
numpy
matplotlib
seaborn
```

## Files
* portfolio.json (stores offer related data)
* profile.json (stores user related data)
* transcript.json (stores transactions executed to/by the user)
* master_data.csv (stores the master dataframe generated during the project)

## Results
The following conclusions were made:
* There are some features more important than others. That is, amount spent or income earned by 
a user is more significant than other features such as offer_duration.
* We can predict (with 91.69% accuracy) if an offer with some given set of features would be 
successful or not.

The methodology in detail have been published at 
[medium.com](https://medium.com/@gsn.06081990/know-your-customers-starbucks-capstone-challenge-48f4f50e0da3)