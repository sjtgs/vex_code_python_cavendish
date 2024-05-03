<!-- Content Developed by Joshua Chipile  -->

# Python Day 3

###### Lambda function

```python
lambda arguments: expression
```

```python
x = lambda a: a + 10
print(x(8))
```

###### Example

```python
add = lambda x, y: x + y

result = add(5, 3)
print(result)  
```

###### Example

```python
def myfunc(b):
  return lambda a : a * b

result = myfunc(2)

print(result(11))
```

## Functional Programming Approach (using Python)

### Functional Programming Approach

#### Define functions for each operation

```python
def add(x, y):
 return x + y

def subtract(x, y):
 return x - y

def multiply(x, y):
 return x * y

def divide(x, y):
 return x / y
```

##### Usage

```python
result_add = add(5, 3)
print("Addition:", result_add)  
# Output: Addition: 8
```

```python
result_subtract = subtract(5, 3)
print("Subtraction:", result_subtract)  
# Output: Subtraction: 2
```

```python
result_multiply = multiply(5, 3)
print("Multiplication:", result_multiply)  

# Output: Multiplication: 15
```

```python
result_divide = divide(5, 3)
print("Division:", result_divide)  
# Output: Division: 1.6666666666666667
```

##### Object-Oriented Programming Approach (using Python)

- Object-Oriented Programming Approach
- Define a Calculator class

```python
class Calculator:
 def add(self, x, y):
     return x + y

 def subtract(self, x, y):
     return x - y

 def multiply(self, x, y):
     return x * y

 def divide(self, x, y):
     return x / y
```

###### Usage

```python
calc = Calculator()

result_add = calc.add(5, 3)
print("Addition:", result_add)  
# Output: Addition: 8
```

```python
result_subtract = calc.subtract(5, 3)
print("Subtraction:", result_subtract)  

# Output: Subtraction: 2
```

```python
result_multiply = calc.multiply(5, 3)
print("Multiplication:", result_multiply)

# Output: Multiplication: 15
```

```python
result_divide = calc.divide(5, 3)
print("Division:", result_divide)  

# Output: Division: 1.6666666666666667
```

<!-- Content Developed by Joshua Chipile  -->