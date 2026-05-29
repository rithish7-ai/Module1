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
real = int(input("Enter the real part: "))
imag = int(input("Enter the imaginary part: "))


c = complex(real, imag)

print("Complex Number =", c)
print("Real Part =", c.real)
print("Imaginary Part =", c.imag)
```
## Output
<img width="493" height="220" alt="image" src="https://github.com/user-attachments/assets/7ef57c55-dfd6-4592-a49c-34d856e509fb" />

## Result:
Thus, the Python program that reads two integers, creates a complex number using them, and prints the complex number along with its real and imaginary parts has been executed successfully.
