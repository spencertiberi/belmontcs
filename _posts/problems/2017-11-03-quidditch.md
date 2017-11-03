---
layout: post
title: "Quidditch"
date: 2017-11-03 00:00:00 -0400
due: 2017-11-06 23:59:59
categories: problems
image:
---

## Problem
You want to calculate the final score for a team that has just participated in an exciting quidditch match. Building on the code below, implement a function that takes two variables as input — an integer indicating the number of times the team got the Quaffle through the other team's hoops, and an integer indicating whether or not they caught the snitch -- and returns that team's final score (what would the return type be?).  

Recall that each 'goal' in quidditch is worth 10 points, and that catching the snitch is worth 150 points.

## Distribution Code
```python
# TODO: create the final_score() function

goal_num = int(input("Number of times your chasers got the quaffle through a hoop: "))
snitch_caught = int(input("Did your team's seeker catch the snitch? Enter 1 if true, 0 otherwise: "))
score = final_score(goal_num, snitch_caught)
print("Your team's final score is: " + score)
```
