# Weather Observation Station 5 🦽


## Task

Query the two cities in ```STATION``` with the shortest and longest ```CITY``` names, as well as their respective lengths (i.e.: number of characters in the name). 
If there is more than one smallest or largest city, choose the one that comes first when ordered alphabetically.

The ```STATION``` table is described as follows:

<img align="center" src="/Images/STATION.png" alt="icon"/>

## Format

### Sample Input

For example, ```CITY``` has four entries: ```DEF```, ```ABC```, ```PQRS``` and ```WXY```.

### Sample Output

```
ABC 3
PQRS 4
```

### Explanation

When ordered alphabetically, the CITY names are listed as ABC, DEF, PQRS, and WXY, with lengths  and . 
The longest name is PQRS, but there are  options for shortest named city. 
Choose ABC, because it comes first alphabetically.

### Note

You can write two separate queries to get the desired output. It need not be a single query.

### Expected Output

```
Amo 3
Marine On Saint Croix 21
```

## Solution

```
(SELECT CITY,LENGTH(CITY) AS A
    FROM station 
        ORDER BY 
            A ASC,
            CITY ASC 
        LIMIT 1)
        
  UNION
  
(SELECT CITY,LENGTH(CITY) AS A
    FROM station 
        ORDER BY 
            A DESC,
            CITY DESC 
        LIMIT 1)
```

## Suggestions
Don't forget to leave feedback if you find this repo useful or any improvements 💞.

Thank you 🧡
