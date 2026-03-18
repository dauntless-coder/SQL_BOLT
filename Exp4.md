# EXERCISE 4: Filtering and Sorting Query Results

USE MOVIES_DB;

SHOW TABLES;

SELECT * FROM MOVIES;

#1. List all directors of Pixar movies (alphabetically), without duplicates
SELECT DISTINCT DIRECTOR
FROM MOVIES
ORDER BY DIRECTOR ASC;

#2. List the last four Pixar movies released (ordered from most recent to least)
SELECT *
FROM MOVIES
ORDER BY YEAR DESC
LIMIT 4;

#3. List the first five Pixar movies sorted alphabetically
SELECT *
FROM MOVIES
ORDER BY TITLE ASC
LIMIT 5;

#4. List the next five Pixar movies sorted alphabetically
SELECT *
FROM MOVIES
ORDER BY TITLE ASC
LIMIT 5 OFFSET 5;
