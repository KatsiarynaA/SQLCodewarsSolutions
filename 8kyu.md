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
