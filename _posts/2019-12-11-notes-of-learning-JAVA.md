---
layout:     post
title:      "Notes of Learning JAVA"
subtitle:   "\"Notes\""
date:       2019-12-11
author:     XL
header-img: 
catalog: 	 true
tags:
    - JAVA
    - Computer Science
    - Programming Language
---
# Notes of Learning Java

This document is mainly used to summarize all the notes for me leaning java. 



## Terms and Common Tools

**Grade** is a *build tool* that used to build projects.

- To build a project means transforming the code into something that can be executed.

**API** is the collections of components used for building applets.

**JavaFX** is used to create graphical user interfaces for any platform.

**AWT** is Abstract Window Toolkit.

The version name of Java 8 matches the following pattern: 

- $MAJOR.$MINOR.$SECURITY

After Java SE 10, the version numbers follow a $YEAR.$MONTH format. A new version of Java is released every six months.

The core of the Java ecosystem is the **class**. A **class** groups **fields** and **methods**. 

All Object types are described in files with the ***.java** extension. Object types are organized in **packages**. 

A **package** is a hierarchy of directories, with the Java object types on the last level.

A **package** is usually named by the following template:

- edu.upenn.cis.precise.continue[*]+

**JARs**: Java Archives

A **library** groups one or more JARs.

Any Java desktop application has a special method named **main** that has to be declared in a top-level class. This method is called by the JRE to run the Java program/application and it's called the **entry point**.

Without the **main** method, a Java project is a collection of classes that are not runnable, cannot be executed, and cannot perform certain functions. It is like the ignition lock cylinder of a car.

**Maven** is a build automation tool used primarily for Java projects, like **Gradle** which is gaining ground.

**Syntax** is the set of programming rules that define how terms should be connected to produce an understanable unit of commincation.

**Compact** import statements:

- import static java.lang.Math.*;

**Modifier**: 

- **Access Modifiers** - controls the access level
  - (classes) public, default
  - (attributes, methods, and constructors) public, private, default, protected
- **Non-Access Modifiers** - do not control access level, but provides other functionality
  - (classes) final, abstract
  - (Attributes, methods) final, static, abstract, transient, synchronized, volatile

**Encapsulation**: 

- **accessors** - getters - getXXX()
- **mutators** - setters - setXXX()

**Polymorphism**:

- **Overriding** - run-time polymorphism
- **Overloading** - compile-time polymorphism

**Abstraction** is an **Objective-Oriented Programming (OOP)** principle that manages complexity.

**Enum** type is a special class type. It cannot be instantiated externally. An enum is by default final.

- Enums are the tools for you to limit the implementation of a class to a fixed number of instances.

What is the difference between an **interface** and an **abstract class**?

- An **interface** is not a class, but it does help create classes.
- An interface is fully abstract.
  - It has no fields, only method definitions (skeletons).
- A **class** can implement an interface, and unless the class is abstract, it is forced to provide concrete implementations for them.
- Each method inside an interface is implicitly *public* and *abstract*.
- The only methods with concrete bodies in an interface are static methods and starting with Java 8, **default** methods.
- Interfaces that declare no method definitions are called **marker** interfaces and have the purpose to mark classes for specific purposes.
- The most renowned/known Java marker interface is **java.io.Serializable**, which makes objects that can be serialized (their state can be saved to a binary file).
- There are two types of interfaces:
  - **Normal interfaces**
  - **Annotations**
- The difference between abstract classes and interfaces, and when one or the other should be used, becomes relevant in the context of **inheritance**.
  - Java supports only single inheritance. 
  - A class can only have one superclass.
  - Using interfaces **multiple inheritance** is possible in Java, and that classes extend classes and implement interfaces.

![](https://ws2.sinaimg.cn/large/006tNbRwly1g9tntv7ezoj30uk0oc79o.jpg)

## Shortcuts

### 1. Intellij IDE

**Double Shift** -> Quick Search (*Classes/Files/Symbols/Actions*) 

**Command** + Click any object type -> Open the code of the object class