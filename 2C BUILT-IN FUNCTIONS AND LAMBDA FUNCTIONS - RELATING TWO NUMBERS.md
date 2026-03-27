**Exp.No:2e  
SEB - SUM OF ODD NUMBER SERIES**

**AIM**

To write a Python program to calculate the sum of the odd number series from 1 to N using a loop.


**ALGORITHM**

1. Start the program.
2. Read a number num from the user using input().
3. Convert the input to an integer using int().
4. Initialize a variable sum to 0 to store the total sum.
5. Loop from i = 1 to num (inclusive):
  Check if i is odd using i % 2 != 0.
  If true, add i to sum.
6. After the loop, print the result in the format:
  "The sum of the series = <sum>"
7. End the program.



**PROGRAM**

**212223060265 - SMRITHI K**

num=int(input())
sum=0
for i in range(1,num+1):
    if(i%2!=0):
        sum+=i
    
print(f"The sum of the series =  {sum}")


**OUTPUT**

![image](https://github.com/user-attachments/assets/b19d1e3f-9ab9-4ed3-9b0c-27bcb7065204)


**RESULT**

Thus the program to calculate the sum of the odd number series from 1 to N using a loop has been implemented and executed successfully.
