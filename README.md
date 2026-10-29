# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

# PROGRAM:
~~~

#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main()
{
    int n, i;

    srand(time(0));

    printf("Enter the number of random numbers to generate: ");
    scanf("%d", &n);

    printf("Pseudorandom numbers:\n");

    for (i = 0; i < n; i++)
    {
        printf("%d\n", rand());
    }

    return 0;
}

~~~
# OUTPUT:
<img width="1422" height="596" alt="image" src="https://github.com/user-attachments/assets/1bffb22e-00a7-43a1-8e72-2099cee0624c" />

# RESULT:
Thus, the C program to generate pseudorandom numbers using the standard library functions srand() and rand() was written and executed successfully.
