# Ödev 12 SQL Komutları

```
select COUNT(*) from film where length > (SELECT AVG(length) from film);
```

```
select COUNT(*) from film where rental_rate = (SELECT MAX(rental_RATE) from film);
```

```
(
	select * from film where rental_rate = (select MIN(rental_rate) from film) 
)
INTERSECT
(
	select * from film where replacement_cost = (select MIN(replacement_cost) from film)
);
```

```
SELECT temp1.customer_id, customer.first_name, customer.last_name, temp1.trade_num FROM 
(select customer_id, COUNT(*) as trade_num from payment
GROUP BY customer_id
ORDER BY COUNT(*) DESC
LIMIT 10) AS temp1
INNER JOIN customer ON customer.customer_id = temp1.customer_id;
```