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


## Week 1

### Basics of R

- getwd()
	- get the current working directory

- setwd(dir)
	- set the current working directory to *dir*

- list.files()
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

