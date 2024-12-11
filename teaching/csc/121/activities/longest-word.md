---
layout: activity
title: Longest Word
---

## 🔖 Background Information

N/A

## 🎯 Problem Statement

Write a function that takes in a sentence (`string`) as an argument and returns the number of characters in the longest word. For example, if you gave your function the string: "The quick brown fox jumped over the lazy dog", the function should return the number 6 because "jumped" is the longest word in the sentence and it has six characters.

## ✅ Acceptance Criteria

* A string with no characters has a longest word length of zero.
* There might be a situation where two words have the same number of characters. This is fine - just return the maximum from either one of them, like usual.
* You can assume that the sentences will not contain any punctuation, numbers, or special characters. They will only contain A - Z and a - z.

## 📋 Dev Notes

* You do not need to handle erroneous input from the user. You can assume that a user of the function will always provide a sentence with valid words.

## 🖥️ Example Output

A sample C++ program that uses the function might look something like this:

```cpp
cout << longest_word("") << endl; // This should return 0
cout << longest_word("a") << endl; // This should return 1
cout << longest_word("a b") << endl; // This should return 1
cout << longest_word("a bb") << endl; // This should return 2
cout << longest_word("My name is Bob") << endl; // This should return 4
```

## 📘 Works Cited

N/A
