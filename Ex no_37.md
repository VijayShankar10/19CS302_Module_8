# Hackerrank problem - 2

Create an array of size n dynamically, and read the values from stdin. Iterate
the array calculating the sum of all elements. Print the sum and free the
memory where the array is stored.
While it is true that you can sum the elements as they are read, without first
storing them to an array, but you will not get the experience working with
an array. Efficiency will be required later.
Input Format
The first line contains an integer, n.The next line contains space-separated
integers
Output Format
Print the sum of the integers in the array.

## AIM:
To write a program to print the sum of the integers in the array.
## ALGORITHM:
1. Start.
2. Define a variables.
3. Write a program to print the sum of the integers in the array.
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End.

### Developed By:
```
Developed by: Vijay Shankar M
RegisterNumber: 212222040178
```

## PROGRAM:
```c program
#include<stdio.h>
int main()
{
int i,n,sum=0,arr[100];
scanf("%d",&n);
{
for(i=0;i<n;i++)
scanf("%d",&arr[i]);
for(i=0;i<n;i++)
sum=sum+arr[i];
i++;
}printf("%d",sum);
}
```
## output:
![Screenshot 2025-05-07 220744](https://github.com/user-attachments/assets/50a5138e-789e-4b45-ab4c-17ee6e0eb62d)
## RESULT:
Thus, the program is executed and verified successfully.
