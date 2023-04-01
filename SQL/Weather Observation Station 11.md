# Weather Observation Station 11 🥙


## Task

Query the list of `CITY` names from STATION that _either do not start with vowels _**OR**_ do not end with vowels_. 
Your result cannot contain duplicates.

The `STATION` table is described as follows:

<img align="center" src="/Images/STATION.png" alt="icon"/>


### Expected Output

```
Kissee Mills
Loma Mar
Sandy Hook
Tipton
Arlington
Turner
Slidell
Negreet
Glencoe
Chelsea
Chignik Lagoon
Pelahatchie
Hanna City
Dorrance
Albany
Monument
...........
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
    OR  
      NOT (CITY LIKE '%A' OR 
           CITY LIKE '%E' OR 
           CITY LIKE '%I' OR 
           CITY LIKE '%O' OR 
           CITY LIKE '%U'); 
```

## Suggestions
Don't forget to leave feedback if you find this repo useful or any improvements 💞.

Thank you 🧡
