<!-- Content Developed by Joshua Chipile  -->

# Python Day 1

## Define Python Programming

- This is a high level general purpose programming language

## Why choose python programming

- Python is a programming language known for its simplicity, versatility, and readability.
- It is free and open source
- It is easy to read and understand
- It has a vast ecosystem of libraries and frameworks

### Example of where Python programming is being used in the industry

#### Data Science

- In Finance: Analyzing stock market data to identify trends and patterns for making investment decisions.
- In Healthcare: Analyzing patient data to predict disease outbreaks or recommend personalized treatments.
- In Marketing: Analyzing customer behavior and preferences to optimize advertising campaigns and customer targeting.

#### Machine Learning

- In Automotive Industry: Developing self-driving car algorithms to recognize objects and make driving decisions.
- In Retail: Implementing recommendation systems to suggest products to customers based on their purchase history and preferences.
- In Agriculture: Building models to predict crop yield based on environmental factors like weather and soil conditions.

#### Web Development

- In E-commerce: Developing online shopping platforms and payment gateways for seamless transactions.
- In Media and Entertainment: Creating interactive web applications for streaming content and engaging users.
- In Education: Building online learning platforms and educational websites for remote learning and collaboration.

#### Text Editor , Python , Jupyter Notebook

- VSCode  -  <https://code.visualstudio.com/download>
- Install Python  - <https://www.python.org/downloads/>
- Jupyter Notebook - <https://jupyter.org/install>

#### First Code (Print)

- Print Statement

```python
print("Hello World!")
Hello, World!
```

#### Variables

- Used to store data or information. Information such as integers, floats, strings , boolean etc

##### Creating a Variable

- variable is created the moment you first assign a value. The code below shows an example how to create a variable and display the value it has been assigned.

```python
car = "Tesla" 
fruit  =  "Orange"
age = 27 

print(car)
print(fruit)
print(age)
```

- Simple variable syntax errors in Python along with their solutions:

- Missing Quotation Marks:
  
###### Error

```python
   name = John
   print("Hello, " + name)
```

###### Solution

- Enclose the string value within quotation marks.

```python
   name = "John"
   print("Hello, " + name)
```

##### Variable Name Starting with a Number

###### Error

```python
   1st_place = "Gold"
   print("The winner is: " + 1st_place)
```

###### Solution

- Variable names cannot start with a number. Rename the variable.

```python
   first_place = "Gold"
   print("The winner is: " + first_place)
```

- Using Reserved Keywords as Variable Names:

###### Error

```python
   def = 10
   print(def)
```

###### Solution

- Avoid using reserved keywords as variable names.

```python
   def_value = 10
   print(def_value)
```

- Unmatched Quotes:

###### Error

```python
   message = 'This is an incomplete string.
   print(message)
```

###### Solution

- Ensure that quotes are matched properly for strings.

```python
   message = 'This is an incomplete string.'
   print(message)
```

- Indentation Error:

###### Error

```python
   x = 5
   print("The value of x is: " + str(x))
```

###### Solution

- Maintain consistent indentation.

```python
   x = 5
   print("The value of x is: " + str(x))
```

- These are common errors that beginners may encounter while writing Python code, and understanding and fixing them can improve their coding skills.

##### Splitting String

```python
sentence = "Hello, how are you?"
words = sentence.split()
print(words)  

# Output: ['Hello,', 'how', 'are', 'you?']
```

##### Joining String

```python
words = ['Hello,', 'how', 'are', 'you?']
sentence = ' '.join(words)
print(sentence)  

# Output: Hello, how are you?
```

##### List

- Used multiple items in a single variable.  

- List items are ordered, changeable, and allow duplicate values.

```python
carlist = ["bmw" , "tesla", "ford"]
print(carlist)
```

```python
agelist = [ 20 , 24 , 28]
print(agelist)
```

- List with multiple data types

```python
mylist = ["Joshua", 27, True]
print(mylist)
```

##### Dictionary

- Dictionaries are used to store data values in key:value pairs.
The example below shows Car Dictionary.

```python
Cars = {
 "Brand" : "tesla",
 "Model" : "model 3",
 "Year" : 2024,
}

print(Cars)
```

##### Tuple

- Tuples are used to store multiple items in a single variable. Ordered , Unchangeable and Allows duplicates

```python
fruit = ("apples", "bananas" , "grapes",  "peach")
python(fruit)
```

```python
Book = ("Joshua", 12, False)
print(Book)
```

##### Sets

- Sets are used to store multiple items in a single variable.

```python
user_id = { 12 , 14 , 15 , 18}
print(user_id)
```

##### Mixed Sets

###### Error

```python
thisset = {"apple", "banana", "cherry", True, 1, 2}
print(thisset
```

###### Solution

```python
thisset = {"apple", "banana", "cherry", True, 1, 2}
print(thisset)
```

###### Examples of when you might use each data structure in a Python program

1. ###### Sets

   - To store a collection of unique elements.
   - Example: Keeping track of unique user IDs in a social media application.

```python
  unique_user_ids = {101, 102, 103, 104}
  print(unique_user_ids)
```

2. ###### Dictionaries

   - To store key-value pairs for efficient lookup.
   - Example: Storing student names and their corresponding grades.

```python
  student_grades = {'Alice': 85, 'Bob': 90, 'Charlie': 75}
  print(student_grades)
```

3. ###### Tuples

   - When you need an immutable sequence of elements.
   - Example: Storing coordinates of a point.

```python
  point = (3, 4)
  print(point)
```

4. ###### Lists

   - To store an ordered collection of items.
   - Example: Storing a list of tasks to be completed.

```python
tasks = ['Task 1', 'Task 2', 'Task 3', 'Task 4']
print(tasks)
```

- Each data structure has its own characteristics and is suitable for different use cases. Understanding when to use each one can help you write more efficient and readable Python code.

##### Comparison Operators

- Comparison operators are used in Python to compare the values of operands. Here are the comparison operators in Python along with their descriptions:

1. ##### Equal to (`==`)

   - Checks if the values of two operands are equal.
   - Example: `x == y` returns `True` if the value of `x` is equal to the value of `y`.

```python
var = 5==5
print(var)
```

2. ##### Not equal to (`!=`)

   - Checks if the values of two operands are not equal.
   - Example: `x != y` returns `True` if the value of `x` is not equal to the value of `y`.

```python
var = 5!=6
print(var)
```

3. ##### Greater than (`>`)

   - Checks if the value of the left operand is greater than the value of the right operand.
   - Example: `x > y` returns `True` if the value of `x` is greater than the value of `y`.

```python
var = 7 > 6
print(var)
```

4. ##### Less than (`<`)

   - Checks if the value of the left operand is less than the value of the right operand.
   - Example: `x < y` returns `True` if the value of `x` is less than the value of `y`.

```python
var = 4 < 6
print(var)
```

5. ##### Greater than or equal to (`>=`)

   - Checks if the value of the left operand is greater than or equal to the value of the right operand.
   - Example: `x >= y` returns `True` if the value of `x` is greater than or equal to the value of `y`.

```python
var = 10 >= 6
print(var)
```

6. ##### Less than or equal to (`<=`)

   - Checks if the value of the left operand is less than or equal to the value of the right operand.
   - Example: `x <= y` returns `True` if the value of `x` is less than or equal to the value of `y`.

```python
var = 1 <= 3
print(var)
```

- These comparison operators return either `True` or `False` based on the comparison result. They are commonly used in conditional statements and loops to control the flow of a program.

<!-- Content Developed by Joshua Chipile  -->
