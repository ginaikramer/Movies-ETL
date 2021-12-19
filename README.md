# Movies-ETL
## Overview
The purpose of this project is to create an automated pipeline for Amazing Prime that does the following:
- Reads in movie data from three different data sources
- Performs cleaning and transformations of the data
- Loads the data into tables
- Stores cleaned data into a database

## Results
This project produced 4 Deliverables:
1) [ETL Function to Read Three Data Files](/ETL_function_test.ipynb): Contains a function to read 3 disparate movie data files 
   
2) [Extract & Transform Wikipedia Data](/ETL_clean_wiki_movies.ipynb): Performs extraction and transformation of movie data from Wikipedia 

3) [Extract & Transform Kaggle Data](/ETL_clean_kaggle_data.ipynb): Performs extraction and transformation of movie data from Kaggle 

4) [Create a Movie Database](/ETL_create_database.ipynb): Creates a SQL database to store cleaned and transformed movie data into a Movie Database 

The final deliverable created a Movie_Data Database that has 2 Tables:
1) Movies
   - This table contains 6,052 rows of data
   - ![# Rows in Movies Table](/Resources/movies_query.png) 
    
2) Ratings
   - This table contains 26,024,289 rows of data
   - ![# Rows in Ratings Table](/Resources/ratings_query.png)  
 
**PLEASE NOTE:** Some of the ipynb files reference a file path outside of the Movies-ETL folder to reference the raw wiki, movie and ratings data. In order for me to not have to re-run all of the code to reference the Resources folder, I placed copies of the raw data files under Resources to include with the final package. 

## Summary
All of the deliverables combined led to a final Movie_Data database with clean data that Amazing Prime can now use for further analysis.
