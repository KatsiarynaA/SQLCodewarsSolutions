# SQLCodewarsSolutions

* https://www.codewars.com/kata/easy-sql-lowercase/train/sql

```SQL
select id, name, birthday, lower(race) as race
from demographics
```

* https://www.codewars.com/kata/easy-sql-square-root-and-log/train/sql

```SQL
select sqrt(number1) as root, log(number2) as log
from decimals
```

* https://www.codewars.com/kata/easy-sql-rounding-decimals/train/sql

```SQL
select floor(number1) as number1, ceiling(number2) as number2
from decimals
```

* https://www.codewars.com/kata/easy-sql-ordering/train/sql

```SQL
select c.*
from companies c
order by c.employees desc
```

* https://www.codewars.com/kata/sql-basics-simple-sum/train/sql

```SQL
select sum(age) as age_sum
from people
```

* https://www.codewars.com/kata/register-for-the-party-sql-for-beginners-number-3/train/sql

```SQL
insert into participants (name, age, attending) values ('Bob', '27', true);
select *
from participants
```

* https://www.codewars.com/kata/on-the-canadian-border-sql-for-beginners-number-2/train/sql

```SQL
select name, country
from travelers
where not (country = 'Canada' or country = 'Mexico' or country = 'USA')
```

* https://www.codewars.com/kata/adults-only-sql-for-beginners-number-1/train/sql

```SQL
select name, age
from users
where age >= 18
```

* https://www.codewars.com/kata/sql-basics-mod/train/sql

```SQL
select mod(number1, number2) as mod
from decimals
```