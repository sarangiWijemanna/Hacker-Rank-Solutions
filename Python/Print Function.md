
# Print Function ⚜

The included code stub will read an integer, ```n```, from STDIN.

Without using any string methods, try to print the following:

- 123......n

- Note that "....." represents the consecutive values in between.

## Example

  if n = 5, the Print the string ```12345```.

## Format

### Input Format

The first line contains an integer ```n```.

### Constraints

  - 1 <= n <= 150


### Output Format

Print the list of integers from ```1``` through ```n``` as a string, without spaces.

### Sample Input 0

```
  3
```

### Sample Output 0

```
  123
```

## Process

> Method 1:

```
if __name__ == '__main__':
    n = int(input())
    
    
    print(*range(1, n + 1), sep="")
    
```

> Method 2:

```

if __name__ == '__main__':
    n = int(input())
    
    string = "" # Empty string Variable 
        
    for i in range(1,n+1):
        string += str(i)
            
    print(string)
````


##  Suggestions

Don't forget to leave feedback if you find this repo useful or any improvemnts ⭐.

Thank you 🧡
