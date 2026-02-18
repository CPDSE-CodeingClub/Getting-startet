
# Introduction to Basic Math in Python

 Python works great as a calculator, but it also provides tools for more advanced mathematical tasks.

This introduction covers the essentials so you can start writing math‑based Python code right away.

---

## Python as a Calculator

At its simplest, Python can evaluate expressions directly:

```python
print(2 + 3)
print(10 - 4)
print(7 * 6)
print(8 / 2)
```

**Output:**

```
5
6
42
4.0
```

---

##  Basic Arithmetic Operators

| Operation | Symbol | Example | Result |
|----------|--------|----------|--------|
| Addition | `+` | `3 + 2` | `5` |
| Subtraction | `-` | `7 - 4` | `3` |
| Multiplication | `*` | `5 * 6` | `30` |
| Division | `/` | `8 / 3` | `2.666...` |
| Floor Division | `//` | `8 // 3` | `2` |
| Modulus (remainder) | `%` | `8 % 3` | `2` |
| powers | `**` | `2 ** 3` | `8` |

---

## Examples

### Exponentiation (powers)
```python
2 ** 5  # 2 to the power of 5
```

### Modulus (finding remainder)
```python
10 % 4  # remainder of 10 divided by 4
```

### Floor Division (integer result)
```python
17 // 3  # divide and round down
```

---

## Combining Operations

Python follows standard math rules:  
**PEMDAS** → Parentheses, Exponents, Multiplication/Division, Addition/Subtraction.

```python
result = (5 + 3) * 2 ** 2 - 10 / 5
print(result)
```

---

## Using the `math` Module

For more advanced math, Python includes a built‑in module called `math`.

```python
import math

print(math.sqrt(25))   # square root
print(math.pi)         # the value of pi
print(math.sin(math.pi / 2))  # sine of 90 degrees
```

---
## Exercise
If you have read this page, you can now go to the exercise folder and you should be able to solve `` 01 basic math `` 
