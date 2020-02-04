# Weather Observation Station 6

## Problem

Query the list of CITY names starting with vowels (i.e., a, e, i, o, or u) from **STATION**. Your result cannot contain duplicates.

![CITY](https://github.com/MaheshMitikiri/github.io/blob/master/SQL/Hackerrank/Images/2.jpg)

where LAT_N is the northern latitude and LONG_W is the western longitude.

## Solution

```MS SQL
SELECT DISTINCT CITY FROM STATION
WHERE LEFT(CITY,1) IN ('a', 'e', 'i', 'o', 'u')
```
