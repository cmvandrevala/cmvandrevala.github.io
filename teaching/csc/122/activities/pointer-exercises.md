---
layout: activity
title: Pointer Exercises
---

## 🔖 Background Information

A pointer is a variable that stores a memory address. We use pointers in a myriad of ways when working in C++. Thus, it is a good idea to get familiar with some basic operations on pointers.

## 🎯 Problem Statement

Complete the following exercises:

### Pointer Basics

Write a program that asks the user to enter two integers to be stored in the variables `a` and `b`. Assign the addresses of `a` and `b` to `ptr_a` and `ptr_b`. Then, print out the dereferenced values of `ptr_a` and `ptr_b` to the console.

### Maximum in an Array

Write a program to find the maximum number in an unsorted list of integers.

Create an integer array (`int[]`) that contains some number of random, unsorted values. You might make the values up yourself or use `rand()`. Then, create a pointer called `max_ptr` that finds and points to the maximum value in the list.

Hint: since this is an unsorted list of integers, you might need to make use of linear search to help you find the maximum.

### Midpoint in a Vector

Write a program to determine the midpoint value of a vector. You can assume that the vector always has an odd number of stored items for the time being so that the midpoint is well-defined.

Create a vector of integers (`vector<int>`) that contains some odd number of random, unsorted values. You might make the values up yourself or use `rand()`. Then, create two pointers - one that points to the beginning of the vector and the other that points to the end. Move the vectors towards each other, step by step, until they meet at the midpoint. Then, return the value of the index where they meet.

## ✅ Acceptance Criteria

* You should write a short solution for each of the questions listed in the Problem Statement.
* Use pointer arithmetic as much as possible (e.g. avoid using array index notation if you could instead use pointers).

## 📋 Dev Notes

N/A

## 🖥️ Example Output

N/A

## 📘 Works Cited

N/A
