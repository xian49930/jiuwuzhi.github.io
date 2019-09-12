---
layout:     post
title:      "Notes for 'Python for Data Science and AI'"
subtitle:   "\"Coursera\""
date:       2019-09-09
author:     XL
header-img: 
catalog: 	 true
tags:
    - Coursera
    - Python
    - Machine Learning
    - Data Science
    - AI
    - Online Courses
---
# Notes 

This posts records all my notes for the online course - Python for Data Science and AI - on Coursera.com.

*New notes will be added on the top of the older ones.*


## Week 2

- Dataframe
	- you can cast a "dictionary" to a dataframe.
	- dx.ix[num_1, num_2], let you access the specific unit in the dataframe
	- 

- with open(filename,file_mode) as File:
	- using statement "with" will always automatically close the file object, like appying "file.close()".

- old_list.sort()
	- .sort() doesn't return new list, it changes the original list.

- Sorted(old_list)
	- sorted() is a function and returns a new list, it does not change the original list.

## Week 1

- **4 Collection Data Types** in Python:
	- **List** is a collection which is ***ordered*** and ***changeable***. ...
	- **Tuple** is a collection which is ***ordered*** and ***unchangeable***. ...
	- **Set** is a collection which is ***unordered*** and ***unindexed***. ...
	- **Dictionary** is a collection which is ***unordered, changeable and indexed***.

- Sets
	- No duplicates.
	- {element 1, element 2, element 3, ...}
	- Set_1.add('new_element')
	- Set_1.remove('old_element')
	- 'Set_1 & Set_2' outputs the overlay of these two sets.
		- The intersection operation ('&') finds the elements that are in both sets.

- Dictionaries
	- Keys & Values
	- {"key_1":value_1, "key_2":value_2, ...}

- Lists
	- [element 1, element 2, element 3...]
	 - Aliasing
	 	- B = A
	 	- Refer to the same list. B & A changes at the same time
	 	- Use 'Clone' to refer to the different lists.
	 - Clone
	 	- B = A[:]
	 	- Refer to the different lists.

- Tuples
	- Tuples: a finite ordered list of elements. (element 1, element 2, element 3...)
	- Tuples are *immutable*.
	- Nesting

- Math Operation
	- **Operands** and Operators.