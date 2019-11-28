## retrieving rows from a table
select * from table name

- retrieving subset from a table
- by where clause
- 	e.g., selec title from book where pages 290 and 300
-    	select where country in ('')
- use string row to look for string pattern
- e.g., select firstname from author where firstname like %R%
* % wildcard character which is used to substitute other characters

## sorting the result set
order by clause
* by default in ascending order
* use desc at the end of the clause

- e.g., select title from book order by 2
* 2 stands for column 2
- or order by title desc

## grouping result
eliminating duplicates
- select distinct() from 

- count('') from author group by country
- count('') as count from author group by country
- use as to assign the column name to the result set

