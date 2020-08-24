# 8 level of difficulty


* Multiply
* https://www.codewars.com/kata/multiply/train/sql

```SQL
SELECT (price * amount) AS total 
FROM items;
```


* Even or Odd
* https://www.codewars.com/kata/53da3dbb4a5168369a0000fe/train/sql

```SQL
SELECT 
  CASE
    WHEN number % 2 = 0 THEN 'Even'
    ELSE 'Odd'
  END
AS is_even
FROM numbers;
```


* Easy SQL: LowerCase
* https://www.codewars.com/kata/easy-sql-lowercase/train/sql

```SQL
SELECT id, name, birthday, lower(race) AS race
FROM demographics;
```


* Easy SQL: Square Root and Log
* https://www.codewars.com/kata/easy-sql-square-root-and-log/train/sql

```SQL
SELECT sqrt(number1) AS root, log(number2) AS log
FROM decimals;
```


* Easy SQL: Rounding Decimals
* https://www.codewars.com/kata/easy-sql-rounding-decimals/train/sql

```SQL
SELECT floor(number1) AS number1, ceiling(number2) AS number2
FROM decimals;
```


* Easy SQL - Ordering
* https://www.codewars.com/kata/easy-sql-ordering/train/sql

```SQL
SELECT c.*
FROM companies c
ORDER BY c.employees DESC;
```


* SQL Basics: Simple SUM
* https://www.codewars.com/kata/sql-basics-simple-sum/train/sql

```SQL
SELECT SUM(age) AS age_sum
FROM people;
```


* Adults only (SQL for Beginners #1)
* https://www.codewars.com/kata/adults-only-sql-for-beginners-number-1/train/sql

```SQL
SELECT name, age
FROM users
WHERE age >= 18;
```


* On the Canadian Border (SQL for Beginners #2)
* https://www.codewars.com/kata/on-the-canadian-border-sql-for-beginners-number-2/train/sql

```SQL
SELECT name, country
FROM travelers
WHERE not (country = 'Canada' OR country = 'Mexico' OR country = 'USA');
```


* Register for the Party (SQL for Beginners #3)
* https://www.codewars.com/kata/register-for-the-party-sql-for-beginners-number-3/train/sql

```SQL
INSERT INTO participants (name, age, attending) VALUES ('Bob', '27', true);
SELECT *
FROM participants;
```


* Collect Tuition (SQL for Beginners #4)
* https://www.codewars.com/kata/collect-tuition-sql-for-beginners-number-4/train/sql

```SQL
SELECT *
FROM students
WHERE tuition_received is false;
```


* SQL Basics: Mod
* https://www.codewars.com/kata/sql-basics-mod/train/sql

```SQL
SELECT mod(number1, number2) AS mod
FROM decimals;
```


* 1.Find all active students
* https://www.codewars.com/kata/1-find-all-active-students/train/sql

```SQL
SELECT *
FROM students
WHERE IsActive;
```


* SQL Basics: Simple MIN / MAX
* https://www.codewars.com/kata/sql-basics-simple-min-slash-max/train/sql

```SQL
SELECT min(age) AS age_min, max(age) AS age_max
FROM people;
```


* SQL Basics: Simple DISTINCT
* https://www.codewars.com/kata/sql-basics-simple-distinct/train/sql

```SQL
SELECT DISTINCT age
FROM people;
```


* SQL Basics: Simple WHERE and ORDER BY
* https://www.codewars.com/kata/sql-basics-simple-where-and-order-by/train/sql

```SQL
SELECT *
FROM people
WHERE age > 50;
```


* SQL Grasshopper: Select Columns
* https://www.codewars.com/kata/sql-grasshopper-select-columns/train/sql

```SQL
SELECT custid, custname, custstate 
FROM customers;
```
