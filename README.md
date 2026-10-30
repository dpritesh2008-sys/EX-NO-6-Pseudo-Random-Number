# EX-NO-6-Pseudo-Random-Number
~~~
## Name : Ritesh DP
## Reg. No. : 212225040339
~~~
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

int main() {
    int n, i;

    srand(time(0));

    printf("Enter the number of random numbers: ");
    scanf("%d", &n);

    printf("Random numbers are:\n");

    for (i = 0; i < n; i++) {
        printf("%d\n", rand());
    }

    return 0;
}
~~~

# OUTPUT:
<img width="610" height="357" alt="image" src="https://github.com/user-attachments/assets/b49f25a6-cbcf-4ee5-a937-aeeaad005b7b" />

# RESULT:
Thus the implementation of pseudorandom number generation had been executed successfully.

