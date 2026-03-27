# EX 25 C program to test whether a number is positive, negative, or equal to zero using pointers
## DATE:
## AIM:
To write a C program to test whether a number is positive, negative, or equal to zero using pointers

## Algorithm

1.Start the program and declare an integer variable num and a pointer ptr.

2.Read the value of num from the user.

3.Assign the address of num to the pointer ptr.

4.Use conditional statements to check the value pointed by ptr (positive, negative, or zero).

5.Display the result and stop the program.

## Program:
```
/*
#include <stdio.h>

int main()
{
    int num;
    int *ptr;

    scanf("%d", &num);
    ptr = &num;

    if (*ptr > 0)
        printf("the number is Positive");
    else if (*ptr < 0)
        printf("the number is negative");
    else
        printf("the number is zero");

    return 0;
}

```

## Output:

<img width="484" height="158" alt="Screenshot 2026-03-19 154110" src="https://github.com/user-attachments/assets/796b9fbf-7f58-4b6f-a2c6-c3a57e459a0c" />


## Result:
Thus the program was executed and the output was verified successfully.
