---
layout: activity
title: Point of Sale
---

## 🔖 Background Information

There is no background information for this activity.

## 🎯 Problem Statement

A grocery store in your area uses five digit codes to store information about each item for sale. For example, the code "10342" might represent a "Granny Smith Apple" that is priced at 50 cents. At the checkout line, a teller will enter the code of each item that a person wants to buy into the point of sale program. Then, the system can display the total price of the items.

## ✅ Acceptance Criteria

Write a class that allows a user to do the following:

1. Enter a code corresponding to an item in the store (see the list below).
2. Print out the total cost of all of the items.

| Name | Code | Price |
|------|------|-------|
| Granny Smith Apple | 10342 | 50 cents |
| Banana | 10557 | 45 cents |
| Peach | 12151 | 75 cents |

## 📋 Dev Notes

In this activity, we will be using a strategy called "ping pong" pair programming. In this setup, two people pair with each other while sharing a computer. Partner A writes an assert statement based on the acceptance criteria outlined above. Then, partner B makes that assert statement pass with the minimal amount of code possible. Afterwards, the partners switch (partner B writes a test and partner A makes it pass). Repeat this process until the password validator function has been implemented.

Think about how you might break this problem down into tiny pieces so that you can solve it effectively!

## 🖥️ Example Output

A user of your class might implement it as follows:

```cpp
PointOfSale pos;

pos.addCode("10342");
pos.addCode("10557");
pos.addCode("10557");

pos.total(); // This will return $1.40
```

## 📘 Works Cited

N/A
