# 7 level of difficulty


* Sum of odd numbers
* https://www.codewars.com/kata/55fd2d567d94ac3bc9000064/train/sql

```SQL
SELECT n * n * n AS res 
FROM nums;
```


* Easy SQL: Counting and Grouping
* https://www.codewars.com/kata/594633020a561e329a0000a2/train/sql

```SQL
SELECT race, COUNT(race)
FROM demographics
GROUP BY race
ORDER BY COUNT(race) DESC;
```


* SQL Basics: Simple GROUP BY
* https://www.codewars.com/kata/58111f4ee10b5301a7000175/train/sql

```SQL
SELECT age, COUNT(age) AS people_count
FROM people
GROUP BY age;
```


* SQL Basics: Simple JOIN
* https://www.codewars.com/kata/5802e32dd8c944e562000020/train/sql

```SQL
SELECT p.*, c.name AS company_name
FROM products p
JOIN companies c ON p.company_id = c.id;
```


* Best-Selling Books (SQL for Beginners #5)
* https://www.codewars.com/kata/591127cbe8b9fb05bd00004b/train/sql

```SQL
SELECT *
FROM books
ORDER BY copies_sold DESC
LIMIT 5;
```


* Countries Capitals for Trivia Night (SQL for Beginners #6)
* https://www.codewars.com/kata/5e5f09dc0a17be0023920f6f/train/sql

```SQL
SELECT capital
FROM countries
WHERE continent IN ('Africa', 'Afrika') AND country LIKE 'E%'
ORDER BY capital
LIMIT 3;
```


* SQL Basics: Raise to the Power
* https://www.codewars.com/kata/594a8f653b5b4e8f3d000035/train/sql

```SQL
SELECT POW(number1, number2) AS result
FROM decimals;
```


* SQL Basics: Simple JOIN with COUNT
* https://www.codewars.com/kata/580918e24a85b05ad000010c/train/sql

```SQL
SELECT p.*, COUNT(t) AS toy_count
FROM people p
JOIN toys t ON p.id = t.people_id
GROUP BY p.id;
```


* SQL: Concatenating Columns
* https://www.codewars.com/kata/59440034e94fae05b2000073/train/sql

```SQL
SELECT CONCAT_WS(' ', prefix, first, last, suffix) AS title
FROM names;
```


* Hello SQL World!
* https://www.codewars.com/kata/581283eb0a5fb13e06000020/train/sql

```SQL
SELECT 'hello world!' AS "Greeting";
```


* SQL Basics - Position
* https://www.codewars.com/kata/59401e0e54a655a298000040/train/sql

```SQL
SELECT id, name, POSITION(',' IN characteristics) AS comma
FROM monsters
ORDER BY comma;
```
