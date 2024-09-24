# Recursion
Experiment 15
## Aim 
To study Recursion

## Theory
### Definition
#### What is a Recursion?
- Recursion in C++ is a technique where a function calls itself to solve a problem.
- This approach is often used for problems that can be divided into smaller, similar subproblems. 
- A recursive function typically has two main components:
  - Base Case: A condition under which the function will stop calling itself, preventing 
  infinite recursion.
  - Recursive Case: The part of the function where it calls itself with modified arguments to 
  gradually approach the base case.
> For example:
```cpp
#include <iostream>
using namespace std;

int factorial(int n) {
    if (n <= 1) {
        return 1;
    }
    return n * factorial(n - 1);
}

int main() {
    int number = 5;
    std::cout << "Factorial of " << number << " is " << factorial(number) << std::endl;
    return 0;
}

```


## Algorithms
