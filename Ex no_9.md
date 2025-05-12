# EX 9 C program to find the sum of odd digits using do while loop.
## DATE:
## AIM:
To write a C program to find the sum of odd digits using do while loop.

## Algorithm
1. Start
2. Declare variables: num, digit, sum
3. Initialize sum = 0
4. Prompt and read the number using scanf
5. Convert number to positive if negative
6. Use do...while loop to extract digits and add odd ones to sum
7. Print the sum and End

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
![image](https://github.com/user-attachments/assets/e671bfce-5930-4983-8671-2aa7c4e68b85)



## Result:
Thus the program was executed and the output was verified successfully.
