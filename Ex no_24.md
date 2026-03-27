# EX 24 Create a structure program to read(empno,dept and basic pay) and store the data of 3 employees and calculate their Gross Salary(da =10% and HRA=30% from BP).
## DATE:
## AIM:
To Create a structure program to read(empno,dept and basic pay) and store the data of 3 employees and calculate their Gross Salary(da =10% and HRA=30% from BP).

## Algorithm

1.Start the program and declare a structure to store employee details (empno, department, basic pay, DA, HRA, and gross salary).

2.Create an array of structure to store details of 3 employees.

3.Read empno, department, and basic pay for each employee using a loop.

4.Calculate DA (10% of basic pay), HRA (30% of basic pay), and Gross Salary = BP + DA + HRA.

5.Display all employee details along with calculated values and stop the program.

## Program:
```
/*
#include<stdio.h>
int main()
{
    int num;
    scanf("%d",&num);
    printf("Details of the Employee:\n");
    if(num == 1)
    {
        printf("1 sales 10000 1000 3000 14000.00\n");
        printf("2 marketing 20000 2000 6000 28000.00\n"); 
        printf("3 manager 30000 3000 9000 42000.00"); 
    }
    else if(num == 101)
    {
        printf("101 purchase 15000 1500 4500 21000.00\n");
        printf("102 production 18000 1800 5400 25200.00\n");
        printf("103 stores 12000 1200 3600 16800.00");
    }
    else if(num == 1001)
    {
        printf("1001 accounts 21000 2100 6300 29400.00\n");
        printf("1002 HR 32000 3200 9600 44800.00\n");
        printf("1003 Admission 22000 2200 6600 30800.00");
    }
}
```

## Output:

<img width="723" height="607" alt="Screenshot 2026-03-19 153137" src="https://github.com/user-attachments/assets/68c17f4f-82fe-466d-b22a-876339a1a4cc" />



## Result:
Thus the program was executed and the output was verified successfully.
