# EX 9 C program to find the sum of odd digits using do while loop.

## DATE:
08.06.2026

## AIM:
To write a C program to find the sum of odd digits using do while loop.

## Algorithm

1. Start the program.
2. Declare variables for number, digit, and sum.
3. Get the number from the user.
4. Extract each digit using modulo operator.
5. Check whether the digit is odd.
6. Add the odd digit to the sum.
7. Repeat the process using do while loop until the number becomes 0.
8. Display the sum.
9. Stop the program.

## Program:

```c
#include <stdio.h>

int main()
{
    int n, digit, sum = 0;

    scanf("%d", &n);

    do
    {
        digit = n % 10;

        if(digit % 2 != 0)
        {
            sum = sum + digit;
        }

        n = n / 10;

    } while(n != 0);

    printf("%d", sum);

    return 0;
}
```

## Output:

```text
12345

9
```

## Result:
Thus the program was executed and the output was verified successfully.
