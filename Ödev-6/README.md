# Ödev 6 SQL Komutları

```
select AVG(rental_rate) from film
```

```
select COUNT(*) from film where title LIKE 'C%'
```

```
select MAX(length) from film where rental_rate = 0.99
```

```
select COUNT(DISTINCT replacement_cost) from film where length > 150
```