# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program
    x=16
    y=bin(x)
    print(y)

## Output
<img width="326" height="277" alt="image" src="https://github.com/user-attachments/assets/4b729d95-6599-4143-af4f-875495b7700f" />

## Result
Thus,the Python program to convert the number 16 into its binary representation using built-in Python functions is created successfully

# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program
    def result(a, b):
        modulo_value = a % b
        return modulo_value
    
    a=int(input())
    b=int(input())
    print("modulo is", result(a, b))


## Output
<img width="567" height="317" alt="image" src="https://github.com/user-attachments/assets/bcfa8bd4-1c07-494f-8fb5-791014a12285" />

## Result
Thus,the Python program that defines a function which accepts two values and returns their modulo using the % operator is created successfully.


# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
    i=int(input())
    j=int(input())
    z=int(input())
    
    f = lambda a, b,c: a+b+c
    
    print(f(i, j,z))

## Output
<img width="439" height="343" alt="image" src="https://github.com/user-attachments/assets/7e4e34d2-39c0-4ac1-acb1-65acf6c95d55" />

## Result
Thus,the Python program that defines a lambda function which takes two arguments a and b, and returns their sum is created successfully


# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

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

---

## 🧪 Program
    import math
    rows = int(input("Enter the number of rows for Pascal's Triangle: "))
    for n in range(rows):
    print(' ' * (rows - n - 1), end='')

    for k in range(n + 1):
        value = math.comb(n, k) 
        print(value, end=' ')

    print()

## Sample Output
<img width="1493" height="675" alt="image" src="https://github.com/user-attachments/assets/ddef9934-f6a8-4528-a492-1f6425e06914" />



## Result
Therefore the given Python Program has been executed successfully and the output has been verified.
