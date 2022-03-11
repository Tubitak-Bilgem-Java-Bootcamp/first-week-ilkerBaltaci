# Ödev 10 SQL Komutları

```
select city.city, country.country from city
LEFT JOIN country ON country.country_id = city.country_id;
```

```
select payment.payment_id, customer.first_name, customer.last_name from customer
RIGHT JOIN payment ON payment.customer_id = customer.customer_id;
```

```
select customer.first_name, customer.last_name, rental.rental_id from customer
FULL JOIN rental ON rental.customer_id = customer.customer_id;
```