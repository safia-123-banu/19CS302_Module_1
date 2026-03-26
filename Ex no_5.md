# EX 5 C program to calculate the total marks, average, and percentage of marks obtained in seven subjects.
## DATE:17-03-26
## AIM:
To write a C program to calculate the total marks, average, and percentage of marks obtained in seven subjects.

## Algorithm
1. Start.
2. Declare three variable value of type int for marks.
3. Prompt the user to enter a value.
4. Read the value using scanf. 
5. Find total and average.
6. Print the result.
7. End.

## Program:
```
#include <stdio.h>
int main() {
 int sub1, sub2, sub3, total;
 float average;
 scanf("%d %d %d", &sub1,&sub2,&sub3);
 total = sub1 + sub2 + sub3;
 average = total / 3.0;
 printf("\nTotal : %d\n", total);
 printf("Average : %.2f\n", average);
 return 0;
}
```

## Output:
<img width="465" height="198" alt="Screenshot 2026-03-26 at 6 08 14 PM" src="https://github.com/user-attachments/assets/48e53e4a-2e04-4d1a-8e03-697e9e689f31" />



## Result:
Thus the program was executed and the output was verified successfully.
