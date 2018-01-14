---
layout: post
title: "Challenge Problems 0: If-Else"
date: 2017-09-29 00:00:00 -0400
due: 2017-10-01 23:59:59
categories: problems
image:
---
# Challenge Problems

Work on these in the [CS50 IDE](cs50.io). If you need help navigating and using the CS50 IDE, check [this nifty how-to guide on all things CS50](https://manual.cs50.net/)!

Create a directory (folder) called `challenge0` using the command `mkdir challenge0` in the terminal. `mkdir` is short for make directory! This is where you will want to store both these problems. To "enter" this directory and run code in it use the command `cd challenge0`. Can you guess what `cd` is short for?

## Problem 0: Calc

In the `challenge0` directory use the command `touch calc.py` to create a python file called `calc.py`. It's essential that the name is exact otherwise your checks and submission won't work later!

Your goal is to create a calculator in Python! Be sure to support addition (using +), subtraction(using -), multiplication(using x), division(using /), and exponents(using ^)! This program should ask the user for a float, followed by an operation, followed by another float, then print the result.

Example Output:
```
First number: 5
Operation: x
Second number: 2.5
12.5
```

### Testing

Be sure to try a few values yourself and then, while currently in the `challenge0` directory, use the following slug: `check50 compsci.one/calc@spencertiberi/checks`

### Submission
1. Be sure the file is saved as **calc.py**
2. While currently in the `challenge0` directory run the following slug: `submit50 compsci.one/calc@spencertiberi/checks`
3. Check it out! Your code is now on [CS50.me](cs50.me)!

## Problem 1: Schedule

Create a program that prompts the user for day of the week and time of day (hours and minutes in military time) and determines if the user is supposed to be in school at BH (assume an 8:00 am to 4:45 pm schedule).

Be sure the program only outputs either `yes` or `no`.

Example Output:
```
What day is it? Friday
What time is it (hours)? 10
What time is it (minutes)? 30
yes
```

### Testing

Be sure to try a few values yourself and then, while currently in the `challenge0` directory, use the following slug: `check50 compsci.one/schedule@spencertiberi/checks`

### Submission
1. Be sure the file is saved as **schedule.py**
2. While currently in the `challenge0` directory run the following slug: `submit50 compsci.one/schedule@spencertiberi/checks`
3. Check it out! Your code is now on [CS50.me](cs50.me)!
