<!-- Q1 -->

34% have a rental rate of 0.99

```sql
SELECT (count(rental_rate)/10) AS Dollar_films 
FROM film 
WHERE rental_rate = 0.99;
```

<!-- Q2 -->


| Tables        | 1           | 2  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |