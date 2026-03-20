# EX 33 C program to read a file name from user and create that file using fopen().

## AIM:
To write a C program to read a file name from user and create that file using fopen().

## Algorithm
1. 
2. 
3. 
4.  
5.   

## Program:
```
/*
C program to read a file name from user and create that file using fopen().
Developed by: KAMALI.S
RegisterNumber:  212222060109
*/
#include <stdio.h>

int main()
{
    char filename[100];
    FILE *fp;

    scanf("%s", filename);

    fp = fopen(filename, "w");
    if (fp != NULL)
        printf("%s File Created Successfully\n", filename);

    printf("%s File Opened\n", filename);

    fclose(fp);
    printf("%s File Closed", filename);

    return 0;
}


```

## Output:

<img width="1004" height="324" alt="image" src="https://github.com/user-attachments/assets/bc05fbaa-f96c-429c-bd84-fc8ec2e40153" />


## Result:
Thus the program was executed and the output was verified successfully.
