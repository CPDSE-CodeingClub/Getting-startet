
#  Logic Statements in Python
*Understanding Boolean Logic, Comparison Operators, and Conditional Expressions*

Logic statements are a fundamental part of Python programming. They allow your code to **make decisions**, **compare values**, and **control the flow** of a program. Without logic statements, programs would simply run straight through without reacting to changing data or conditions.

---

## 1. Boolean Values: `True` and `False`
Python uses two special values to represent truth:
- `True`
- `False`

These are known as **booleans** (`bool` type).

```python
print(True)
print(False)
print(type(True))
```
output:
```
True
False
<class 'bool'>
````

---

## 2. Comparison Operators
Comparison operators test relationships between values and always evaluate to either **True** or **False**.

| Operator | Meaning | Example | Result |
|----------|----------|----------|--------|
| `==` | equal to | `5 == 5` | `True` |
| `!=` | not equal to | `5 != 3` | `True` |
| `<` | less than | `4 < 10` | `True` |
| `>` | greater than | `7 > 9` | `False` |
| `<=` | less than or equal | `3 <= 3` | `True` |
| `>=` | greater than or equal | `8 >= 6` | `True` |

---

## 3. Logical Operators: `and`, `or`, `not`
Logical operators combine or modify boolean expressions.

### and
Returns `True` only if **both** statements are true.
```python
age = 30
print(age > 10 and age < 40)
print(age > 10 and age < 20)
```
```
output:
```
True
False
```

### or
Returns `True` if **at least one** statement is true.

```python
temperature = 5
print(temperature < 0 or temperature < 30)
print(temperature < 0 or temperature > 30)
```
output:
```
True
False
```

### not
Reverses a boolean value:

```python
print( not(1<2) )
```

---

## 4. Combining Comparisons
Python allows chained comparisons, making expressions more readable:

```python
x = 10
print(5 < x < 20)
```

This is equivalent to:

```python
print(5 < x and x < 20)
```

you can create very complex and advanced logic statements.
by putting a logic statement in brackets its evaluated separately

```python
print((5 < x and x < 20) and not(x == 10))
```
this will evaluate true only if x is between 5 and 20 but not equal to 10 

---

## 5. Conditional Statements (`if`, `elif`, `else`)
Conditional statements execute code only when certain conditions are met.
an if-statement is construted as followed:
```
if logic-statement:
    code to be executed if statement is true
code to be exceuted regadless of the statemnt is true or not
```
it's imprtant to inded the code that belongs to the if statement else python will not know it belongs to the if-statement

### Basic `if` statement
```python
number = 10
if number > 5:
    print("Number is greater than 5")
```

### `if`–`else`
this is used when you want one output if the statement is true and different code if the statement is false

here is an excample of this:

```python
age = 16
if age >= 18:
    print("You can vote!")
else:
    print("You are too young to vote.")
```

### `if`–`elif`–`else`
this is used if you have more then one condition but you do not have to chek every case if one is true.

```python
score = 75
if score >= 90:
    print("Grade: 12")
elif score >= 80:
    print("Grade: 10")
elif score >= 70:
    print("Grade: 7")
else:
    print("Grade: 4")
```


---

## 6. Ternary Conditional Expressions
A quick way to write simple conditions:

```python
message = "Adult" if age >= 18 else "Minor"
```

---

---
## Exercise
If you have read this page, you can now go to the exercise folder and you should be able to solve `` 02 FizzBuzz `` 

