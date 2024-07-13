---
layout: activity
title: "ASCII Plot: Part 2"
---

## 🔖 Background Information

N/A

## 🎯 Problem Statement

The goal of this activity is to expand on the code written in [ASCII Plot: Part 1]({{ "/teaching/csc/121/activities/ascii-plot-part-1.html" | absolute_url }}). Now, we are going to handle the situation where we want to plot points along the x and y axes.

## ✅ Acceptance Criteria

* A user should be able to enter the x and y coordinates of a point (each will be an integer greater than or equal to zero).
* The output should include a set of axes as well as the plotted point.

## 📋 Dev Notes

* Your code should support the same business logic as in part one, plus the new addition of plotting points along each axis.
* You can assume that the x and y coordinates will always be integers that are greater than or equal to zero.
* You do not need to write any validation of the inputted coordinates.

## 🖥️ Example Output

Some of the sample outputs are as follows:

```bash
./plot.out

Enter the x-coordinate that you want to plot: 5
Enter the y-coordinate that you want to plot: 2

^
|
|
|
|         X
|
+ - - - - - ->
```

```bash
./plot.out

Enter the x-coordinate that you want to plot: 5
Enter the y-coordinate that you want to plot: 0

^
|
|
|
|
|
+ - - - - X ->
```

```bash
./plot.out

Enter the x-coordinate that you want to plot: 0
Enter the y-coordinate that you want to plot: 3

^
|
|
X
|
|
+ - - - - - ->
```

## 📘 Works Cited

N/A
