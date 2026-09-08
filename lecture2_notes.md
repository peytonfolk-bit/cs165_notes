# Interpreted Languages

- Python is one and interpeter languages are more secure and robust to bad code.
- It will tell you what is actually wrong and why commands can't execute.
- Also, you write the code once and it works on any device.
- Can also utilize packages in python.

# Python Statements, Expressions, and Comments

**Statement:** a complete line of code that performs an action or task. Python code consists of a series of statements, and each statement is executed sequentially. The entire line is a statement.

- Ex: 
```python 
print(1+1)
print(67*2)
print(4*3-6)
```
**Expression:** inside the print statement is the expression "4*3-6" for example. Expression is the value the print statement would use.

- Note that without a print statement, the interpreter would just do the last line of code computed, for example:
```python
1+1
67*2
4*3-6
```
- Would only print "6".

**Comments:** Comments begin with # in python, comments are human readable text to basically give information on what the script is doing.
- Multiple lines of comments use ''' or """ 
```python
'''
Hello my name is P Folk
'''
```

# Arithmetic Operators
**(+) Addition:** The operator for addition is the plus sign. Can be binary or unary.
**(-) Subtraction:** The operator for subraction is the minus sign. Can be binary or unary.
**(*) Multiplication:** The operator for multiplication is the asterisk sign. Binary.
**(/) Division:** The operator for division is the slash sign. Binary.

- 2+3, the 2 and the 3 are the *Operands*
- Not (!=) is an example of a statement when there would be one *Operand*
    - Ex: 
```python
if (p != 1)
```

**(//) Floor Division:** Binary operator. 8//3 = 2, where as 8/3 = 2.666...
**(%) Remainder:** Binary. 7%3 = 1.
**Exponentiation:** (**) Raises left operand to the power of the right operand.

- BEDMAS applies like normal math. Modulus and floor division are with normal division and multiplication.