

# List Comprehensions 💛

Let's learn about list comprehensions! You are given three integers x,y and z representing the dimensions of a cuboid along with an integer n. Print a list of all possible coordinates given by  (i,j,k) on a 3D grid where the sum of  is not equal to n. Here, 
 0 <= i < x; 
 0 <= j < y;
 0 <= k < z;

Please use list comprehensions rather than multiple loops, as a learning exercise.

## Example

if x = 1, y = 1, z = 2, n = 3

All permutations of [i,j,k] are:

``` 
[[0, 0, 0], [0, 0, 1], [0, 0, 2], [0, 1, 0], [0, 1, 1], [0, 1, 2], [1, 0, 0], [1, 0, 1], [1, 0, 2], [1, 1, 0], [1, 1, 1], [1, 1, 2]]
```

Print an array of the elements that do not sum to n = 3.

```
[[0, 0, 0], [0, 0, 1], [0, 0, 2], [0, 1, 0], [0, 1, 1], [1, 0, 0], [1, 0, 1], [1, 1, 0], [1, 1, 2]]
```

## Process 

### Method 1 - Using Multiple Loop
``` 
  x = int(input())
  y = int(input())
  z = int(input())
  n = int(input())

  l = []
  for i in range(x + 1):
      for j in range(y + 1):
          for k in range(z + 1):
              m = [i, j, k]
              if sum(m) != n:
                  l.append(m)
  print(l) 
```

### Method 2 - Using List Comprehensions

```
  x = int(input())
  y = int(input())
  z = int(input())
  n = int(input())
    
  print([[i,j,k] for i in range(x+1) for j in range(y+1) for k in range(z+1) if (i+j+k)!=n])
```

##  Suggestions

Don't forget to leave feedback if you find this repo useful or any improvemnts⭐

Thank you 🎆






