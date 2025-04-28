# Experiment No: 1e – SEB-Minimum of Three Numbers

## AIM  
To write a Python program to find the minimum between three integer numbers .

## ALGORITHM  
1. Begin the program.  
2. Read the three numbers: `num1`, `num2`, and `num3` from the user.  
3. Compare `num1`, `num2`, and `num3` to find the smallest number:  
   - If `num1` is less than or equal to both `num2` and `num3`, then `num1` is the minimum.  
   - Else, if `num2` is less than or equal to both `num1` and `num3`, then `num2` is the minimum.  
   - Otherwise, `num3` is the minimum.  
4. Print the minimum value along with the input numbers in the format:  
   `"The minimum of num1, num2, num3 is min_num."`  
5. Terminate the program.

## PROGRAM
```
a = int(input())
b = int(input())
c = int(input())
d = (a) if a<b and a<c else (b) if b<a and b<c else (c)
print (f"The Smallest  of the three a= {a} b= {b} c= {c} is {d}")```

## OUTPUT
![image](https://github.com/user-attachments/assets/5a006f31-ac8c-4192-8e91-cba08f9e5540)

## RESULT
Thus the Python program for finding the minimum between three integer  numbers is implemented and executed successfully.
