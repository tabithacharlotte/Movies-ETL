# Movies-ETL

## Overview of the Project

For this project, I created an automated pipeline that takes in new data on movies, performs the appropriate transformations and loads the data into existing tables. 

I created a function that takes in three files -- Wikipedia data, Kaggle metadata, and a MovieLens rating data -- and performed an ETL process by adding the data to a PostgreSQL database.

## Resources

- Data Source: movies_metadata.csv, ratings.csv, wikipedia-movies.json
- Software: JupyterNotebook, Pandas Library

## File Organization

- `ETL_function_test.ipynb` file which contains an ETL Function to Read Three Data Files
- `ETL_clean_wiki_movies.ipynb` file that extracts and transforms Wikipedia Data per specifications
- `ETL_clean_kaggle_data.ipynb` file which extracts and transforms Kaggle Data
- `ETL_create_database.ipynb` file creates the movie database
- `movie_data.ipynb` contains scratch code and practice tests
- Resources Folder
  - Contains images of the screenshots showing the tables and queries.