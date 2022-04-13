# Movies-ETL

## Purpose
The goal of this project is to create an automated ETL pipeline that creates a Movie database from both structured and unstructured data. Code is written that extracts Wikipedia JSON data, Kaggle metadata, and the MovieLens rating data, transforms the data, and it into a PostgreSQL database.

## Results

The resulting database consists of two tables that are displayed below.

A movies table with 6,051 rows of data, each representing a unique movie title. The table also includes 31 columns of data with production related information, such as, movie budget, producers, actors and release data.

<img width="374" alt="movies_query" src="https://user-images.githubusercontent.com/93743169/163238373-5c3577b9-aca5-49ad-9883-f12cb1c438ab.png">

A ratings table was also generated with 26,024,289 rows of data, each representing a viewer rating of 1-5. The table includes 5 columns of data such as movie title, rating and date.

<img width="393" alt="ratings_query" src="https://user-images.githubusercontent.com/93743169/163238485-a99f3c32-9810-4c21-a4f1-5e0b481a4125.png">
