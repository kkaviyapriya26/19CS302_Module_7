# EX 33 C program to read a file name from user and create that file using fopen().
## DATE: 30-04-25
## AIM:
To write a C program to read a file name from user and create that file using fopen().

## Algorithm
1. Start.
2. Define a variables.
3. Write a program to read a file name from user and create that file using fopen().
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End.
## Program:
```
#include <stdio.h> 
int main()
{FILE *p;
char name[40]; 
scanf("%s",name);
p=fopen("name","w");
printf("%s File Created Successfully\n",name); 
printf("%s File Opened\n",name);
fclose(p);
printf("%s File Closed",name);
}
```

## Output:
![image](https://github.com/user-attachments/assets/34b6969e-6cfa-47d7-9996-4c1295536fce)

## Result:
Thus the program was executed and the output was verified successfully.
