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
```
def result(a, b):
    return a % b
    
a = int(input())
b = int(input())
mod_value = result(a, b)

print(f"modulo is {mod_value}")
```
## Output
<img width="549" height="242" alt="image" src="https://github.com/user-attachments/assets/54874ed6-b9a9-434c-8650-fe2451761927" />

## Result
The Python program was successfully executed to calculate the modulo of two numbers using a user-defined function.
