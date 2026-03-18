# EXERCISE 1: SELECT Queries

USE MOVIES_DB;

SHOW TABLES;

SELECT * FROM MOVIES;

#1. Find the title of each film.
SELECT TITLE
FROM MOVIES;

#2. Find the director of each film.
SELECT DIRECTOR
FROM MOVIES;

#3. Find the title and director of each film.
SELECT TITLE, DIRECTOR
FROM MOVIES;

#4. Find the title and year of each film.
SELECT TITLE, YEAR
FROM MOVIES;

#5. Find all the information about each film.
SELECT *
FROM MOVIES;
