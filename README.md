# SQLCodewarsSolutions

* https://www.codewars.com/kata/easy-sql-lowercase/train/sql

```SQL
SELECT id, name, birthday, lower(race) AS race
FROM demographics;
```

* https://www.codewars.com/kata/easy-sql-square-root-and-log/train/sql

```SQL
SELECT sqrt(number1) AS root, log(number2) AS log
FROM decimals;
```

* https://www.codewars.com/kata/easy-sql-rounding-decimals/train/sql

```SQL
SELECT floor(number1) AS number1, ceiling(number2) AS number2
FROM decimals;
```

* https://www.codewars.com/kata/easy-sql-ordering/train/sql

```SQL
SELECT c.*
FROM companies c
order by c.employees desc;
```

* https://www.codewars.com/kata/sql-basics-simple-sum/train/sql

```SQL
SELECT SUM(age) AS age_sum
FROM people;
```

* https://www.codewars.com/kata/register-for-the-party-sql-for-beginners-number-3/train/sql

```SQL
insert into participants (name, age, attending) values ('Bob', '27', true);
SELECT *
FROM participants;
```

* https://www.codewars.com/kata/on-the-canadian-border-sql-for-beginners-number-2/train/sql

```SQL
SELECT name, country
FROM travelers
WHERE not (country = 'Canada' or country = 'Mexico' or country = 'USA');
```

* https://www.codewars.com/kata/adults-only-sql-for-beginners-number-1/train/sql

```SQL
SELECT name, age
FROM users
WHERE age >= 18;
```

* https://www.codewars.com/kata/sql-basics-mod/train/sql

```SQL
SELECT mod(number1, number2) AS mod
FROM decimals;
```

* https://www.codewars.com/kata/1-find-all-active-students/train/sql

```SQL
SELECT *
FROM students
WHERE IsActive;
```

* https://www.codewars.com/kata/sql-basics-simple-min-slash-max/train/sql

```SQL
SELECT min(age) AS age_min, max(age) AS age_max
FROM people;
```

* https://www.codewars.com/kata/sql-basics-simple-distinct/train/sql

```SQL
SELECT distinct age
FROM people;
```

* https://www.codewars.com/kata/collect-tuition-sql-for-beginners-number-4/train/sql

```SQL
SELECT *
FROM students
WHERE tuition_received is false;
```

* https://www.codewars.com/kata/sql-basics-simple-where-and-order-by/train/sql

```SQL
SELECT *
FROM people
WHERE age > 50;
```

* https://www.codewars.com/kata/sql-grasshopper-select-columns/train/sql

```SQL
SELECT custid, custname, custstate 
FROM customers;
```
