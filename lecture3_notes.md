# Variables
A named storage location in a computers memory that can hold data, such as numbers, strings, or other objects. Allows us to store and manipulate information within a program.

Python has specific rules for naming variables:
- Must begin with a letter (a-z, A-Z) or an underscore.
- Remaining characters can include letters, numbers, and underscores.
- No other character that is not a letter or a number or an underscore is permitted.
- Variable names are case sensitive. my_variable and My_variable are two different variables.

To store a value in a variable we use the assignment operator (=). We can also give an expression that evaluates to a value as well.

```python
my_var = 2**2+1
print(my_var)
```

In python we also have reserved words like "None", which can't be a variable name.

## Assignment Operator (=)
variable_name = value

Values can be strings, integers, floats, booleans, etc and you don't have to say what it is or anything.

```python
name = "Alice"
number_1 = 67
is_student = True
```

Statements within a block are executed sequentially. If you don't run a block Python will ignore it and for variables go on what was previously ran, unless you have restarted the session which then nothing is assigned yet.

## Special Assignment Operators
=+, -=, *=, /=, %/, **=, and //=.

Equivalent to: 

```python
x += a
# or, same thing
x = x + a
```

## Multiple Assignment
Assigning mutliple variables on the same line.

```python
p, q = 83.4, 2**0.5 # Value 83.4 will be assigned to p and the result of 2**0.5 will be q
p = q = 83.4 # Value 83.4 will be assigned to both p and q
```
