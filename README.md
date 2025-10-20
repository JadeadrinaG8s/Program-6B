# Program-6B
C module 6
EX NO-6)B)a C program to count total number of even elements in an array 
DATE:20/10/25
NAME:JADE ADRINA J
REF NO:25017000
AIM:TO Write a C program to count total number of even elements in an array 
ALGORITHM:1)TO take a array as input from the user.2)iterate the array using for loop.3) add 1 to count if the element is divisible by 2.4) print the output using printf() function.
PROGRAM:
```
#include<stdio.h>
int main()
{
    int n,i,c=0;
    scanf("%d",&n);
    int arr[n];
    for(i=0;i<n;i++){
        scanf("%d",&arr[i]);
    }
    for(i=0;i<n;i++){
        if(arr[i]%2==0){
            c=c+1;
        }
    }
    printf("Total even elements: %d",c);
}
```
OUTPUT:
<img width="824" height="326" alt="Screenshot 2025-10-20 091241" src="https://github.com/user-attachments/assets/ba053fde-d869-406f-957f-2025a71d65a1" />
RESULT:
Thus, C program to count total number of even elements in an array has been executed successfully.
