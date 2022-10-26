# Data-Analyst-Nanodegree-Project-2-Wrangle-and-Analyze-Data
### Second project in Udacity's ALX Data Analyst Nanodgree Program 

## Overview: 
This project aims to wrangle, analyze, and visualize the WeRateDogs dataset, which is the
tweet archive of Twitter user @dog_rates. WeRateDogs is a Twitter account that rates
people's dogs with a humorous comment about the dog. These ratings almost always have a
denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10,
13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million
followers and has received international media coverage.

## Data Sources: 
The data for this project consists of 3 different datasets that were obtained as following: <br>
- Enhanced Twitter Archive: obtained from the twitter_archive_enhanced.csv file
provided by Udacity which was manually downloaded. <br>
- Image Predictions: which is a file that contains a dog breed prediction for each dog
in a certain tweet. 3 predictions are given for each dog with their corresponding
confidence level and whether that prediction is true or not. This file was hosted on
Udacity’s servers and was downloaded programmatically using the Requests library
and he given URL. <br>
- Twitter API and JSON: twitter API was used to query additional data beyond the
data included in the WeRateDogs Twitter archive. This additional data will include
retweet count and favorite count. The data gathered was written to a JSON file
tweet_json.txt to be used later. There was also the option to access this data without
a twitter account by downloading the tweet_json.txt directly as given by Udacity. <br>

## Steps: 
#### 1. Assessing Data: <br>
Using both visual and programmatic assessments. divided to Quality Issues and Tidiness Issues, as well as divided by
the tables to which each issue belongs.

#### 2. Cleaning Data: <br>
Cleaned the issues identified in the data assessment step. <br>
The "define, code, and test" methodology was used to structure the cleaning step 

#### 3. Storing Data: <br>
The clean dataset was stored to twitter_archive_master.csv file
using .to_csv function.

#### 4. Data Visualizations and Insights: <br>
The final clean dataset was used to derive insights and make visualizations.


## Data Dictionary: 
| Variable | Type | Definition | Example |
| ------------- | ------------- |------------- |------------- |

