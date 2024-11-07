# EX-NO-6-Pseudo-Random-Number
# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library
# Program 
```c
#include <stdio.h>
#include <stdlib.h>
#include <time.h>
int main() 
{
    int count, min, max;
    printf("Enter the number of random numbers to generate: ");
    scanf("%d", &count);
    printf("Enter the minimum value: ");
    
    scanf("%d", &min);
    printf("Enter the maximum value: ");
    scanf("%d", &max);
    srand(time(NULL));
    printf("Pseudorandom numbers:\n");   
    for (int i = 0; i < count; i++) 
    {
        int random_number = (rand() % (max - min + 1)) + min;
        printf("%d\n", random_number);
    }
    return 0;
}
```
# Output
![image](https://github.com/user-attachments/assets/061be87c-f2cb-4f42-8825-8274e1d887ae)
# Result
Thus the c program has been executed successfully.
