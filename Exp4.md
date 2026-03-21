# EXERCISE 4: Filtering and Sorting Query Results

## 1. List all directors of Pixar movies (alphabetically), without duplicates

```sql
SELECT DISTINCT DIRECTOR
FROM MOVIES
ORDER BY DIRECTOR ASC;
```

## 2. List the last four Pixar movies released (ordered from most recent to least)

```sql
SELECT *
FROM MOVIES
ORDER BY YEAR DESC
LIMIT 4;
```

## 3. List the first five Pixar movies sorted alphabetically

```sql
SELECT *
FROM MOVIES
ORDER BY TITLE ASC
LIMIT 5;
```

## 4. List the next five Pixar movies sorted alphabetically

```sql
SELECT *
FROM MOVIES
ORDER BY TITLE ASC
LIMIT 5 OFFSET 5;
```
