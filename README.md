# Introduction to Python
Data analysis is a broad term that covers a wide range of techniques that enable revealing any insights and relationships that may exist within raw data. As might be expected, Python lends itself readily to data analysis. 
# Variable
A variable is a storage location (in a computer's memory) for holding a value of a specific data type.

<div align="center"><img src="https://github.com/salsanssp/Python-for-Data-Analyst/assets/166114037/7448e626-03cd-4c4c-a056-fa8e153a8300" /></div>

# Data Type (1)
The built-in data types in Python include three main categories:

## 1. Numbers
In Python the numeric data type "numbers" is divided into three: 
1. integer 
2. float
3. complex

**example**

<div align="center"><img src="https://github.com/salsanssp/Python-for-Data-Analyst/assets/166114037/20283ceb-e9a3-423f-91d4-39d42b261eac" /></div>

> The difference between the integer data type and float is the presence of decimal points.

> The value of a complex number is written in the form x+yj, where x is a real number and yj is an imaginary number

## 2. String
A string is a sequence of Unicode characters declared with single or double quotes. Multi-line strings can be indicated by three single quotes ('''), double quotes ("""), or \n.

**example**

<div align="center"><img src="https://github.com/salsanssp/Python-for-Data-Analyst/assets/166114037/bc0fafd7-e289-4725-bf3c-1abdc18e0a73" /></div>

## 3. Boolean
The Boolean data type, or Bool, is a subtype of integers that only has two constant values: True or False.

**example**

<div align="center"><img src="https://github.com/salsanssp/Python-for-Data-Analyst/assets/166114037/c4582f95-52bb-419d-9c02-4ab91f042329" /></div>

# Other Data Type (2)

Data types in Python include:

## 1. List
list is a type of ordered sequence data, which can be called by its index (starting from zero), and is one of the commonly used variables in Python. It's similar, but not identical to arrays in other programming languages. The difference is that elements in a Python list do not have to have the same data type.

**example:**

<div align="center"><img src="https://github.com/salsanssp/Python-for-Data-Analyst/assets/166114037/63ff8c57-5189-41ce-bb72-ee94e4a14ec3" /></div>

# 2. Slicing

Refers to the process of extracting a segment from a string, list, or tuple. It allows to retrieve a particular range of elements by specifying their indices.

<div align="center"><img src="https://github.com/Vanz92x/Python-for-Data-Analyst/assets/165736197/b3444806-f21e-464d-a468-4b8cd1bd3106" /></div>

## 3. Tuple

Tuple is a type of list whose elements cannot be changed. Generally, tuples are used for data that is write-once, and can be executed more quickly. Tuples are defined with brackets [ ] and elements separated by commas.

<div align="center"><img src="https://github.com/Vanz92x/Python-for-Data-Analyst/assets/165736197/349897f9-479d-4d2a-9b88-bd4b518aa8f4" /></div>

## 4. Set

The SET data type is a type that stores unique elements. Numbers in elements in SET can be of type Vary, but cannot be Null This data type cannot perform slicing. 
<div align="center"><img src="https://github.com/Vanz92x/Python-for-Data-Analyst/assets/165736197/a1be0054-0bd2-4063-acb7-856ffbd53190" /></div>

Union: Combines two data into one without repetition
  <div align="center"><img src="https://github.com/Vanz92x/Python-for-Data-Analyst/assets/165736197/d786422e-2687-40c6-8b5e-b90eb016a8eb" /></div>

Intersect: data that combines data that is repeated in both data.
 <div align="center"><img src="https://github.com/Vanz92x/Python-for-Data-Analyst/assets/165736197/fe61de55-9637-4b40-b2ba-18d9aa895bbd" /></div>

## 5. Dictionary

Dictionaries are used to store data values in key:value pairs. A dictionary is a collection which is ordered, changeable and do not allow duplicates. Dictionaries can be used to store small to large data. To access the data, we must know the key. In Python, dictionaries are defined with braces and appendages:

1) Each element of a key-value pair is separated by a comma (,)
2) Key and value are separated by a colon (:)
3) Key and Value can be any type of variable/object.

 <div align="center"><img src="https://github.com/Vanz92x/Python-for-Data-Analyst/assets/165736197/3e03baaf-35ad-4e5e-b684-c0185ef4fefe" /></div>


## Operator (2)
Operators in Python are symbols used to perform operations on variables and values.

## 1. Summation or Addition (+)
The Summation or Addition (+) operator is used to add numeric values or combine strings.
 <div align="center"><img src="https://github.com/Vanz92x/Python-for-Data-Analyst/assets/165736197/a23c69d9-250e-4c6c-870e-70a7f65a5705" /></div>

 ## 2. Subtraction (-)
Subtraction (-) is used to subtract numeric values or process subtraction operations on numeric data types. But The subtraction operation between two strings is invalid in Python and will produce an error, because the subtraction operator (-) does not apply to the string data type in Python.
 <div align="center"><img src="https://github.com/Vanz92x/Python-for-Data-Analyst/assets/165736197/af3d6d57-a04c-49f1-9b54-befebba8a413" /></div>

 # 3. Multiplication (*)
The multiplication operator (*) is used to multiply numeric values or repeat strings.

  - Repetition String:  Repeating or doubling a string "n" times
    <div align="center"><img src="https://github.com/Vanz92x/Python-for-Data-Analyst/assets/165736197/2c8152fb-33bc-4705-9247-7e7a028b8a7e" /></div>

  - Rank (**):  Calculate the power or exponential of a number
     <div align="center"><img src="https://github.com/Vanz92x/Python-for-Data-Analyst/assets/165736197/4ae8c703-0b19-4fc9-96c9-fa51cb9301d2" /></div>

 # 4. Division (/)
Division (/) in Python is used to perform a division operation between two numeric values, and the result will always be a float number (decimal).
 <div align="center"><img src="https://github.com/Vanz92x/Python-for-Data-Analyst/assets/165736197/912e25ee-0a9c-48ec-b39b-fa5103e09ead" /></div>

  - Intersection or Floor Division (//): Produces a division result in the form of the largest integer that is less than or equal to the division result.
  <div align="center"><img src="https://github.com/Vanz92x/Python-for-Data-Analyst/assets/165736197/6d646690-5146-4e2c-9b1f-1e10f4903f74" /></div>

  - Modula (%): Calculate the remainder of the division result between two numeric values.
    <div align="center"><img src="https://github.com/Vanz92x/Python-for-Data-Analyst/assets/165736197/cb30eb9e-4c1d-4cac-b408-76f36e5efe40" /></div>


# Input and Output
The input() function in Python is a useful tool for allowing programs to interact with users and receive input directly from the keyboard. By using this function, users can be prompted to enter values or text that can be used in the program.

For example:

<div align="center"><img src="https://github.com/Aisyahrahmap/Python-for-Data-Analyst-1/assets/166115307/1adcb163-4e4e-44a2-be19-427a308570b9"/></div>

Because the return data type of the input() function is a string, we need to convert its type according to our needs.

<div align="center"><img src="https://github.com/Aisyahrahmap/Python-for-Data-Analyst-1/assets/166115307/bf406a91-6abb-44b2-afbb-79dd24f9eb18"/></div>

# Conditional Statements
Conditional Statements are statements in Python that provide a choice for the control flow based on a condition. It means that the control flow of the Python program will be decided based on the outcome of the condition.
### 1. If Conditional Statement
If the simple code of block is to be performed if the condition holds then the if statement is used.
<div align="center"><img src="https://github.com/Aisyahrahmap/Python-for-Data-Analyst-1/assets/166115307/c2c0dd3c-9e35-4a85-9163-9ab9120ff465"/></div>

### 2.If else Conditional Statements
In a conditional if Statement the additional block of code is merged as an else statement which is performed when if condition is false.
<div align="center"><img src="https://github.com/Aisyahrahmap/Python-for-Data-Analyst-1/assets/166115307/786391d9-e7d7-4b79-8d24-1f0d25eac08a"/></div>

### 3.Nested if..else Conditional Statements in Python
Nested if..else means an if-else statement inside another if statement. Or in simple words first, there is an outer if statement, and inside it another if – else statement is present and such type of statement is known as nested if statement. We can use one if or else if statement inside another if or else if statements.
<div align="center"><img src="https://github.com/Aisyahrahmap/Python-for-Data-Analyst-1/assets/166115307/41fc74d7-57f2-4f56-b72d-a6cccb3bbce6"/></div>

### 4.If-elif-else Conditional Statements in Python
The if statements are executed from the top down. As soon as one of the conditions controlling the if is true, the statement associated with that if is executed, and the rest of the ladder is bypassed. If none of the conditions is true, then the final “else” statement will be executed.
<div align="center"><img src="https://github.com/Aisyahrahmap/Python-for-Data-Analyst-1/assets/166115307/c6eaadd9-ccac-446e-95ca-fe08797d70c5"/></div>

### 5. Ternary Expression Conditional Statements in Python
The Python ternary Expression determines if a condition is true or false and then returns the appropriate value in accordance with the result. The ternary Expression is useful in cases where we need to assign a value to a variable based on a simple condition, and we want to keep our code more concise — all in just one line of code.
<div align="center"><img src="https://github.com/Aisyahrahmap/Python-for-Data-Analyst-1/assets/166115307/1d955b50-7f22-43cf-9181-d7ce30284685"/></div>

# For Loop
A for loop is a type of definite iteration that is used to iterate over a sequence of items, such as a list, a tuple, a dictionary, a set, or a string. A for loop executes a block of code once for each item in the sequence, until the sequence is exhausted or a break statement is encountered

### 1. Python For Loop with List
This code uses a for loop to iterate over a list of strings, printing each item in the list on a new line. The loop assigns each item to the variable I and continues until all items in the list have been processed.
<div align="center"><img src="https://github.com/Aisyahrahmap/Python-for-Data-Analyst-1/assets/166115307/7ed90c80-062b-484e-8632-7d87212330f0"/></div>

### 2. Python For Loop with String
This code uses a for loop to iterate over a string and print each character on a new line. The loop assigns each character to the variable i and continues until all characters in the string have been processed.
<div align="center"><img src="https://github.com/Aisyahrahmap/Python-for-Data-Analyst-1/assets/166115307/6abc4703-257f-4e27-9043-cdaac92281b1"/></div>

### 3. Python For Loop with range
The range() function returns a sequence of numbers, starting from 0 by default, and increments by 1 (by default), and ends at a specified number.
<div align="center"><img src="https://github.com/Aisyahrahmap/Python-for-Data-Analyst-1/assets/166115307/a491ef7c-4537-417c-9628-6f1f4173b6ad"/></div>

# Nested For Loop
Nested for loops are a way to iterate over multiple sequences (lists, tuples, strings, etc.) within each other. This means that you have one loop inside another loop. The inner loop will run completely for each iteration of the outer loop.

### How Nested For Loops Work
When you have a nested loop, the inner loop runs to completion for each iteration of the outer loop. This means that for each element in the outer loop, the inner loop will run through all of its iterations. As in the example below, it can also be combined with range() and conditional expressions, etc. To draw a python asterisk (inverted pyramid pattern).
<div align="center"><img src="https://github.com/Aisyahrahmap/Python-for-Data-Analyst-1/assets/166115307/4da0ed9b-ab56-4393-8376-e2ae0ccbe537"/></div>

# Else After For
Else after for is used primarily in search loops to provide a program exit when the search is not found or to execute code when the loop is finished without a break. This means that if the loop runs to completion (without any break being executed), then the code block in else will be executed.
<div align="center"><img src="https://github.com/salsanssp/Python-for-Data-Analyst/assets/166114037/b599754e-164c-4fcf-b870-5fc82c134bbf" /></div>

<div align="center"><img src="https://github.com/salsanssp/Python-for-Data-Analyst/assets/166114037/f242bb76-64f2-4e9b-a57d-512dc4d8829f" /></div>

# Break and Continue
In every example you've encountered thus far, the complete body of the while loop is executed during each iteration. Python offers two keywords that prematurely end a loop iteration:  
  - The Python break statement instantly terminates the entire loop. Program execution moves on to the first statement following the loop body.
   <div align="center"><img src="https://github.com/Aisyahrahmap/Python-for-Data-Analyst-1/assets/166115307/f04ca148-870d-4c4c-8880-b95c02eec50f"/></div>

  - The Python continue statement promptly terminates the ongoing loop iteration. Execution leaps to the loop's top, and the controlling expression is re-evaluated to decide whether the loop will continue executing or terminate.
    <div align="center"><img src="https://github.com/Aisyahrahmap/Python-for-Data-Analyst-1/assets/166115307/490b7d97-587d-402c-8ef5-14976aafa3bd"/></div>

## While
In Python, while is used as a loop structure that will execute a block of code as long as a certain condition is met or True. 
<div align="center"><img src = https://github.com/difasafrina/Pyhton-Fundamentals-for-Data-Analyst/assets/113273578/7d19b3db-90e2-4bb8-a5cf-49efa72a3281" /></div>

**While with else** This is a unique feature of Python, not found in most other programming languages.
<div align="center"><img src = https://github.com/difasafrina/Pyhton-Fundamentals-for-Data-Analyst/assets/113273578/42029049-11e1-4297-88cc-b0eb8c9ebb04" /></div>

## List Comprehension
It lets you create a new list by applying an expression to every element in an already-existing iterable (such a list, tuple, or range) and, if necessary, filtering the elements according to specific criteria.
  -  Condition :
     The condition is like a filter that only accepts the items that valuate to True
<div align="center"><img src = https://github.com/difasafrina/Pyhton-Fundamentals-for-Data-Analyst/assets/113273578/f4f560e1-f811-481c-899d-8a11848762c6" /></div>

  -  Interable :
     The iterable can be any iterable object, like a list, tuple, set etc.
<div align="center"><img src = https://github.com/difasafrina/Pyhton-Fundamentals-for-Data-Analyst/assets/113273578/2360534c-6b92-4dc1-bc99-e46ff0524bb3" /></div>

  - Expression :
    The expression is the current item in the iteration, but it is also the outcome, which you can manipulate before it ends up like a list item in the new list.
<div align="center"><img src = https://github.com/difasafrina/Pyhton-Fundamentals-for-Data-Analyst/assets/113273578/bbe54a63-1ac9-43a1-b3e3-8e3d5bd326a5" /></div>

## Python Journey🐍
Once Python has analyzed the data, findings can then be used to make good business decisions, improve procedures, and even make informed predictions based on what has been discovered.


