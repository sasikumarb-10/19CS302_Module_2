# EX 9 C program to find the sum of odd digits using do while loop.
## DATE:
## AIM:
To write a C program to find the sum of odd digits using do while loop.

## Algorithm
1. 
2. 
3. 
4.  
5.   

## Program:
```
/*
Program to find the sum of odd digits using do while loop.
Developed by: Sasi Kumar B
RegisterNumber:  212223060252
*/
#include <stdio.h>

int main() {
    int num, digit, sum = 0;

    printf("Enter a number: ");
    scanf("%d", &num);

    if (num < 0)
        num = -num;

    do {
        digit = num % 10;
        if (digit % 2 != 0) {
            sum += digit;
        }
        num /= 10;
    } while (num != 0);

    printf("Sum of odd digits: %d\n", sum);

    return 0;
}

```

## Output:



## Result:
Thus the program was executed and the output was verified successfully.
