# Higher Than 75 Marks 7️⃣5️⃣


## Task

Query the Name of any student in `STUDENTS` who scored higher than  Marks. 

- Order your output by the last three characters of each name. 
- If two or more students both have names ending in the same last three characters (i.e.: Bobby, Robby, etc.), secondary sort them by ascending ID.

## Format

### Input Format

The `STUDENTS` table is described as follows:  

<img align="center" src="/Images/STUDENTS.png" alt="icon"/>

The Name column only contains uppercase (A-Z) and lowercase (a-z) letters.

### Sample Input

| ID  | Name     | Marks |
|-----|----------|-------|
| 1   | Ashley   | 81    |
| 2   | Samantha | 75    |
| 3   | Julia    | 76    |
| 4   | Belvet   | 84    |


### Sample Output

```
Ashley
Julia
Belvet
```

### Explanation

- Only Ashley, Julia, and Belvet have Marks > 75 . 
- If you look at the last three characters of each of their names, there are no duplicates and 'ley' < 'lia' < 'vet'.


## Expected Output

```
Stuart 
Kristeen 
Christene 
Amina 
Aamina 
Priya 
Heraldo 
Scarlet 
Julia 
Salma 
Britney 
Priyanka 
Samantha 
Vivek 
Belvet 
Devil 
Evil
```

## Solution

```
SELECT NAME  
    FROM STUDENTS 
        WHERE MARKS > 75
            ORDER BY RIGHT(NAME,3), ID;
```

## Suggestions

Don't forget to leave feedback if you find this repo useful or any improvements 💞.

Thank you 🧡
