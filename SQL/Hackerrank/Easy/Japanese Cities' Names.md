# Japanese Cities' Names

## Problem

Query the names of all the Japanese cities in the CITY table. The COUNTRYCODE for Japan is JPN.

![CITY](https://github.com/MaheshMitikiri/github.io/blob/master/SQL/Hackerrank/Images/1.jpg)

## Solution

```MS SQL
SELECT NAME FROM CITY 
WHERE CountryCode = 'JPN'
```
