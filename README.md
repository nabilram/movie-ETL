# movie-ETL 

# Outline
    * Client requires analyses using multiple data sets from multiple sources
        * movies data, kaggle data, and ratings data
    * ETL to be used for analysis
 
# Methods Analyses
* Extract data
    * data has been provided by client directly

* Transform data
    * Clean and merge data sets
    * Pivot ratings data set as needed
    * Once merged
        * Remove redundant columns
        * Replace Nulls with
            * available data from other sources datasets
            * 0's if no data is available
* Load Data
    * Loaded outcomes to SQL database movies_db
