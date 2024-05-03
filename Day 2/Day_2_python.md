<!-- Content Developed by Joshua Chipile  -->

# Python Day 2

#### Control Statements

##### If statement

```python
if condition:
    # code block to be executed if condition is true
```

###### Example

```python
a  = 10
b = 3

if a > b :
  print (" a great than b")
```

###### if-else Statement

```python
if condition:
    # code block to be executed if condition is true
else:
    # code block to be executed if condition is false
```

###### Example

```python
a = 2
b = 4

if a > b:
 print("a greater than b")
else:
 print("b is greater than a")
```

###### if-elif-else Statement

```python
if condition1:
    # code block to be executed if condition1 is true
elif condition2:
    # code block to be executed if condition1 is false and condition2 is true
else:
    # code block to be executed if both condition1 and condition2 are false
```

###### Example

```python
a = 80
b = 40
if b > a:
  print("b is greater than a")
elif a == b:
  print("a and b are equal")
else:
  print("a is greater than b")
```

#### Loops

- For loop is used for iterating over a sequence

```python
for item in iterable:
    # code block to be executed for each item in the iterable
```

###### Example

- Create a list Called fruits which stores different fruits

```python
fruits = ["oranges", "bananas" , "grape"]

for x in fruits:
  print(x)
```

- While loop executes a set of statements as long as a condition is true.

```python
while condition:
    # code block to be executed as long as condition is true
```

###### Example

```python
a = 1
while a < 6:
  print(a)
  a += 1
```

#### Function

```python
def function_name(parameters):

    # Function body - code block that performs the task
    # You can access parameters inside the function
    # Optionally, perform some operations

    # Optionally, return a value
    return result      
```

###### Example

```python
def myName(lname):
     print("your last name " + lname)

myName("Smith")
```

###### Example

```python
def add_numbers(x, y):
 sum = x + y
 return sum

answer = add_numbers(1,5)
print(answer)
```

<!-- Content Developed by Joshua Chipile  -->
