# Revising the Select Query II

## Problem

Query the names of all American cities in CITY with populations larger than 120000. The CountryCode for America is USA. 

![CITY](https://github.com/MaheshMitikiri/github.io/blob/master/SQL/Hackerrank/Images/1.jpg)

## Solution

```MS SQL
SELECT NAME FROM CITY 
WHERE CountryCode = 'USA' AND Population > 120000
```
