# Weather Observation Station 7 🚲


## Task

Query the list of `CITY` names ending with vowels (a, e, i, o, u) from `STATION`. 
Your result cannot contain duplicates.

The `STATION` table is described as follows:

<img align="center" src="/Images/STATION.png" alt="icon"/>


### Expected Output

```
Acme 
Aguanga 
Alba 
Aliso Viejo 
Alpine 
Amazonia 
Amo 
Andersonville 
Archie 
Arispe 
Arkadelphia 
Atlantic Mine 
Baileyville 
Bainbridge 
Barrigada 
Baton Rouge
.............
```

## Solution

```
SELECT DISTINCT CITY A
    FROM STATION 
        WHERE CITY LIKE '%A' OR 
              CITY LIKE '%E' OR 
              CITY LIKE '%I' OR 
              CITY LIKE '%O' OR
              CITY LIKE '%U'
        ORDER BY A;
```

## Suggestions
Don't forget to leave feedback if you find this repo useful or any improvements 🌹.

Thank you 🧡
