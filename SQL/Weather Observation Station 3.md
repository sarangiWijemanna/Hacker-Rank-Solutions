# Weather Observation Station 3 🚢


## Task

Query a list of ```CITY``` names from ```STATION``` for cities that have an even ```ID``` number. 
Print the results in any order, but exclude duplicates from the answer.

The ```STATION``` table is described as follows:

<img align="center" src="/Images/STATION.png" alt="icon"/>


### Expected Output

```
Aguanga 
Alba 
Albany 
Amo 
Andersonville 
Archie 
Athens 
Atlantic Mine 
Bainbridge 
Baker 
Bass Harbor 
Bayville 
........
```

## Solution

```
SELECT DISTINCT  CITY
    FROM STATION  
        WHERE MOD(ID,2)=0
            ORDER BY CITY ASC;
```

## Suggestions
Don't forget to leave feedback if you find this repo useful or any improvements 💞.

Thank you 🧡
