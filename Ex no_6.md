# EX 6 C Program to print the string "KEYBOARD" n number of times.

## DATE:
08.06.2026

## AIM:
To write a C Program to print the string "KEYBOARD" n number of times.

## Algorithm

1. Start the program.
2. Declare integer variables.
3. Get the value of n from the user.
4. Use a loop to print the string "KEYBOARD" n number of times.
5. Stop the program.

## Program:

```c
#include <stdio.h>

int main()
{
    int i, n;

    scanf("%d", &n);

    for(i = 1; i <= n; i++)
    {
        printf("KEYBOARD\n");
    }

    return 0;
}
```

## Output:

```text
3

KEYBOARD
KEYBOARD
KEYBOARD
```

## Result:
Thus the program was executed and the output was verified successfully.
