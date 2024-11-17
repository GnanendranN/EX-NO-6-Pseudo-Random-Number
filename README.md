# EX-NO-6-Pseudo-Random-Number

## AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

## Program
```
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
        printf("%d ", random_number);
    }
    return 0;
 }
```
## Output
![image](https://github.com/user-attachments/assets/0ddbbe22-eb7d-4de0-8050-5a694dfea5c3)

## Result
Thus the Implementation of Pseudorandom Number Generation Using Standard library was executed successfully.
