# Movies-ETL - Analysis for Amazing Prime

## Overview

1. Create an ETL pipeline from raw data to a SQL database.
2. Extract data from multiple different sources using Python.
3. Clean and transform data using Pandas.
4. Use regular expressions to parse data and transform text into numbers.
5. Load data with PostgreSQL and verify in PgAdmin.

## Results

The resulting database consists of two tables that are highlighted below.

A movies table with 6,052 rows of data, each representing a unique movie title. The table also includes 31 columns of data with production related information, such as, movie budget, producers, actors and release data. 

![movies](https://github.com/jbowman86/Movies-ETL/blob/353f694bbdc0c061a8a265636df8e946e4caba16/Resources/movies_query.png)

A ratings table a table with 26,024,289 rows of data, each representing a viewer rating of 1-5. The table also includes 5 columns of data such as movie title, rating and date.

![ratings](https://github.com/jbowman86/Movies-ETL/blob/353f694bbdc0c061a8a265636df8e946e4caba16/Resources/ratings_query.png)
