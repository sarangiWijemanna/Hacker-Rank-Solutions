# Weather Observation Station 4 🪂


## Task

Find the difference between the total number of ```CITY``` entries in the table and the number of distinct ```CITY``` entries in the table.

The ```STATION``` table is described as follows:

<img align="center" src="/Images/STATION_1.png" alt="icon"/>


### Expected Output

```
13
```

## Solution

```
SELECT COUNT(CITY) - COUNT(DISTINCT CITY ) 
    FROM STATION;
```

## Suggestions
Don't forget to leave feedback if you find this repo useful or any improvements 💞.

Thank you 🧡
