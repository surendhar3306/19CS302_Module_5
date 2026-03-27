# EX 23 C program to store and display the name, id and salary of an employee using structure(using array of structure).
## DATE:
## AIM:
To write a C program to store and display the name, id and salary of an employee using structure(using array of structure).

## Algorithm

1. Start the program and define a structure employee with fields id, name, and salary.

2.Declare an array of structures to store details of employees.

3.Read the name, id, and salary for each employee using a loop.

4.Store the entered details in the structure array.

5.Display the stored employee details and stop the program.
   

## Program:
```
#include<stdio.h>
struct employee
{
    int id;
    char name[100];
    float salary;
    
};
int main()
{
    struct employee emp;
    scanf("%[^\n]",emp.name);
    scanf("%d",&emp.id);
    scanf("%f",&emp.salary);
    printf("Entered detail is:\n");
    printf("Name: %s\n",emp.name);
    printf("Id: %d\n",emp.id);
    printf("Salary: %.2f\n",emp.salary);
    return 0;
}
```

## Output:

<img width="429" height="189" alt="Screenshot 2026-03-19 153545" src="https://github.com/user-attachments/assets/0e8df2fd-b146-4216-81ea-e37197756839" />


## Result:
Thus the program was executed and the output was verified successfully.
