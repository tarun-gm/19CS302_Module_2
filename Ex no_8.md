# EX 8 C program to perform multiplication and division of two numbers using functions (without argument and without return type).

## DATE:
08.06.2026

## AIM:
To write a C program to perform multiplication and division of two numbers using functions (without argument and without return type).

## Algorithm

1. Start the program.
2. Declare two functions for multiplication and division.
3. Get two numbers from the user.
4. Call the multiplication function.
5. Call the division function.
6. Display the results.
7. Stop the program.

## Program:

```c
#include <stdio.h>

int a, b;

void multiply()
{
    printf("Multiplication = %d\n", a * b);
}

void divide()
{
    printf("Division = %d", a / b);
}

int main()
{
    scanf("%d %d", &a, &b);

    multiply();
    divide();

    return 0;
}
```

## Output:

```text
20 5

Multiplication = 100
Division = 4
```

## Result:
Thus the program was executed and the output was verified successfully.
