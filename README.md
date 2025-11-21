# 2A.Built-in Functions -Binary Conversion Using Built-in Functions in Python

##  Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

##  Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

##  Program
```
x=16
y=bin(x)
print(y)
```

## Output
<img width="446" height="99" alt="image" src="https://github.com/user-attachments/assets/b68df37d-2c2e-4632-babe-dc44b3a9ccbb" />


## Result
Thus,the Python program to convert the number 16 into its binary representation using built-in Python functions is created successfully.


## 2B.Function in python: Modulo calculator

##  Aim
To write a Python program that defines a function to accept two values and return their modulo value.

##  Algorithm
1.Start the program.

2.Define a function that takes two parameters a and b.

3.Inside the function, compute the modulo using a % b.

4.Return the result.

5.In the main program, read two input values from the user.

6.Call the function with the given inputs.

7.Display the modulo result.

8.End the program.

##  Program
```
def result(a, b):
    d = a % b
    print("modulo is", d)

a = int(input())
b = int(input())
result(a, b)


```

## Output
<img width="445" height="147" alt="image" src="https://github.com/user-attachments/assets/06ba86cb-6811-4cde-bc3d-8b3152038888" />




## Result
The program successfully reads an upper limit from the user and prints all the prime numbers within the given range.


# 2C.Lambda Function in Python: multiplication Three Numbers

##  Aim
To write a Python program that defines a **lambda function** which takes three arguments `a` ,`b`,`c` and returns their multiplication.

##  Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `result` that returns `a * b`*`c`.
3. Call the function with the user inputs and print the result.

##  Program
```
f=lambda a,b,c:a*b*c
a=int(input())
b=int(input())
c=int(input())
result=f(a,b,c)
print(result)
```

## Output
<img width="443" height="174" alt="image" src="https://github.com/user-attachments/assets/8c323aaa-e9e2-4f9a-8951-3c4c9db70a81" />


## Result
Thus,the Python program that defines a lambda function which takes three arguments a , b,c and returns their multiplecation is created successfully.


#2D. Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

##  Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

##  Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

##  Program
```
def pascal_triangle(n):
    for i in range(n):
        print(" " * (n - i - 1), end="")
        num = 1
        for j in range(i + 1):
            print(num, end=" ")
            num = num * (i - j) // (j + 1)   
        print()

rows = int(input())
pascal_triangle(rows)
```

## Sample Output
<img width="446" height="337" alt="image" src="https://github.com/user-attachments/assets/864fbdea-260a-47ec-93de-87f4eb3c19c7" />


## Result
Thus,the Python program that generates Pascal's Triangle using numbers. The number of rows is accepted from the user is created successfully.

## 2E. Loops in Python: Palindrome Number Checker

##  Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

##  Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

##  Program
```
num=int(input())
rev=0
temp=num
while temp>0:
    rev=(10*rev)+temp%10
    temp//=10
if rev==num:
    print("The given number {} is a Palindrome".format(num))
else:
    print("The given number {} is not a palindrome".format(num))

```
## Output
<img width="446" height="120" alt="image" src="https://github.com/user-attachments/assets/32eb57c2-6d71-40d2-8443-502822e01715" />


## Result
Thus,the Python program that checks whether a given number is a palindrome using loops is created successfully.
