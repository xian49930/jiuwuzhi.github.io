---
layout:     post
title:      "Notes for 'R Programming'"
subtitle:   "\"Coursera\""
date:       2019-09-10
author:     XL
header-img: 
catalog: 	 true
tags:
    - Coursera
    - R
    - Data Science
    - Online Courses
---
# Notes 

This posts records all my notes for the online course - Python for Data Science and AI - on Coursera.com.

*New notes will be added on the top of the older ones.*


## Week 2

### Logic

- **&**
	- use the `&` operator to evaluate AND across a vector.
- **&&**
	- The `&&` version of AND only evaluates the first member of a vector.

- **|**
	- The `|` version of OR evaluates OR across an entire vector
- **||**
	- the `||` version of OR only evaluates the first member of a vector.

- **isTRUE(argument)**
	- The function isTRUE() takes one argument. If that argument evaluates to TRUE, the function will return TRUE. Otherwise, the function will return FALSE.

- **xor(argument_1, argument_2)**
	- The xor() function stands for exclusive OR. If one argument evaluates to TRUE and one argument evaluates to FALSE, then this function will return TRUE, otherwise it will return FALSE.

- **which(argument)**
	- The which() function takes a logical vector as an argument and returns the indices of the vector that are TRUE.

- **any(argument)**
	- The any() function will return TRUE if one or more of the elements in the logical vector is TRUE. 

- **all(argument)**
	- The all() function will return TRUE if every element in the logical vector is TRUE.

## Week 1

- [**swirl**](https://swirlstats.com/) is a nice place to start. It will teach R programming and data science interactively. Good!

### Basics of R

- getwd()
	- get the current working directory

- setwd(dir)
	- set the current working directory to *dir*

- file.create("mytest.R")
	- create new files

- file.exists("mytest.R")
	- Check to see if "mytest.R" exists in the working directory

- file.info("mytest.R")
	- Access information about the file "mytest.R"

- file.rename("mytest.R", "mytest2.R")
	- Change the name of the file "mytest.R" to "mytest2.R"

- file.copy("mytest2.R", "mytest3.R")
	- Make a copy of "mytest2.R" called "mytest3.R"

- file.path("mytest3.R")
	- Provide the relative path to the file "mytest3.R"

- list.files(), dir()
	- list the files in the current working directory

- ls()
	- list the current objects

- read.csv(filename)
	- read filename.csv

- <-
	- equal to '=' in MATLAB

- data$name
	- extract parts of an object, i.e. return elements after 'name' in 'data'.

- data[complete.cases(data),]
	- return the data frame without NA

- data[!complete.cases(data),]
	- return the full data frame

- max(), min(), mean()
	- get the maximum, minimum, mean values

