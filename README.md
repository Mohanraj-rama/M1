
# EX-01-Datatypes-Operators
## AIM:
Write a C program to read 3 characters one by one and print the characters in a reverse order.

## ALGORITHM:
1.	Declare three character variables to store the input characters.
2.	Use the scanf function to read the characters one by one from the user.
3.	Print the characters in reverse order using the printf function.
4.	End the program.

## PROGRAM:

```
#include <stdio.h>

int main() {
    char ch1, ch2, ch3;
    scanf(" %c", &ch1);
    scanf(" %c", &ch2);
    scanf(" %c", &ch3);
    printf("Characters in reverse order: %c %c %c\n", ch3, ch2, ch1);

    return 0;
}

```

## OUTPUT:


![image](https://github.com/user-attachments/assets/c1efb10a-ed76-47ab-85fa-9e8673ccdc5c)















## RESULT:
Thus the program to read 3 characters one by one and print the characters in a reverse order has been executed successfully.


# EX-02- Conditional-Statements
## AIM:
Write a C program to read A values and check whether A is positive number or not.

# ALGORITHM:
1.	Declare a variable to store the input value A.
2.	Use the scanf function to read the value of A from the user.
3.	Check if the value of A is greater than zero.
4.	If A is greater than zero, print a message indicating that it's a positive number. 
5.	Otherwise, print a message indicating that it's not a positive number.
6.End the program.

# PROGRAM:

```
#include <stdio.h>
int main()
{
    int a;
    scanf("%d",&a);
    if (a>=0)
    {
        printf("a is positive number");
    
    }
    else
    {
        printf(" ");
    }
    return 0;
}
```
# OUTPUT:



![image](https://github.com/user-attachments/assets/efc1f3a4-8b4c-4636-a96c-28701915341e)







# RESULT:
Thus the program to read A values and check whether A is positive number or not has been executed successfully.
 
 
 


# EX-03- Operators-Expressions
## AIM:
Write a program to find minimum between two fraction numbers using conditional operator or ternary operator.

## ALGORITHM:
1.	Declare variables to store the two fraction numbers and the result.
2.	Use the printf function to prompt the user to enter the first fraction number (numerator and denominator separately).
3.	Use the scanf function to read the numerator and denominator of the first fraction.
4.	Repeat steps 2 and 3 to get the second fraction from the user.
5.	Calculate the decimal values of both fractions by dividing the numerators by the denominators.
6.	Use the conditional (ternary) operator to compare the decimal values and store the minimum value in the result variable.
7.	Print the minimum value.

## PROGRAM:
```
#include <stdio.h>

int main() {
    float num1, den1, num2, den2, fraction1, fraction2;
    scanf("%f %f", &num1, &den1);
    scanf("%f %f", &num2, &den2);
    fraction1 = num1 / den1;
    fraction2 = num2 / den2;
    float min = (fraction1 < fraction2) ? fraction1 : fraction2;

    printf("Minimum between %f and %f is %.3f\n", min);

    return 0;
}
```

## OUTPUT:



![image](https://github.com/user-attachments/assets/4002830d-32ac-457a-93a0-f519dc8886b2)






## RESULT:
Thus the program to find minimum between two fraction numbers using conditional operator or ternary operator has been executed successfully.




# EX-04- Using Conditional Statements

## AIM:
Write a C program to check whether the input value is equal to 1 using simple if statement

## ALGORITHM:
1.	Declare a variable to store the input value.
2.	Use the scanf function to read the input value from the user.
3.	Use an if statement to check if the input value is equal to 1.
4.	If the condition in the if statement is true, print a message indicating that the input value is equal to 1.
5.	Otherwise, print a message indicating that it's not equal to 1.
6.	End the program.

## PROGRAM:
```
#include <stdio.h>
int main()
{
    int a;
    scanf("%d",&a);
    if (a==0) printf("FALSE");
    else printf(" ");
    return 0;
}

```

## OUTPUT:





![image](https://github.com/user-attachments/assets/513ed47b-5a28-4bae-b201-846aeb9b9853)





	

## RESULT:
Thus the program to check whether the input value is equal to 1 using simple if statement has been executed successfully



# EX-05- Calculating Total, Percentage, And Division Using Conditional Statements 
## AIM:
To write a C program that reads marks of three subjects, calculates the total and percentage, and then determines the division (First, Second, Pass, or Fail) based on the percentage and minimum marks criteria.
## ALGORITHM:
1.	Start
2.	Declare integer variables m1, m2, m3 for marks, and float variables tot, per.
3.	Input the marks for three subjects.
4.	Calculate total marks: tot = m1 + m2 + m3
5.	Calculate percentage: per = tot / 3
6.	Display total and percentage.
7.	Check if all marks are greater than or equal to 40:
8.	If yes:
a.	If percentage >= 60: Print “Division = First”
b.	Else if percentage >= 48: Print “Division = Second”
c.	Else if percentage >= 36: Print “Division = Pass”
9.	Else: Print “Division = Fail”
10.	End
## PROGRAM:
```
#include <stdio.h>
int main()
{
    float a,b,c,d,e,f,t,av;
    scanf("%f%f%f%f%f%f",&a,&b,&c,&d,&e,&f);
    t=a+b+c+d+e+f;
    printf("Total marks = %.2f",t);
    av=t/6;
    printf("\nAverage marks = %.2f \nPercentage = %.2f",av,av);
    return 0;
    
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/dd6cfc05-541f-4204-a5bd-e48b288bbb3a)

## RESULT:
The program successfully takes three subject marks, calculates the total and percentage, and correctly determines the division based on predefined grading logic.

