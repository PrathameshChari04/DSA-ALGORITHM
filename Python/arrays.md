## Arrays

### Creating Arrays
There are two main ways to create an array-like structure in Python 3:

1. Using Lists:

Lists are the most common way to store collections of elements in Python. They are versatile and can hold elements of different data types. Here's how to create a list:

```python

# Empty list
my_list = []

# List with elements
fruits = ["apple", "banana", "cherry"]

# List with all elements set to the same value (using list comprehension)
numbers = [5] * 3  # Creates [5, 5, 5]

```

2. Using the array module (for more specific data types):

The array module offers arrays that store elements of a single data type for memory efficiency. You'll need to import the module first.

```python
from array import *

# Array of integers
int_array = array('i', [1, 2, 3])

# Array of floating-point numbers
float_array = array('d', [3.14, 2.72])

```
Choosing between Lists and Arrays:

Use lists for general-purpose collections where data type flexibility is important.
Use arrays from the array module when you need a fixed size and efficient storage for elements of the same data type.