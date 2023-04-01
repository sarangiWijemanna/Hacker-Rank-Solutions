# Japanese Cities Attributes 🚚


## Task

Query all attributes of every Japanese city in the CITY table. The COUNTRYCODE for Japan is JPN.

The CITY table is described as follows:

<img align="center" src="/Images/Japanese Cities Attributes.png" alt="icon"/>

### Expected Output

```
1613 Neyagawa JPN Osaka 257315 
1630 Ageo JPN Saitama 209442 
1661 Sayama JPN Saitama 162472 
1681 Omuta JPN Fukuoka 142889 
1739 Tokuyama JPN Yamaguchi 107078 
.....................................
```

## Solution

```
SELECT *
    FROM CITY
    WHERE COUNTRYCODE = 'JPN';
```

## Suggestions
Don't forget to leave feedback if you find this repo useful or any improvements 💞.

Thank you 🧡
