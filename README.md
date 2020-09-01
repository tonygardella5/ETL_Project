# ETL- Extract, Transform, Load

## Extract

 ### Data source 1:  Next Space Flight:  https://nextspaceflight.com
* This data was extracted in the form of a csv file
* We used Pandas to read the csv file into the dataframe

### Data source 2:  Space Flight News:  https://spaceflightnewsapi.net
* This data was extracted in the form of an API call
* We used the requests and json libraries to read this data into the dataframe

## Transform

In order to transform the data and use it in our study we performed the following:
CSV file was transformed using the Pandas library
* df.drop was used to drop extra columns
* .value_counts was used to review the amount of data collected
* df.to_csv was used to save the completed dataframe as a csv file
* df.to_json was used to save the completed dataframe as a json file

JSON file was transformed using the Pandas library
* Pandas library was used to convert the json data into a dataframe
* df.dtypes was used to determine data types
* 
* 
* df.to_csv was used to save the completed dataframe as a csv file
* df.to_json was used to save the completed dataframe as a json file
* 
* The two files were merged using pd.merge


## Load
The last step was to transfer our final output into a Database. We created a database and respective table to match the columns from the final Panda's Data Frame using ... 

## Summary

