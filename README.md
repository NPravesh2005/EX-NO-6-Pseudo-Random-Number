# EX-NO-6-Pseudo-Random-Number

# AIM: 

Implementation of Pseudorandom Number Generation Using Standard library

# PROGRAM:
```C
#DEVELOPED BY : PRAVESH N
#REG NO : 212223230154
```
```C
#include <stdio.h>
#define A 1664525
#define C 1013904223
#define M 4294967296 // 2^32
unsigned int lcg(unsigned int seed) {
return (A * seed + C) % M;
}
int main() {
unsigned int seed;
int n, i;
printf("\n\n **Pseudorandom number generator**\n\n");
printf("Enter the seed value: ");
NAME: PRAVESH N
REG NO: 212223230154

scanf("%u", &seed);
printf("Enter how many random numbers to generate: ");
scanf("%d", &n);
printf("Random numbers:\n");
for (i = 0; i < n; i++) {
seed = lcg(seed);
printf("%u\n", seed);
}
return 0;
}
```

# OUTPUT :

![Screenshot 2024-10-28 124347](https://github.com/user-attachments/assets/a140652d-c470-4205-a892-edbfa6e73b08)

# RESULT :

Thus the program for pseudorandom number generator is executed successfully.




