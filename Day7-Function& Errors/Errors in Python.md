# Understanding Errors in Python

>Errors are an essential part of programming and occur when something goes wrong in your code. Whether you're a beginner or an intermediate Python developer, understanding the types of errors and how to handle them is crucial for debugging and writing robust code.

In this guide, we'll explore common types of errors in Python along with examples and tips to fix them.

- [Understanding Errors in Python](#understanding-errors-in-python)
    - [📌 1. Syntax Error](#-1-syntax-error)
    - [📌 2. Indentation Error](#-2-indentation-error)
    - [📌 3. Name Error](#-3-name-error)
    - [📌 4. Type Error](#-4-type-error)
    - [📌 5. Value Error](#-5-value-error)
    - [📌 6. Index Error](#-6-index-error)
    - [📌 7. ModuleNotFoundError / Import Error](#-7-modulenotfounderror--import-error)
    - [📌 8. FileNotFoundError](#-8-filenotfounderror)
    - [📌 9. Memory Error](#-9-memory-error)
    - [📌 10. Timeout Error](#-10-timeout-error)
    - [Few More Errors](#few-more-errors)
- [✅ Tips to Handle Errors](#-tips-to-handle-errors)

---
### 📌 1. Syntax Error
Occurs when Python cannot understand the code because it doesn’t follow correct syntax rules.

**Example**:

``` python
if x > 3
    print("x is greater than 3")
```
> you can fix this using correct syntax like missing colon in the example

**Correct**
``` python
if x > 3:
    print("x is greater than 3")
```
---

### 📌 2. Indentation Error

Occurs when Python expects indentation (spaces or tabs) to define code blocks, but it is missing or inconsistent.

**Example**:
``` python

def greet():
print("Hello")
```
> Ensure proper indentation:

**Correct**
```python
def greet():
    print("Hello")
```
----

### 📌 3. Name Error

Occurs when a variable or function is not defined or is misspelled.

**Example**:
``` python
print(value)
```
>You can fix this by correcting the variable name spelling like Checking the spelling:

**Correct**
```python
value = 5
print(value)
```
---


### 📌 4. Type Error
Occurs when an operation is performed on an inappropriate data type.
**Example:**
```python
num = 5
text = " apples"
print(num + text)
```

> Convert types appropriately like for this You can fix this by correcting the variable name spelling.:

**Correct**
```python
print(str(num) + text)
```
--- 

### 📌 5. Value Error

Occurs when a function receives an argument of the right type but an inappropriate value.

**Example:**

` int("abc") `

> Ensure the value is valid like You can fix this by providing a string that can be converted to an integer.

**Correct**
`int("123")`

---


### 📌 6. Index Error

Occurs when trying to access an index that does not exist in a list or other indexable structure.

**Example:**
```python
numbers = [1, 2, 3]
print(numbers[5])
```
> Check the length before accessing:

**Correct**
```python
if len(numbers) > 5:
    print(numbers[5])
```

----

### 📌 7. ModuleNotFoundError / Import Error

Occurs when Python cannot find the module or import fails.

**Example**:
`import numppy`

> Check the module name and install it if needed.You can fix this by correcting the module name and ensuring it is installed.:

**Correct**
```python
pip install numpy
import numpy
```
---

### 📌 8. FileNotFoundError

Occurs when a file operation fails because the file does not exist.

**Example**:
```python
with open("nonexistent_file.txt") as file:
    data = file.read()
```

> Ensure the file exists or handle the error.You can fix this by checking if the file exists or handling the error with try-except.:

**Correct**
```python
try:
    with open("file.txt") as file:
        data = file.read()
except FileNotFoundError:
    print("File not found!")

```
### 📌 9. Memory Error

Occurs when your program runs out of memory.
**Example**:

`big_list = [1] * (10**10)`

> Optimize memory usage or use generators:

**Correct**
``` python
for i in range(10**10):
    print(i)
```
---

### 📌 10. Timeout Error
Occurs when an operation exceeds the allotted time to complete, often seen in network or machine learning tasks.

**Example:**

```python
# In ML training
model.fit(data, timeout=60)
```
> Set a reasonable timeout or handle it with retries.

----
###  Few More Errors
* Attribute Error
* Zero Divison Error
* KeyError
* Recursion Error
---

# ✅ Tips to Handle Errors

* Use try-except blocks to catch and manage exceptions.

* Always read the error message carefully.

* Use debugging tools or print statements to trace the problem.

* Start with smaller code and scale up.

