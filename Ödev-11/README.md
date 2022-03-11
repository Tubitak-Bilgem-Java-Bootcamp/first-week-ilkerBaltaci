# Ödev 11 SQL Komutları

```
(
	select first_name from actor
)
UNION ALL
(
	select first_name from customer
)
```

```
(
	select first_name from actor
)
INTERSECT
(
	select first_name from customer
)
```

```
(
	select first_name from actor
)
EXCEPT
(
	select first_name from customer
)
```
