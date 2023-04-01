# Weather Observation Station 9 🍟


## Task

Query the list of `CITY` names from STATION that _do not start with vowels_. 
Your result cannot contain duplicates.

The `STATION` table is described as follows:

<img align="center" src="/Images/STATION.png" alt="icon"/>


### Expected Output

```
Baileyville 
Bainbridge 
Baker 
Baldwin 
Barrigada 
Bass Harbor 
Baton Rouge 
Bayville 
Beaufort 
Beaver Island 
Bellevue 
Benedict 
Bennington 
Bentonville 
Berryton 
Bertha 
..........
```

## Solution

```
SELECT DISTINCT CITY AS A
    FROM STATION 
        WHERE NOT (CITY LIKE 'A%' OR 
               CITY LIKE 'E%' OR 
               CITY LIKE 'I%' OR 
               CITY LIKE 'O%' OR 
               CITY LIKE 'U%')  
        ORDER BY A; 
```

## Suggestions
Don't forget to leave feedback if you find this repo useful or any improvements 💞.

Thank you 🧡
