# Weather Observation Station 3

## Problem

Query a list of CITY names from STATION with even ID numbers only. You may print the results in any order, but must exclude duplicates from your answer.

![CITY](https://github.com/MaheshMitikiri/github.io/blob/master/SQL/Hackerrank/Images/2.jpg)

where LAT_N is the northern latitude and LONG_W is the western longitude.

## Solution

```MS SQL
SELECT DISTINCT CITY FROM STATION
WHERE ID%2 = 0
```
