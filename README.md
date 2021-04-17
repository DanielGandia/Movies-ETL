# Movies-ETL
## Overview of the Analysis
Refactor the code from the module to create one function that takes in the three files (Wikipedia data, Kaggle metadata, and the MovieLens rating data) and perform the ETL process by adding the data to a PostgreSQL database.
### Resources
- Data Sources: ratings.csv, movies_metadata.csv 
- Software: PostgreSQL, pgAdmin 4, Visual Studio Code 1.54, Python 3.8.3, Jupyter Notebook 6.1.4

### Results
A query was run to ensure that the Movies table had 6,052 rows. Another query was run to ensure that Ratings table had 26,024,289 rows.

Please see below the screenshots of the output of each query:

Movies Query:

![movies_query.png](https://github.com/DanielGandia/Movies-ETL/blob/main/Resources/movies_query.png)

Ratings Query:

![ratings_query.png](https://github.com/DanielGandia/Movies-ETL/blob/main/Resources/ratings_query.png)