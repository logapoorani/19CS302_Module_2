# EX 8 C program to perform multiplication and division of two numbers using functions (without argument and without return type).
## DATE:
## AIM:
To write a C program to perform multiplication and division of two numbers using functions (without argument and without return type).

## Algorithm:
1.Start the program.
2.Declare two global variables for the numbers.
3.Create two functions — one for multiplication and one for division — without arguments and return type.
4.In main(), take input for the two numbers, then call both functions.
5.End the program.

## Program:
```
/*
Program to perform multiplication and division of two numbers using functions (without argument and without return type).
Developed by: Logapoorani R
RegisterNumber: 212223060136

#include <stdio.h>

int num1, num2;

void multiply() {
    printf("Multiplication: %d\n", num1 * num2);
}

void divide() {
    if(num2 != 0)
        printf("Division: %.2f\n", (float)num1 / num2);
    else
        printf("Division by zero is not allowed.\n");
}

int main() {
    scanf("%d%d", &num1, &num2);
    multiply();
    divide();
    return 0;
}

*/
```

## Output:

![image](https://github.com/user-attachments/assets/dc44d0d6-2a3a-4120-9e2e-246052db2ea6)

## Result:
Thus the program was executed and the output was verified successfully.
