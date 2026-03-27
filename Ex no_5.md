# EX 5 C program to calculate the total marks, average, and percentage of marks obtained in seven subjects.
## DATE:
## AIM:
To write a C program to calculate the total marks, average, and percentage of marks obtained in seven subjects.

## Algorithm
Start the program. Read marks of 7 subjects from the user and calculate the total. Calculate the average marks by dividing total by 7. Calculate the percentage based on total marks out of 700. Display the total marks, average, and percentage, then end the program.
## Program:
```
/*
Program to calculate the total marks, average, and percentage of marks obtained in seven subjects.
Developed by: ARAVINDHAN K A P
RegisterNumber: 212222063001
*/

#include <stdio.h>

int main() {
    int marks[7], total = 0;
    float average, percentage;
    int i;

    printf("Enter marks for 7 subjects:\n");
    for (i = 0; i < 7; i++) {
        scanf("%d", &marks[i]);
        total += marks[i];
    }

    average = total / 7.0;
    percentage = (total / 700.0) * 100;

    printf("Total Marks = %d\n", total);
    printf("Average Marks = %.2f\n", average);
    printf("Percentage = %.2f%%\n", percentage);

    return 0;
} 
```

## Output:
<img width="413" height="416" alt="image" src="https://github.com/user-attachments/assets/90450b8b-0f40-4ba3-bdfd-f764fcc056c3" />



## Result:
Thus the program was executed and the output was verified successfully.
