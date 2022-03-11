# Ödev 9 SQL Komutları

```
select city.city, country.country from city
INNER JOIN country ON city.country_id=country.country_id;
```

```
select customer.first_name, customer.last_name, payment.payment_id from customer
INNER JOIN payment ON payment.customer_id = customer.customer_id;
```

```
select rental.rental_id, customer.first_name, customer.last_name from customer
INNER JOIN rental ON rental.customer_id = customer.customer_id;
```