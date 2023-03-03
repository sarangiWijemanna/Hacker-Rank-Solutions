

# Find the Runner-Up Score!

Given the participants' score sheet for your University Sports Day, you are required to find the runner-up score. You are given  scores. Store them in a list and find the score of the runner-up.

## Input Format

The first line contains . The second line contains an array   of  integers each separated by a space.

### Constraints

  ```2 <= n < = 10```

  ```-100 < = A[] <= 100```

Print the runner-up score.

## Example

### Sample Input 

```
  5
  2 3 6 6 5
```

### Sample Output 

```
  5
```

### Explanation 

Given list is [2, 3, 6, 6, 5] . The maximum score is 6, second maximum is 5. Hence, we print 5 as the runner-up score.

## Process 

```
if __name__ == '__main__':
    n = int(input())
    arr = map(int, input().split())
    
l = []
l = list(arr)
l.sort()
# print(l)
  
# removing duplicate elements from the list
# Way 1: res = list(set(l)) # using set() to remove duplicated from list
# Way 2: 
res = []
[res.append(x) for x in l if x not in res]
# print(res)

print(res[-2])

```

##  Suggestions

Don't forget to leave feedback if you find this repo useful or any improvemnts⭐

Thank you 🎆






