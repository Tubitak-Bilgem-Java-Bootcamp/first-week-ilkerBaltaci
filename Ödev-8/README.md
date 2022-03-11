# Ödev 8 SQL Komutları

```
CREATE TABLE employee (
	id INTEGER,
	name VARCHAR(50),
	birthday DATE,
	email VARCHAR(100)
);
```

```
insert into employee (id, name, birthday, email) values (1, 'Hugibert Kleehuhler', '1997-03-16', 'hkleehuhler0@newsvine.com');
insert into employee (id, name, birthday, email) values (2, 'Diarmid Sidebottom', null, 'dsidebottom1@google.pl');
insert into employee (id, name, birthday, email) values (3, 'Nelia Hurdis', '2008-11-26', 'nhurdis2@plala.or.jp');
insert into employee (id, name, birthday, email) values (4, 'Ericka Covell', '2000-05-13', 'ecovell3@over-blog.com');
insert into employee (id, name, birthday, email) values (5, 'Anders Larkkem', '1996-09-11', 'alarkkem4@cnet.com');
insert into employee (id, name, birthday, email) values (6, 'Genna Mateev', '2002-09-17', null);
insert into employee (id, name, birthday, email) values (7, 'Pru Malenoir', '1969-02-26', 'pmalenoir6@infoseek.co.jp');
insert into employee (id, name, birthday, email) values (8, 'Alaine Bonehill', '1994-07-22', null);
insert into employee (id, name, birthday, email) values (9, 'Ophelie Yarr', '1978-06-12', 'oyarr8@soup.io');
insert into employee (id, name, birthday, email) values (10, 'Madelyn Crosswaite', null, 'mcrosswaite9@wordpress.com');
insert into employee (id, name, birthday, email) values (11, 'Toddy Hatch', '1981-04-11', 'thatcha@usatoday.com');
insert into employee (id, name, birthday, email) values (12, 'Bennie Laurie', '1970-06-07', 'blaurieb@over-blog.com');
insert into employee (id, name, birthday, email) values (13, 'Donn Powderham', '1950-11-19', 'dpowderhamc@pcworld.com');
insert into employee (id, name, birthday, email) values (14, 'Mario Walls', '1956-09-25', 'mwallsd@blog.com');
insert into employee (id, name, birthday, email) values (15, 'Forrester Drewett', '1952-09-20', 'fdrewette@yellowbook.com');
insert into employee (id, name, birthday, email) values (16, 'Sophia Berndtssen', '1964-11-14', 'sberndtssenf@npr.org');
insert into employee (id, name, birthday, email) values (17, 'Shane Vaudin', '2001-10-25', 'svauding@oakley.com');
insert into employee (id, name, birthday, email) values (18, 'Nikolaos Caraher', '1987-11-04', null);
insert into employee (id, name, birthday, email) values (19, 'Wolfgang Hamlet', '1983-06-01', 'whamleti@wsj.com');
insert into employee (id, name, birthday, email) values (20, 'Gladi Hedley', '2018-12-03', 'ghedleyj@newsvine.com');
insert into employee (id, name, birthday, email) values (21, 'Toinette Felderer', '1985-09-25', 'tfeldererk@ezinearticles.com');
insert into employee (id, name, birthday, email) values (22, 'Emmalee Rodders', '1979-10-05', 'eroddersl@gnu.org');
insert into employee (id, name, birthday, email) values (23, 'Wheeler McWhinnie', '1987-06-18', 'wmcwhinniem@google.nl');
insert into employee (id, name, birthday, email) values (24, 'Rogers Teffrey', '1990-12-06', 'rteffreyn@delicious.com');
insert into employee (id, name, birthday, email) values (25, 'Doll Ramberg', '1979-04-24', 'drambergo@livejournal.com');
insert into employee (id, name, birthday, email) values (26, 'Jeralee Elphey', '1956-10-05', 'jelpheyp@springer.com');

```

```
UPDATE employee
SET name = 'UPDATE'
WHERE name LIKE 'A%'
```

```
DELETE FROM employee
WHERE name = 'UPDATE'
```