**Exp.No:2d
LOOPING PATTERNS - PRINTING PATTERN**


**AIM** 

To write a Python program to print a pyramid pattern of numbers based on the number of rows entered by the user.


**ALGORITHM**

1. Begin the program.
2. Read the number of rows a from the user using input() and convert it to an integer.
3. Use a for loop that runs from i = 1 to a (inclusive) to handle the number of rows.
4. Inside the loop, use a nested for loop that runs from j = 1 to i (inclusive) to print numbers in each row.
5. Print each number j followed by a space, and keep the output on the same line using end=" ".
6. After the inner loop ends, move to the next line using print(end="\n").
7. Repeat steps 4–6 until the pyramid is printed.
8. Terminate the program.





**PROGRAM**

**212223060265 - SMRITHI K **

a=int(input())
for i in range(1,a+1):
    for j in range(1,i+1):
        print(j,end=" ")
    print(end="\n")



**OUTPUT**

![image](https://github.com/user-attachments/assets/e77de4f1-4356-4e71-870a-79da6cb42627)


**RESULT**

Thus the program to print a pyramid pattern of numbers based on the number of rows entered by the user has been implemented and executed successfully.
