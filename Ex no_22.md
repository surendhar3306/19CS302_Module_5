# EX 22 C program to swap the three values m = 20, n = 45, 0 = 65 using function pointers ( without temporary variable) 
## DATE:
## AIM:
To write a  C program to swap the three values m = 20, n = 45, 0 = 65 using function pointers ( without temporary variable) 

## Algorithm

1.Start the program and initialize three variables m = 20, n = 45, and o = 65.

2.Pass the addresses of m, n, and o to the function using pointers.

3.Inside the function, add all three values and store the result in *m.

4.Update *n, *o, and *m sequentially using arithmetic operations to swap the values without using a temporary variable.

5.Return to the main function, display the swapped values, and stop the program.  

## Program:
```
#include <stdio.h>

void swap(int *m, int *n, int *o)
{
    *m = *m + *n + *o;
    *n = *m - (*n + *o);   // n gets original m
    *o = *m - (*n + *o);   // o gets original n
    *m = *m - (*n + *o);   // m gets original o
}

int main()
{
    int m = 20, n = 45, o = 65;

    printf("m is %d, n is %d, o is %d\n", m, n, o);

    swap(&m, &n, &o);

    printf("m is %d, n is %d, o is %d", m, n, o);

    return 0;
}

```

## Output:

<img width="659" height="194" alt="Screenshot 2026-03-19 151134" src="https://github.com/user-attachments/assets/46b04490-5523-40f8-82ac-1d1851a32dd1" />


## Result:
Thus the program was executed and the output was verified successfully.
