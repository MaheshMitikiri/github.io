# Revising the Select Query I

## Problem

Query all columns for all American cities in CITY with populations larger than 100,000. The CountryCode for America is USA. 

![CITY](https://github.com/MaheshMitikiri/github.io/blob/master/SQL/Hackerrank/Images/1.jpg)

## Solution

```MS SQL
SELECT * FROM CITY WHERE CountryCode = 'USA' AND Population > 100000
```
