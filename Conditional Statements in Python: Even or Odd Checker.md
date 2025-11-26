# Conditional Statements in Python

## 🎯 Aim
To write a Python program to check whether the given number is **even** or **odd** using `if...else` statements.

## 🧠 Algorithm
Step 1: Input
Read an integer a from the user.

Step 2: Check Divisibility
Use the modulus operator % to check if a % 9 == 0.

If True, a is divisible by 9.

If False, it is not divisible by 9.

Step 3: Output
Display a message based on the result of the check.

## 🧾 Program
``` python
a=int(input())
if a%9==0:
    print(a,"is divisible by 9")
else:
        print(a,"is NOT divisible by 9")
```
## Output

![image](https://github.com/user-attachments/assets/8f5cd46d-ee17-491d-b1f5-97db00c6942e)

## Result
Thus the python program to check whether the given input is divisible by 9 or not.

# Ex 1:Datatypes-Boolean Expression Evaluation in Python

## 🎯 Aim
To write a Python program that evaluates and prints the results of boolean and arithmetic expressions involving `True` and `False`.

## 🧠 Algorithm

Step 1: Input
Read string a from the user.

Read string b from the user.

Step 2: Comparison
Use the == operator to check whether both strings are exactly the same (including case, whitespace, etc.).

Step 3: Output
Print True if a is equal to b, else print False.

## 💻 Program
``` python
a=(input())
b=(input())
print((a == b))
```

## Output

![image](https://github.com/user-attachments/assets/14e4027f-087f-4243-917e-282e1b2e7e1f)

## Result

Thus the python program to print the boolean value is executed successfully.

# Datatypes-Character Literal in Python

## 🎯 Aim
To write a Python program that prints the characters `'T'` and `'a'` using character literals.

## 🧠 Algorithm
1. Print the character `'T'`.
2. Print the character `'a'`.

## 🧾 Program
``` python
v = 'T'
w = "a"
print(v)
print(w)

```
## Output
![image](https://github.com/user-attachments/assets/db0a8de7-5f0c-499f-95ec-59c683de7cf4)

## Result
Thus the python program to print the character literal is executed successfully.

# 🧮 Datatypes-Complex Number Creation in Python

## 🎯 Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## 🧠 Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

## 💻 Program
``` python
a=int(input())
b=int(input())
comp_num=complex(a,b)
print(comp_num)
print(comp_num.real)
print(comp_num.imag)
```
## Output
![Screenshot 2025-05-22 175436](https://github.com/user-attachments/assets/924e54df-7851-4a42-98bb-cc4155ada47a)

## Result
Thus the python program to convert the real number into complex number is executed successfully.

# Datatypes-Read and Print a String in Python

## 🎯 Aim
To write a Python program to read a string from the user and then print it.

## 🧠 Algorithm
1. Assign a variable named `men_stepped_on_the_moon`.
2. Use `input()` to read a integer from the user and store it in the variable.
3. Print the value stored in the variable.

## 🧾 Program
``` python
men_stepped_on_the_moon=int(input())
print(men_stepped_on_the_moon)
```
## Output
![image](https://github.com/user-attachments/assets/965a06a5-d72a-4862-83d3-b78a166fb084)

## Result
Thus the python program to get the input from the user and print it executed successfully.
