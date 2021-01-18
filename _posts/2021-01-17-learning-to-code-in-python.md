---
title: Learning to code in Python.
typeog: article
url: https.//yohago.tech/posts/learning-to-code-in-python
timeiso: 2021-01-17
ogsection: Tutorial
ogtag: Python
author: SciDroid
date: 2021-01-17 00:00 -0500
categories: [Tutorial, Python]
tags: [Python, Code]
toc: true
comments: true
img: https://test.yohago.tech/assets/img/sample/sample/
description: Learn to program in Python, a high-level, interpreted, multi-paradigm language used for Web with Flask and Django, Artificial Intelligence and Data Science.
---

## About Python

![Python Logo](https://test.yohago.tech/assets/img/sample/python.svg){: width="240" .left}
Python is a widely-used, interpreted, object-oriented, and high-level programming language with dynamic semantics, used for general-purpose programming. It was created by Guido van Rossum, and first released on February 20, 1991.


### Why Python?

* it’s easy to learn – the time needed to learn Python is shorter than for many other languages; this means that it’s possible to start the actual programming faster.

* it’s easy to teach – the teaching workload is smaller than that needed by other languages; this means that the teacher can put more emphasis on general (language-independent) programming techniques, not wasting energy on exotic tricks, strange exceptions and incomprehensible rules.

* it’s easy to use for writing new software – it’s often possible to write code faster when using Python.
  
* it’s easy to understand – it’s also often easier to understand someone else’s code faster if it is written in Python.
  
* it’s easy to obtain, install and deploy – Python is free, open and multiplatform; not all languages can boast that.

### What is Python used for?

* Web and Internet development (e.g., Django and Pyramid frameworks, Flask and Bottle micro-frameworks).
  
* Scientific and numeric computing (e.g., SciPy – a collection of packages for the purposes of mathematics, science, and engineering; Ipython – an interactive shell that features editing and recording of work sessions).
  
* Education (it’s a brilliant language for teaching programming!).

* Desktop GUIs (e.g., wxWidgets, Kivy, Qt).

* Software Development (build control, management, and testing – Scons, Buildbot, Apache Gump, Roundup, Trac)

* Business applications (ERP and e-commerce systems – Odoo, Tryton)
  
* Games (e.g., Battlefield series, Sid Meier\’s Civilization IV…)
  
* Websites and services (e.g., Dropbox, UBER, Pinterest, BuzzFeed…)

**Text By [Python Institute](https://pythoninstitute.org/what-is-python/).**

## The Basics

To start programming we have to start with the basics, we will install Python, a code editor and learn the most basic things of Python.

### Installing Python

The first thing we must do is go to the Python website at <https://python.org>

Click on the download section and download the version compatible with your computer.

![Python Downloads Section](https://test.yohago.tech/assets/img/sample/downloadpython.png) __Download Section__

When you have downloaded it, just execute the file, BEFORE INSTALLING MAKE SURE THAT THE OPTION THAT SAYS *ADD TO PATH* IS ACTIVATED.

Then just press continue until it is installed.

### Installing a code editor

After installing Python search for Sublime Text in Google and select the option to download.

When you are in the download menu you only have to select the option compatible with your operating system, when it has been downloaded you install it. 

![Download Sublime](https://test.yohago.tech/assets/img/sample/downloadsublime.png) __Sublime's Download Menu__

### REPL

The REPL is a console interface where you can enter instructions written in Python, In this case I am only going to show you the REPL to begin but we are not going to use it more after this. 

The first thing we must do is open our terminal.

In Windows we only have to press Win+R and a pop-up menu will appear, just type cmd and press enter.

To open it in MacOS, you can open the Applications folder, then Utilities and double-click on Terminal.

And in Ubuntu press Alt+F2 and type "gnome-terminal" and then enter.

If your operating system is not here, look on the Internet to find out how to open it.

When you have the terminal open just type `python` in Windows, OR in MacOS or Linux `python3`.

If you get an error on MacOS or Linux try just typing `python`.

If you get an error in any operating system try to reinstall Python.

```console
C:\Users\SciDroid>python
Python 3.9.0 (tags/v3.9.0:9cf6752, Oct  5 2020, 15:34:40) [MSC v.1927 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license" for more information.
>>>
```

Here you only have to write this and something magical will happen.

```python
print("Hello World")
```
And if you did it correctly in the terminal you should get the text *Hello World*.

Congratulations you have already written your first line of code, but this is nothing now let's do the real code.

### Creating a Python executable

Before we start we must activate the file name view.

In Windows you must go to the file explorer in the view section and activate the option called File Name Extension.

![Activate Extensions](https://test.yohago.tech/assets/img/sample/Extensions.png) __This is the Spanish menu, just look for the option that says File Name Extensions.__

To create our executable we open Sublime Text, press Ctrl+N and then Ctrl+S, here you name the file followed by the extension .py and save the file in a path you remember so you can later enter that path from the terminal.

When you have saved the file, open the terminal and move to the directory with the command cd.

for example if your file is in the directory `C:/Users/user/downloads/index.py` and taking into account that by default Windows leaves us in the user folder to enter the file folder we should write

```console
cd downloads
```
Now we write in our code editor the command that we write in the REPL that is  

```python
print("Hello World")
```

We save the changes with Ctrl+S and in our terminal we write `python file` you must replace the word file by the name of your file and press enter.

And if everything went correctly you should get the text "Hello World" in the terminal.

### Comments

In Python a comment is a text that is not executed and is initialized with the # symbol.

This serves us for example to explain what our code does, I'll show you with an example.

```python
# Program that shows the text "Hello World" in the terminal
print("Hello World")
```
In this case we use the comment to explain the function of a program, but you can write anything inside a comment.

Commenting your code is always a good practice, do it whenever possible, later we will talk about documenting your code.

### Variables

A variable is a space in RAM where you can save data for later use.

This allows us to save very important data for the operation of a program, for example, someone's name, how many lives a character has, etc. 

To define a variable in Python we have the following syntax.

```python
playerLifes = 5
```

As we see in this example we put a name to the variable then a sign = and assign a value.

Now the variables have certain rules, one of them is the names, the variables cannot begin by number and cannot be put as name reserved words of the language.

when naming variables it's very good practice to put a self-descriptive name to them, for example if you want to refer to the number of attempts that a person has you can put numberOfAttempts instead of number.

If you are observant you may have noticed that the variable name is written in such a way that the first word is in lower case but the first letter of next the word is in upper case, this is called Camel Case and it is a good practice to use it when you have more than one word as a variable name.

And now you have a superpower you can save values in variables and with the `print()` function pass it through the screen, let's try.

We are going to define a variable and then print it for this we must use `print(variable)` changing variable by the name of the variable that we assign, then we are going to write it in code.

```python
name = "Jhon"
print(name)
```

and if we run it it will result in the following.

```console
Jhon
```

### Request text

Now what if we want to ask the user for data?

In Python there is a function called `input()` for that.

Let's make an example.

```python
name = input("What is your name?: ")
```

In this code we are asking the user to write their name, and as we see is a variable to which we say that its value is what the user enters.

### Exercise

Ok now we are going to make an exercise to put in practice all that we learned, it is quite simple, what you must do is ask a user his age and then you must pass it through the screen, but the code must have comments that explain what each thing does. 

**ATTENTION: DO NOT GO TO THE RESULT IF YOU HAVE NOT DONE THE EXERCISE, THE ONLY WAY TO LEARN IS TO PRACTICE.**

If you want to see how to solve it, [click here](https://test.yohago.tech/posts/learning-to-code-in-python/#exercise-one).

## Data Types

### Strings

### Integers

### Floats

### Booleans

## Arrays

### Lists

#### Methods of the lists

### Tuples

#### Methods of the tuples

### Dictionaries

#### Methods of the dictionaries

### Range

## Exercise

## Flow Control

### if

### elif

### else

## Loops

### While

### For

## Try and Except

### try

### except

## Functions

### functions

### modules and libraries

### PIP

## Object-oriented programming

### Objects 

### attributes

### metods

### Classes

### Intances

## Document your code

## Exercises

### Calculator

### Pokemons

### ID Management 

## Bonus: Making a bot in python

## Answers to the exercises

**WARNING: IF YOU HAVEN'T DONE THE EXERCISES GO BACK UPSTAIRS AND DO THEM, IF YOU DON'T DO THEM THIS TUTORIAL WILL BE USELESS.**

### Exercise One 

```python
# this code asks for the user's age and then displays it on the screen.

# We ask for the age and store it in a variable.
age = input("Enter your age: ")
# We pass on the screen the value of the variable age.
print(age)
```