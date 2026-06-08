# EX 7 C Program to Print a Right Triangle Star Pattern

## DATE:
08.06.2026

## AIM:
To write a C Program to Print a right triangle star Pattern.

## Algorithm

1. Start the program.
2. Declare integer variables.
3. Get the number of rows from the user.
4. Use nested loops to print the star pattern.
5. Stop the program.

## Program:

```c
#include <stdio.h>

int main()
{
    int i, j, n;

    scanf("%d", &n);

    for(i = 1; i <= n; i++)
    {
        for(j = 1; j <= i; j++)
        {
            printf("* ");
        }

        printf("\n");
    }

    return 0;
}
```

## Output:

```text
5

* 
* * 
* * * 
* * * * 
* * * * * 
```

## Result:
Thus the program was executed and the output was verified successfully.
