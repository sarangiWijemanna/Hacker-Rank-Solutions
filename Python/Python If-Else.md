

# Python If-Else 👧

Given an integer, ```n```, perform the following conditional actions:

If ```n``` is odd, print ```Weird```
If ```n``` is even and in the inclusive range of 2 to 5, print ```Not Weird```
If ```n``` is even and in the inclusive range of 6 to 20, print ```Weird```
If ```n``` is even and greater than 20, print ```Not Weird```


## Input Format

A single line containing a positive integer, ```n```.

### Constraints

```1 <= n <= 100```

## Output Format

Print Weird if the number is weird. Otherwise, print ```Not Weird```.

### Sample Input  0

```3```

#### Sample Output   0

```Weird```

#### Explanation 0

if n = 3, n is odd and odd numbers are weird.
So, print ```Weird```

### Sample Input 1

```24```

#### Sample Output 1

```Not Weird```

#### Explanation 1

if n = 24, 
n > 20 and n is even, so it is not weird.


## Process 

```
if __name__ == '__main__':
    n = int(input().strip())
    
    if n%2 == 0 :
        if n in range(2,6):
            print("Not Weird")
        elif n in range(6,21):
            print("Weird")
        elif n > 20:
            print("Not Weird")
        
    else:
        print("Weird")
```

##  Suggestions

Don't forget to leave feedback if you find this repo useful or any improvemnts⭐

Thank you 🎆






