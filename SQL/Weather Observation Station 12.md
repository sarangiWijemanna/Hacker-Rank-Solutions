# Weather Observation Station 12 🥗


## Task

Query the list of `CITY` names from `STATION` that _do not start with vowels **AND** do not end with vowels_. 
Your result cannot contain duplicates.

The `STATION` table is described as follows:

<img align="center" src="/Images/STATION.png" alt="icon"/>


### Expected Output

```
Baker 
Baldwin 
Bass Harbor 
Beaufort 
Beaver Island 
Benedict 
Bennington 
Berryton 
Beverly 
Bison 
Blue River 
Bowdon 
Bowdon Junction 
Bridgeport 
Bridgton 
Brighton 
Brilliant 
Bristol 
.........
```

## Solution

```
SELECT DISTINCT CITY
    FROM STATION 
        WHERE 
            NOT 
              (CITY LIKE 'A%' OR 
               CITY LIKE 'E%' OR 
               CITY LIKE 'I%' OR 
               CITY LIKE 'O%' OR 
               CITY LIKE 'U%') 
        AND  
          NOT (CITY LIKE '%A' OR 
               CITY LIKE '%E' OR 
               CITY LIKE '%I' OR 
               CITY LIKE '%O' OR 
               CITY LIKE '%U'); 
```

## Suggestions
Don't forget to leave feedback if you find this repo useful or any improvements 🌹.

Thank you 🧡
