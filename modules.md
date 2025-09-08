# Modules

Contains all the modules available within this framework / package as a list, their syntaxes and the way to import and use them.

## Sorting Algorithms

Import them all:
```py
from sorts import *
```

### bubble_sort

Import:
```py
from sorts import bubble_sort
```

Usage:
```py
array = [4, 2, 8, 3, 10, 12, 6, 8]
sorted_array = bubble_sort(array) # bubble_sort(target_array)
print(sorted_array)
```

### insertion_sort

Import:
```py
from sorts import insertion_sort
```

Usage:
```py
array = [4, 2, 8, 3, 10, 12, 6, 8]
sorted_array = insertion_sort(array) # insertion_sort(target_array)
print(sorted_array)
```

### lisst_sort

**Note:** Lisst sort is a method I came up with, and it uses multiple lists to sort one array. Works well with a large amount of data.

Import:
```py
from sorts import lisst_sort
```

Usage:
```py
array = [4, 2, 8, 3, 10, 12, 6, 8]
sorted_array = lisst_sort(array) # lisst_sort(target_array)
print(sorted_array)
```

## Searching Algorithms

Import them all:
```py
from searches import *
```

### binary_search

**Note:** Binary Search can only function properly on a sorted array. 

Import:
```py
from sorts import lisst_sort
from searches import binary_search
```

Usage:
```py
array = [4, 2, 8, 3, 10, 12, 6, 8]
sorted_array = lisst_sort(array)
sorted_array = binary_search(sorted_array, 6) # binary_search(target_array, value_to_search)
```

### linear_search

Import:
```py
from searches import linear_search
```

Usage:
```py
array = [4, 2, 8, 3, 10, 12, 6, 8]
linear_search(array, 6) # linear_search(target_array, value_to_search)
```

## Stack Algorithms

Import them all:
```py
from stacks import *
```

### stacks

Import:
```py
from stacks import stacks
```

Usage:
```py
array = []
stacks(array, 6, 'push', 6) # stacks(target_array, max_value, function, conditional: data to push)
stacks(array, 6, 'pop')
```

### stacks_OOP

Import:
```py
from stacks import stacks_OOP
```

Usage:
```py
array = stacks_OOP(6) # object array takes class's attributes. stacks_OOP(max_value)
array.push(6) # object.push(value_to_add)
array.pop() # object.pop()
```

## Queue Algorithms

Import them all:
```py
from queues import *
```

### queues

Import:
```py
from queues import queues
```

Usage:
```py
array = []
queues(array, 6, 'enter', 6) # queues(target_array, max_value, function, conditional: data to enter)
queues(array, 6, 'leave')
```

### queues_OOP

Import:
```py
from queues import queues_OOP
```

Usage:
```py
array = queues_OOP(6) # object array takes class's attributes. queues_OOP(max_value)
array.enter(6) # object.enter(value_to_add)
array.leave() # object.leave()
```

## Linked List Algorithms

Import them all:
```py
from linked_lists import *
```

**Note:** While linked lists do have a non-OOP counterpart in the framework, I have decided not to include it because it's an eyesore to look at. I hope you can understand.

### linked_lists_OOP

Import:
```py
from linked_lists import LinkedList
```

Usage:
```py
something.insert(69) # object.insert(value)
something.insert(420)
```
```py
something.delete_byval(420) # object.delete_byval(value) Deletes a node by the data it contains
```
```py
something.delete_byind(0) # object.delete_byind(index) Deletes a node by it's index
```
```py
something.display() # object.display() Prints the array to the terminal
```