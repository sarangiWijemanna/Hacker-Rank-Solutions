# Japanese Cities' Names 🚇


## Task

Query the names of all the Japanese cities in the ```CITY``` table. The ```COUNTRYCODE``` for Japan is ```JPN```.
The ```CITY``` table is described as follows:

<img align="center" src="/Images/CITY.png" alt="icon"/>

### Expected Output

```
    Neyagawa 
    Ageo 
    Sayama 
    Omuta 
    Tokuyama 
    ........
```

## Solution

```
SELECT NAME
    FROM CITY
    WHERE COUNTRYCODE = 'JPN';
```

## Suggestions
Don't forget to leave feedback if you find this repo useful or any improvements 💞.

Thank you 🧡
