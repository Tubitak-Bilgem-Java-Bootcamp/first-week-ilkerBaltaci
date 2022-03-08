# Ödev 1 SQL Komutları


```
Select title, description FROM film ORDER BY title DESC;
```
```
Select * from film where length > 60 AND length < 75 ORDER BY length ASC
```
```
Select * from film where (rental_rate=0.99) AND (replacement_cost=12.99 OR replacement_cost=28.99);
```
```
Select first_name, last_name from customer where first_name='Mary'
```
```
Select * from film where not length > 50 AND NOT (rental_rate=2.99 OR rental_rate=4.99);
```