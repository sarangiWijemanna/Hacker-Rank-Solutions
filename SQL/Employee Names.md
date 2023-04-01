# Employee Names 👲


## Task

Write a query that prints a list of employee names (i.e.: the name attribute) from the `Employee` table in alphabetical order.


## Format

### Input Format

The `Employee` table containing employee data for a company is described as follows:

<img align="center" src="/Images/Employee.png" alt="icon"/>

_where employee_id is an employee's ID number, name is their name, months is the total number of months they've been working for the company, and salary is their monthly salary._


### Sample Input

<img align="center" src="/Images/Employee_Sample_Output.png" alt="icon"/>

### Sample Output

````
Angela
Bonnie
Frank
Joe
Kimberly
Lisa
Michael
Patrick
Rose
Todd
````

## Expected Output

```
Alan 
Amy 
Andrew 
Andrew 
Angela 
Ann 
Anna 
Anthony 
Antonio 
Benjamin 
Bonnie 
Brandon 
Brandon 
Brian 
Carol 
Charles 
Christina 
Christina 
Christine 
.......
```

## Solution

```
SELECT NAME  
    FROM EMPLOYEE 
        ORDER BY NAME;
```

## Suggestions
Don't forget to leave feedback if you find this repo useful or any improvements 🎈.

Thank you 🧡
