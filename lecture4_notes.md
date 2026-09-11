# Input and Output in Python

## String Concatentation
- Uses the '+' to make strings bigger string
- This is an example of operator overloading

```python
print("Hello" + " " + "World" + "!") # string concatenation
```

## Inline string formatting (Interpolation)
- Uses f-strings (formatted string literals) to embed expressions in strings

```python
# Formatted string
a = 3
print(f"This print will show an embedded expression as output. The expected expression is: {a}+2 and output is: {a+2}")
```

## Escape Sequence
- Very common one is "\n" which is a new line

```python
# escape sequences: tab, protected characters, unicode characters, backspace.
print("First\tSecond\tThird")
print("Hello,\b\b\b\b World!")
print("He said, \"Hello!\"")
print("Smiley face: \U0001F604")
print("This is a backslash: \\")
```

## Standard Input
- Can read user input using the input() function. It reads a line of text entered by the user and returns it as a string
- If we wanted to enter something like "2+4" python treats it as characters, not numbers, so it would just read "2+4"
- If you want to input a number use the eval() function
    - eval() essentially takes a string and converts it to a number

```python
name = input("Enter your name: ")
print('Your name is: ' + name)

a = "8"
b = eval(a + 6)
print(b)
```

# Basic Data Types
*int:* Integer values or whole numbers (42, -10)

*float:* Floating-point values or rational numbers (3.14, -0.5)

*str:* String or text values, enclosed in single or double quotes  ("Hello, Python!")

*bool:* Boolean values, either True or False

*NoneType:* Represents the absence of a value (None)

Can use the built in function "type()" in Python, we can check the data type of the variable

## Type Conversion
There are two types of conversion of data types

**Implicit type conversion**

**Explicit type conversion**

### Implicit
- Also known as automatic type conversion, a feature in python where the interpreter automaticaly converts data from one data type to another to avoid data loss, programmer doesn't need to give any instructions for it

```python
number_1 = 5 #int
number_2 = 2.5 #float
number_1 = number_1 + number_2 # Implicit conversion to float
# Resulting data type will be a float (7.5), this can be checked by using type()
```

### Explicit
- User converts the data type on their own, can use functions like int(), float(), str(), etc

```python
number_1 = 3
print(float(number_1))
# Will print 3.0, however it would still be an int, would have to change it prior to make it a float, e.g. 
# number_1 = float(number_1)
```

