# Ödev 5 SQL Komutları

```
select * from film where title LIKE '%n' ORDER BY length DESC LIMIT 5;
```

```
select * from film where title LIKE '%n' ORDER BY length OFFSET 5 LIMIT 5;
```

```
select * from customer where store_id=1 ORDER BY last_name LIMIT 4
```