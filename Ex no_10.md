# EX 10 C program to find the factorial of a given number using a function with arguments and return type.

## DATE:
08.06.2026

## AIM:
To write a C program to find the factorial of a given number using a function with arguments and return type.

## Algorithm

1. Start the program.
2. Declare a function to calculate factorial.
3. Get the number from the user.
4. Call the function with the number as argument.
5. Calculate the factorial using loop.
6. Return the factorial value.
7. Display the factorial.
8. Stop the program.

## Program:

```c
#include <stdio.h>

int factorial(int n)
{
    int i, fact = 1;

    for(i = 1; i <= n; i++)
    {
        fact = fact * i;
    }

    return fact;
}

int main()
{
    int n, result;

    scanf("%d", &n);

    result = factorial(n);

    printf("%d", result);

    return 0;
}
```

## Output:

```text
5

120
```

## Result:
Thus the program was executed and the output was verified successfully.
