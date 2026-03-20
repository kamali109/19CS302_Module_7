# EX 31 C program to find the smallest among three numbers using Structure.

## AIM:
To write a C program to find the smallest among three numbers using Structure.

## Algorithm
```
1.Start.
Define a variables a,b,c.
Write program to find the smallest among the three numbers.
Read the value using scanf.
Ask the user to make an input.
Print out the answer.
End 
```

## Program:
```
/*
C program to find the smallest among three numbers using Structure.
Developed by: 
RegisterNumber:  
*/
#include<stdio.h> 
struct num 
{ 
int a,b,c; 
}; 
int main() 
{ 
struct num n; 
scanf("%d%d%d",&n.a,&n.b,&n.c); 
if(n.a<n.b&&n.a<n.c) 
{ 
printf("%d",n.a); 
} 
else if(n.b<n.a&&n.b<n.c) 
{ 
printf("%d",n.b); 
} 
else 
{printf("%d",n.c);}} 
```

## Output:
11352
2


## Result:
Thus the program was executed and the output was verified successfully.
