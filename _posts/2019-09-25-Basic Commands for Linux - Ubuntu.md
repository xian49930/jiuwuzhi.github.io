---
layout:     post
title:      "Basic Commands for Linux/Ubuntu"
subtitle:   "\"Cheat Sheet\""
date:       2019-09-12
author:     XL
header-img: 
catalog: 	 true
tags:
    - Linux
    - Ubuntu
    - Cheat Sheet
---

# Common Commands for Linux System (Ubuntu)

These days, I use Ubuntu a lot. Three Raspberry Pi 3 have installed Ubuntu Mate, and one Linux computer in the lab runs on Ubuntu 18.04. I need to use the basic commands often, but I cannot remember them very well. 

In stead of finding these basic commands on Google all the time, I plan to organize and write them down, and to make the checking much easier for myself. I believe that there are some other people like me have the same problem. If you are one of us, feel free to borrow it. Refer to this article if you are nice, that I believe you are.

This list will start from the basic common operation (i.e. copy, cut, paste, delete, ..., create file/directory) to other useful operations like become the specific user.

## File Commands

**ls** - directory listing

**ls -al** - formatted listing with hidden files

**cd** ***dir*** - change directory to *dir*

**cd** - change to home

**pwd** - show present working directory

**mkdir** ***dir*** - create a directory *dir*

**rm** ***file*** - delete *file*

**rm -r** ***dir*** - delete directory *dir*

**rm -f** ***file*** - force remove *file*

**rm -rf** ***dir*** - force remove directory *dir*

**cp** ***old_file new_file*** - copy *old_file* to *new_file*

**cp -r** ***old_file new_file*** - copy *old_file* to *new_file*; create *new_dir* if it doesn't exist

**mv** ***old_file new_file*** - rename or move *old_file* to *new_file*; if *new_file* is an existing directory, moves *old_file* into directory *new_file*

## System Info

**date** - show the current date and time

**cal** - show this month's calendar

**uptime** - show current uptime

**w** - display who is online

**whoami** - who you are logged in as

**su -** ***username_1*** - switch to the *username_1* account, be placed into the home directory for *username_1*

### To-be-continued...

