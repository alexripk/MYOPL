# MYOPL Programming Language Documentation

Welcome to the documentation for MYOPL (MYOPL Your Own Programming Language)! MYOPL is a simple programming language that is designed to be easy to understand and use. This documentation will provide you with an overview of the language, its features, and instructions on how to set it up and get started.

## Table of Contents

1. [Introduction](#introduction)
2. [Getting Started](#getting-started)
    - [Installation](#installation)
    - [Running the Interpreter](#running-the-interpreter)
3. [Syntax](#syntax)
    - [Variables](#variables)
    - [Logical Operators](#logical-operators)
    - [Conditional Statements](#conditional-statements)
    - [Loops](#loops)
    - [Functions](#functions)
4. [Built-in Functions](#built-in-functions)
5. [Examples](#examples)
6. [Conclusion](#conclusion)

## 1. Introduction <a name="introduction"></a>

MYOPL is a programming language that is based on Python. It aims to provide a simplified syntax and a minimalistic set of features while maintaining the power and flexibility of Python. MYOPL supports variables, logical operators, conditional statements, loops, and functions.

## 2. Getting Started <a name="getting-started"></a>

### Installation <a name="installation"></a>

To get started with MYOPL, you can either clone the GitHub repository or download it as a ZIP file. Here are the steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/myopl.git
   ```

   Alternatively, you can download the ZIP file by visiting the repository's page on GitHub and clicking on the "Download" button.

2. Once you have the source code on your local machine, you're ready to set up and run the interpreter.

### Running the Interpreter <a name="running-the-interpreter"></a>

To run the MYOPL interpreter, follow these steps:

1. Navigate to the directory where you cloned or extracted the MYOPL source code.

2. Locate the `interpreter.bat` file.

3. Double-click on `interpreter.bat` to execute it.

   This will start the MYOPL interpreter, and you will see a prompt where you can start entering MYOPL commands.

## 3. Syntax <a name="syntax"></a>

### Variables <a name="variables"></a>

In MYOPL, you can declare variables using the `var` keyword followed by the variable name and an optional initial value. Variable names can contain letters, numbers, and underscores but must start with a letter. Here's an example:

```python
var x = 42
var message = "Hello, world!"
```

### Logical Operators <a name="logical-operators"></a>

MYOPL provides the following logical operators:

- `and`: Logical AND operator
- `or`: Logical OR operator
- `not`: Logical NOT operator

Here's an example of using logical operators in MYOPL:

```python
var x = true
var y = false

var result = x and y  # result is false
```

### Conditional Statements <a name="conditional-statements"></a>

MYOPL supports conditional statements using the `if`, `elseif`, and `else` keywords. Here's an example:

```python
var x = 10

if x > 5 then
    print("x is greater than 5")
elseif x < 5 then
    print("x is less than 5")
else
    print("x is equal to 5")
end
```



### Loops <a name="loops"></a>

MYOPL provides two types of loops: `for` and `while`.

The `for` loop allows you to iterate over a range of values. Here's an example:

```python
for var i = 1 to 5 step 1 then
    print(i)
end
```

The `while` loop allows you to repeatedly execute a block of code while a condition is true. Here's an example:

```python
var i = 1

while i <= 5 then
    print(i)
    var i = i + 1
end
```

### Functions <a name="functions"></a>

You can define your own functions in MYOPL using the `func` keyword. Functions can have parameters and return values. Here's an example:

```python
func greet(name) then
    return "Hello, " + name + "!"
end

var message = greet("Alice")
print(message)  # Output: Hello, Alice!
```

## 4. Built-in Functions <a name="built-in-functions"></a>

MYOPL comes with several built-in functions that you can use in your programs. Here are some of the available functions:

- `null()`: Returns null.
- `false()`: Returns false.
- `true()`: Returns true.
- `pi()`: Returns the value of pi.
- `print(value)`: Prints the value to the console.
- `printret(value)`: Prints the value to the console and returns it.
- `input()`: Reads a line of input from the user.
- `inputint()`: Reads an integer input from the user.
- `clear()`: Clears the console.
- `isNum(value)`: Checks if the value is a number.
- `isStr(value)`: Checks if the value is a string.
- `isList(value)`: Checks if the value is a list.
- `isFunc(value)`: Checks if the value is a function.
- `append(list, value)`: Appends a value to the end of a list.
- `pop(list, index)`: Removes and returns the element at the specified index from a list.
- `extend(list1, list2)`: Extends `list1` by appending all elements from `list2`.
- `len(list)`: Returns the length of a list.

Please refer to the source code for a complete list of built-in functions and their usage.

## 5. Examples <a name="examples"></a>

Here are a few examples to help you get started with MYOPL:

1. Printing "Hello, world!":
   ```python
   print("Hello, world!")
   ```

2. Calculating the factorial of a number:
   ```python
   func factorial(n) then
       if n <= 1 then
           return 1
       else
           return n * factorial(n - 1)
       end
   end

   var result = factorial(5)
   print(result)  # Output: 120
   ```

3. Iterating over a list:
   ```python
   var numbers = [1, 2, 3, 4, 5]

   for var number in numbers then
       print(number)
   end
   ```

## 6. Conclusion <a name="conclusion"></a>

Congratulations! You have completed the MYOPL documentation. You should now have a good understanding of the language's syntax, features, and how to set it up. Feel free to explore and experiment with MYOPL to create your own programs. If you have any further questions or need assistance, don't hesitate to reach out. Happy

 coding with MYOPL!
