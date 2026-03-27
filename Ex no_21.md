# EX 21 C program to find  Largest of Three Numbers Using Pointer.
## DATE:
## AIM:
To write a C program to find  Largest of Three Numbers Using Pointer:

## Algorithm

1.Start the program and read three integer values a, b, and c.

2.Declare three pointer variables p1, p2, and p3 and assign them the addresses of a, b, and c.

3.Compare the values pointed by p1, p2, and p3 using conditional statements.

4.Determine the largest value among the three using the pointer dereferenced values.

5.Display the largest number and stop the program.

## Program:
```
#include <stdio.h>

int main()
{
    int a, b, c;
    int *p1, *p2, *p3;

    scanf("%d", &a);
    scanf("%d", &b);
    scanf("%d", &c);

    p1 = &a;
    p2 = &b;
    p3 = &c;

    if (*p1 >= *p2 && *p1 >= *p3)
        printf("Largest = %d", *p1);
    else if (*p2 >= *p1 && *p2 >= *p3)
        printf("Largest = %d", *p2);
    else
        printf("Largest = %d", *p3);

    return 0;
}

```

## Output:

<img width="527" height="318" alt="Screenshot 2026-03-19 144700" src="https://github.com/user-attachments/assets/f9f4c1b2-53a8-4404-ab5e-b61057085a00" />



## Result:
Thus the program was executed and the output was verified successfully.
