
# Revising the Select Query II 🕎

## Task

Query the NAME field for all American cities in the CITY table with populations larger than 120000. The CountryCode for America is USA.

The CITY table is described as follows:

<img align="center" src="/Images/Revising the Select Query II.png" alt="icon"/>

## Expected Output

```
  Scottsdale
  Corona
  Concord
  Cedar Rapids
```

## Solution

```
SELECT NAME
FROM CITY
WHERE POPULATION > 120000 AND COUNTRYCODE = "USA";
```

## Suggestions

Don't forget to leave feedback if you find this repo useful or any improvemnts ⭐💘.

Thank you 🧡
