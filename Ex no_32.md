# EX 32 C program to display Hardware details such as price, product name and price using structure.

## AIM:
To write a C program to display Hardware details such as price, product name and price using structure.

## Algorithm
1. 
2. 
3. 
4.  
5.   

## Program:
```
/*
C program to display Hardware details such as price, product name and price using structure.
Developed by: 
RegisterNumber:  
*/
#include<stdio.h> 
struct hardware 
{ 
char qr[10]; 
char product[10]; 
int price; 
}j[10]; 
int main() 
{ 
int i; 
for(i=0;i<3;i++) 
scanf("%s%s%d",j[i].qr,j[i].product,&j[i].price); 
for(i=0;i<3;i++) 
printf("QRcode:%s\nproduct:%s\nprice :%d\n",j[i].qr,j[i].product,j[i].price);}
```

## Output:

QR123 Mouse 599
QR456 Keyboard 1299
QR789 Monitor 9999



## Result:
Thus the program was executed and the output was verified successfully.
