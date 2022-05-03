# Movies-ETL

## Purpose

1. Create an automated ETL pipline that is capable of daily updates.
2. Extract large data sets from different sources and read in using python.
3. Clean and transform data into usable dataframe using pandas.
4. Load into PostgreSQL to create a usable database.

AmazingPrimevideo team is sponsoring a hackathon to develop ETL pipline to predict which movies will become popular. The data created from Kaggle and wikipedia are cleaned and transformed to provide the datesets to be loaded into PostgresSQL for the hackathon. 

## Results

The resulting SQL database consists of two tables created by extracts from Kaggle metadata, MovieLens rating data, and Wikipedia JSON file.

A movies table with 6,052 rows representing unique movie titles with columns of relevant production information.

![image](https://github.com/courtneysims/Movies-ETL/blob/8e66a93746bac83fdc16b995bb4c580c59d59a3e/Resource/movies_query.PNG)

A ratings table with 26,024,289 rows of data that consists of user's ratings scaled 1-5 for a unique movie id. 
![image](https://github.com/courtneysims/Movies-ETL/blob/8e66a93746bac83fdc16b995bb4c580c59d59a3e/Resource/ratings_query.PNG)

