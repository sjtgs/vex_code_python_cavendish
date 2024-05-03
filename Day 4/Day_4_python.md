<!-- Content Developed by Joshua Chipile  -->

# Python Day 4

##### Modules

- A module is a file containing Python code. It can define functions, classes, and variables.

```python
# mymodule.py

def greet(name):
 print("Hi, " + name)
```

```python
# main.py

import mymodule
mymodule.greet("Joshua")
```

```python
# mymod.py

def add(a, b):
 result = a + b
 print(result)
```

```python
# main2.py

import mymod

mymod.add(4,10)
```

##### Packages

```
mypackage/
├── __init__.py
├── module1.py
└── module2.py
```

```
 __init__.py
```

- This file can be empty or contain initialization code for the package

```python
# module1.py

def func1():
 print("Function 1")
```

```python
# module2.py

def func2():
 print("Function 2")
```

```python
#  main.py

import mypackage.module1
import mypackage.module2

mypackage.module1.func1()
mypackage.module2.func2()
```

<!-- Content Developed by Joshua Chipile  -->