# EX 35 C program to create a file named "Hospital.txt" and display messages on successful creation, opening, and closing of the file.

## AIM:
To write a C program to create a file named "Hospital.txt" and display messages on successful creation, opening, and closing of the file.

## Algorithm
```
.Start the program and declare a file pointer.

2.Use fopen() in write mode to create and open the file "Hospital.txt".

3.Check if the file was created and opened successfully and display a message.

4.Close the file using fclose() after confirming successful opening.

5.Display a message indicating the file was closed successfully.
````
## Program:
```
/*
C program to create a file named "Hospital.txt" and display messages on successful creation, opening, and closing of the file.
Developed by: KAMALI.S
RegisterNumber:  212222060109
*/
#include <stdio.h>

int main()
{
    FILE *fp;

    fp = fopen("Hospital.txt", "w");
    printf("Hospital.txt File Created Successfully\n");
    printf("Hospital.txt File Opened\n");

    fclose(fp);
    printf("Hospital.txt File Closed");

    return 0;
}


```

## Output:


<img width="816" height="153" alt="image" src="https://github.com/user-attachments/assets/fd8342ea-76d4-4f26-9cfa-2070c8ea4d22" />



## Result:
Thus the program was executed and the output was verified successfully.
