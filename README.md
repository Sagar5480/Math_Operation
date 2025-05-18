# Math Operations Script

This Python script performs a series of mathematical operations, divided into two main tasks:

---

## 🔢 Task 1: Factorial Calculation

This task calculates the factorial of a user-input number using recursion.

### ✅ Description:

* Defines a recursive function `fact(a)` to compute the factorial.
* Takes an integer input from the user.
* Prints the factorial result.

### 🧾 Code:

```python
def fact(a):
    if a < 2:
        return 1
    else:
        return a * fact(a - 1)
```

### 📤 Sample Output:

```
Enter your Number: 5
Factorial of the number is: 120
```

---

## 🧮 Task 2: Mathematical Operations

This task performs several mathematical operations on the same input number:

* Square root using `math.sqrt()`
* Natural logarithm using `math.log()`
* Radian conversion using `math.radians()`
* Sine value using `math.sin()`

### 🧾 Complete Code:

```python
import math

# Task 1: Factorial Calculation
def fact(a):
    if a < 2:
        return 1
    else:
        return a * fact(a - 1)

a = int(input("Enter your Number: "))

# Calculate and print factorial
result = fact(a)
print("Factorial of the number is:", result)

# Task 2: Mathematical Operations
b = math.sqrt(a)
print("Square root of the number is:", b)

natural_log_a = math.log(a)
print("Natural log of the number is:", natural_log_a)

a_radians = math.radians(a)
sine_value = math.sin(a_radians)
print("Sine value of the number (in radians) is:", sine_value)
```

### 📤 Sample Output (for input `5`):

```
Enter your Number: 5
Factorial of the number is: 120
Square root of the number is: 2.23606797749979
Natural log of the number is: 1.6094379124341003
Sine value of the number (in radians) is: 0.08715574274765817
```

---

## ▶️ How to Run

1. Make sure Python 3 is installed.
2. Save the code in a file, e.g., `math_script.py`.
3. Open a terminal and run:

   ```bash
   python math_script.py
   ```

---


Let me know if you want this as a downloadable file or converted to a Jupyter Notebook format.
