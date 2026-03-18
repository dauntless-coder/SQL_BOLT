# EXERCISE 3: Queries with Constraints (Pt. 2)

USE MOVIES_DB;

SHOW TABLES;

SELECT * FROM MOVIES;

#1. Find all the Toy Story movies
SELECT *
FROM MOVIES
WHERE TITLE LIKE 'Toy Story%';

#2. Find all the movies directed by John Lasseter
SELECT *
FROM MOVIES
WHERE DIRECTOR = 'John Lasseter';

#3. Find all the movies (and director) not directed by John Lasseter
SELECT TITLE, DIRECTOR
FROM MOVIES
WHERE DIRECTOR != 'John Lasseter';

#4. Find all the WALL-* movies
SELECT *
FROM MOVIES
WHERE TITLE LIKE 'WALL-%';
