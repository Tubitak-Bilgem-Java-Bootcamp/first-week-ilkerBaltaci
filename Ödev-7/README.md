# Ödev 7 SQL Komutları

```
select rating, COUNT(*) from film group by rating
```

```
select replacement_cost, COUNT(*) from film group by replacement_cost HAVING COUNT(*) > 50
```

```
select store_id, COUNT(*) from customer group by store_id
```

```
select country_id, COUNT(*) from city group by country_id ORDER BY COUNT(*) DESC LIMIT 1
```