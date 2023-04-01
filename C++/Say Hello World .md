# Say "Hello, World!" With C++ 💛


## Task

### Objective

This is a simple challenge to help you practice printing to stdout. You may also want to complete Solve Me First in C++ before attempting this challenge.


We're starting out by printing the most famous computing phrase of all time! In the editor below, use either `printf` or `cout` to print the string ``Hello, World!`` to [stdout](https://en.wikipedia.org/wiki/Standard_streams#Standard_output_.28stdout.29).

The more popular command form is cout. It has the following basic form:

```
cout<<value_to_print<<value_to_print;
````

Any number of values can be printed using one command as shown.

The printf command comes from `C` language. It accepts an optional format specification and a list of variables. Two examples for printing a string are:

```
printf("%s", string); printf(string);
```

Note that neither method adds a newline. It only prints what you tell it to.


### Expected Output

```
Hello, World!
```

## Solution

```
#include <iostream>
#include <cstdio>
using namespace std;

int main() {
    printf("Hello, World!");
    return 0;
}
```

## Suggestions

Don't forget to leave feedback if you find this repo useful or any improvements 💞.

Thank you 🧡
