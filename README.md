# Dataset

**WeRateDog Twitter archive is a dataset that contains an extracted data of 2356 of over 5000 tweets from @dog_rate Twitter handle, where any dog posted are being rated by people. In this report I will be describing my data wrangling steps.

## Summary of Findings

### Gathering the Datasets

**In this project I gathered 3 datasets from different sources:

- A csv file (twitter_ enhanced _archive) that was provided by Udacity which needed to be downloaded from their server.

= A tsv file (image_predictions) that was downloaded programmatically from Udacity server.

- A json file was also downloaded via twitter API using tweepy All this files where read into a pandas dataframe for analysis.

## Key Insights for Presentation

### Assessing and Cleaning the Dataset

The 3 datasets were assessed independently checked for possible quality and tidiness issue using both visual and programmatic method of data assessment.
After possible issues where discovered I made a copy of each dataframe before starting my cleaning exercise. After the cleaning I merged the 3 dataframe into one single dataframe which I then saved as a csv file named “twitter_archive_master” and stored it into my work folder. I then read the new wrangled dataset into pandas dataframe for data visualization.


## Requirements
Python
Numpy
Pandas
Seaborne 
Matplotlib
requests
json
tweepy
datetime
