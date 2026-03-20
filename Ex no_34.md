# EX 34 C program to read a file name from user and create that file and insert student roll numbers in to that file.

## AIM:
To write a C program to read a file name from user and create that file and insert student roll numbers in to that file.

## Algorithm
1. 
2. 
3. 
4.  
5.   

## Program:
```
/*
C program to read a file name from user and create that file and insert student roll numbers in to that file.
Developed by: KAMALI.S
RegisterNumber:  212222060109
*/
#include <stdio.h>

int main()
{
    char filename[100];
    int n, i, roll;
    FILE *fp;

    scanf("%s", filename);

    fp = fopen(filename, "w");
    printf("%s Opened\n", filename);

    scanf("%d", &n);

    for (i = 0; i < n; i++)
    {
        scanf("%d", &roll);
        fprintf(fp, "%d\n", roll);
    }

    fclose(fp);
    printf("Data added Successfully");

    return 0;
}

```

## Output:


<img width="757" height="147" alt="image" src="https://github.com/user-attachments/assets/c476756b-085c-4c95-aaff-b81cba53b987" />


## Result:
Thus the program was executed and the output was verified successfully.
