# Booleans
Used to perform logical operators and make decisions in your code.
- Returns boolean values (True or False)
- Primary boolean operators in python are 
    - and (binary)
    - or (binary)
    - not (uniary)

## Truth Tables
| a | b | a and b |
|---|---|---|
| T | T | T |
| T | F | F |
| F | T | F |
| F | F | F |

## Comparison Operators
- Equal (==)
- Not Equal (!=)
- Greater than (>)
etc

These return boolean values

## Order of operations 
In order: 

1. not
2. and
3. or

# Conditional Statements
Allows you to execute specific blocks of code based on conditions. 

## if statements
The "if" statement is used to execute a block of code if a condition is true.

```python
x = 6
if x > 5:
    print("x is greater than 5")
    print("This line will also execute")
print("done")
```
Format is:
if <conditional>:
    <body>
- Indentation is crucial in python, statements with the same identation are called a block of code in python
- All statements with the same identation will be executed by the interpreter if the condition is true
- Also note that "tab" and 4 spaces are actually different and interpreted differently by python even though they look the same

## if-else statement
The if-else statement is used to execute one block of code if a condition is true and another block if it is false

```python
age = 13
if age >= 18:
    print("You can vote.")
    print("This line will also execute")
else:
    print("You cannot vote")
print("done")
```

