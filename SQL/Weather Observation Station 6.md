# Weather Observation Station 6 🚠


## Task

Query the list of ```CITY``` names starting with _**vowels**_ (i.e., a, e, i, o, or u) from ```STATION```. 
Your result _cannot contain duplicates_.

The ````STATION```` table is described as follows:

<img align="center" src="/Images/STATION.png" alt="icon"/>


### Expected Output

```
Acme 
Addison 
Agency 
Aguanga 
Alanson 
Alba 
Albany 
Albion 
Algonac 
Aliso Viejo 
Allerton 
Alpine 
..........
```

## Solution

```
SELECT DISTINCT CITY A
    FROM STATION 
        WHERE CITY LIKE 'A%' OR 
              CITY LIKE 'E%' OR 
              CITY LIKE 'I%' OR 
              CITY LIKE 'O%' OR
              CITY LIKE 'U%'
        ORDER BY A;
```

## Suggestions
Don't forget to leave feedback if you find this repo useful or any improvements 🎀.

Thank you 🧡
