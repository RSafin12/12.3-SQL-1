# 12.3-SQL-1

## Задание 1
```SELECT DISTINCT district
FROM address
WHERE district  LIKE 'K%a';
```

## Задание 2
```SELECT payment_id, amount, payment_date  
FROM payment p
WHERE payment_date  BETWEEN '2005-06-05 00:00:00' AND '2005-06-19 00:00:00' AND amount > 10;
```

## Задание 3
```SELECT rental_date
FROM rental r
ORDER BY rental_date DESC
LIMIT 5;
```

## Задание 4
```SELECT LOWER(first_name), LOWER(last_name), LOWER(REPLACE(first_name, 'L', 'p'))
FROM customer c
WHERE active = 1 AND first_name = 'Kelly' OR first_name = 'Willie';
```
