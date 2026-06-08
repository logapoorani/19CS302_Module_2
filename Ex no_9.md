# EX 9 C program to find the sum of odd digits using do while loop.


## AIM:
To write a C program to find the sum of odd digits using do while loop.

## Algorithm
1.Read an integer input (a) from the user.
2.Initialize sum as 0 and i as 1.
3.Use a do-while loop to iterate from i = 1 to a, adding odd numbers to sum.
4.Increment i in each iteration.
5.Print the final sum of odd numbers. 

## Program:
```
/*
Program to find the sum of odd digits using do while loop.
Developed by: 
RegisterNumber:  
*/
#include <stdio.h>
int main()
{
    int i=1,a,sum=0;
    scanf("%d",&a);
    do{
        if(i%2!=0)
        {sum=sum+i;}
        i++;
        
    }while(i<=a);
    printf("%d",sum);
    return 0;
}
```

## Output:
![image](https://github.com/user-attachments/assets/b5da2413-2b42-4f9b-872c-0df5a8f8ecf5)



## Result:
Thus the program was executed and the output was verified successfully.
