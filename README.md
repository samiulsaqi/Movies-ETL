# Movies-ETL

## Overview of analysis

This analysis looks at movies information from wikipedia and Movielens, cleans and merges them in a consistent format using Pandas and lastly passes the merged dataframe to PostgreSQL with ETL pipeline processes.

## Analysis Steps

The analysis does the following things:

-> Read in files in different formats for analysis
    - Read in a wikipedia extract in json format
    - Read in a movie metadata extract from Movielens in csv format
    - Read in a csv file with movie ratings
-> Clean the files read in by:
    - formatting columns properly(i.e. numerical columns standardized, text columns standardized)
    - dropping duplicate rows
    - dropping adult films data
    - merging the wikipedia and movielens data and removing any duplicate or empty columns
    - cleaning the ratings file and pivoting based on ratings value
-> Output files to a databes by:
    - creating a connection to a postgreSQL databases
    - pass on the merged movies and ratings dataframe.

## Summary

Overall, this was a wholesome experience, as this included working in Pandas and python, creating functions for data wrangling and connecting to SQL databases. 