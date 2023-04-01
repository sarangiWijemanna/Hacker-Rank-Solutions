# Weather Observation Station 8 🍔


## Task

Query the list of `CITY` names from STATION which have vowels (i.e., a, e, i, o, and u) as _both their first and last characters_. 
Your result _cannot contain duplicates_.

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
East China 
East Irvine 
.............
```

## Solution

```
SELECT DISTINCT CITY AS A
    FROM STATION 
        WHERE (CITY LIKE 'A%' OR 
               CITY LIKE 'E%' OR 
               CITY LIKE 'I%' OR 
               CITY LIKE 'O%' OR 
               CITY LIKE 'U%') 
        AND 
            (CITY LIKE '%A' OR 
             CITY LIKE '%E' OR 
             CITY LIKE '%I' OR 
             CITY LIKE '%O' OR 
             CITY LIKE '%U') 
        ORDER BY A;    
```

## Suggestions
Don't forget to leave feedback if you find this repo useful or any improvements 💞.

Thank you 🧡
