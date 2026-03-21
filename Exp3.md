# EXERCISE 3: Queries with Constraints (Pt. 2)

## 1. Find all the Toy Story movies

```sql
SELECT *
FROM MOVIES
WHERE TITLE LIKE 'Toy Story%';
```

## 2. Find all the movies directed by John Lasseter

```sql
SELECT *
FROM MOVIES
WHERE DIRECTOR = 'John Lasseter';
```

## 3. Find all the movies (and director) not directed by John Lasseter

```sql
SELECT TITLE, DIRECTOR
FROM MOVIES
WHERE DIRECTOR != 'John Lasseter';
```

## 4. Find all the WALL-* movies

```sql
SELECT *
FROM MOVIES
WHERE TITLE LIKE 'WALL-%';
```
