# EX 8 C program to perform multiplication and division of two numbers using functions (without argument and without return type).


## AIM:
To write a C program to perform multiplication and division of two numbers using functions (without argument and without return type).

## Algorithm
1.Read two integer inputs (a and b) from the user.
2.Compute the product of a and b and store it in c.
3.Compute the quotient of a divided by b and store it in d.
4.Print the multiplication result (c).
5.Print the division result (d). 

## Program:
```
/*
Program to perform multiplication and division of two numbers using functions (without argument and without return type).
Developed by: 
RegisterNumber:  
*/
#include <stdio.h>
void multiply()
{
    int a,b,c,d;
    scanf("%d%d",&a,&b);
    c=a*b;
    d=a/b;
    printf("Multiplication: %d\n",c);
    printf("Division: %d",d);
    
}
int main()
{
    multiply();
}
```

## Output:
![image](https://github.com/user-attachments/assets/ca8c03d4-0155-4486-b049-9c7993fb184a)



## Result:
Thus the program was executed and the output was verified successfully.
