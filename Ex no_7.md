# EX 7 C Program to Print a right triangle star Pattern
## AIM:
To write a C Program to Print a right triangle star Pattern

## Algorithm
1.Input the number of rows: Read an integer value (rows) from the user.
2.Outer loop for rows: Iterate i from 1 to rows to control line count.
3.Inner loop for columns: Iterate j from 1 to i to print stars.
4.Print stars: Output * in each iteration of the inner loop.
5.Newline for formatting: Print a newline (\n )
## Program:
```
/*
Program to Print a right triangle star Pattern
Developed by: 
RegisterNumber:  
*/
#include <stdio.h>
int main()
{
    int i,j,rows;
    scanf("%d",&rows);
    for(i=1;i<=rows;i++)
    {
        for(j=1;j<=i;j++)
        printf("*");
        printf("\n");
    }
}

```

## Output:
![image](https://github.com/user-attachments/assets/9180d8a8-e8fd-40d9-8e1a-635c448ff16c)



## Result:
Thus the program was executed and the output was verified successfully.
