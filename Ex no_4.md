# EX 4 C program to read the age of a person and determine whether he is eligible for marriage (eligible if age ≥ 21).
## DATE:17/03/2026
## AIM:
To write a C program to read the age of a person and determine whether he is eligible for marriage (eligible if age ≥ 21).

## Algorithm
1. Start.
2. Declare a variable value of type char.
3. Prompt the user to enter a value.
4. Read the value using scanf. 
5. Check eligible for marriage.
6. If age >= 21, print "Eligible".
7. If false, print " Not Eligible".
8. End.

## Program:
```
#include <stdio.h>
int main() {
    int age;
    scanf("%d", & age);
    if (age >= 21) {
        printf("You are eligible for marriage.\n");
    } else {
        printf("You are not eligible for marriage.\n");
    }
    return 0;
}
```

## Output:
<img width="650" height="462" alt="Screenshot 2026-03-26 at 6 05 45 PM" src="https://github.com/user-attachments/assets/d614967e-987b-470b-9e18-796abb22c317" />



## Result:
Thus the program was executed and the output was verified successfully.
