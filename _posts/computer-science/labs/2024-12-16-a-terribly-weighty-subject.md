---
title: A Terribly Weighty Subject
date: 2024-12-16 05:30:00 -0600
categories: [Computer Science, Labs]
tags: [c++, java, csc-121, csc-214]
math: true
description: In this lab you write a simple program that can convert weights between ounces and pounds. It will help you get started with some basic mathematical operations.
---

## 🔖 Background Information

In the Imperial system of measurements, weight can be measured using ounces and pounds. There are 16 ounces in one pound. Ounce is abbreviated as "oz" and pound is abbreviated as "lb" (singular) or "lbs" (plural).

This problem is available courtesy of {% cite jamesTERRIBLYWeightySubject2017 %}.

## 🎯 Problem Statement

Given a user's input of some number of ounces, convert their input to units of pounds and ounces as well as a decimal number of pounds.

## ✅ Acceptance Criteria

* When I execute the program, I should see a welcome prompt.
* Then, the program should ask me to enter a value for the number of ounces.
* After I give my input, the program should confirm that it got the input.
* Then, the program should print out the converted weight, both in terms of pounds / ounces and pounds as a decimal.
* Finally, I should see an exit message as the program gracefully exits.
* Right now, you do not have to distinguish between "lb" and "lbs" in your output. You can simply use "lbs" as the unit. There is a portfolio add-on that will address this item.

## 📋 Dev Notes

* You can assume that the user always types in a whole number of ounces. They will never type in a decimal number of ounces. That being said, the final number of pounds might be a decimal number.

## 🖥️ Example Output

```bash
$ ./ounces.out

Welcome to the Ounce Conversion Program!

How many ounces do you have? 62
Thank you! Converting ounces to pounds.

62 oz is equivalent to 3 lbs and 14 oz.
62 oz is equivalent to 3.875 lbs.

Thank you for using the OCP!
```

## 📝 Thought Provoking Questions

1. What variables do you have in this program? What are their data types?
2. Is it possible to get both the decimal number of total pounds and the whole pounds with remaining ounces from the same input value? If so, how?
3. What happens if the user types a decimal number of ounces as their input? You do not need to change your code to account for this behavior.
4. What happens if the user accidentally types a symbol or a letter instead of their ounces amount? You do not need to change your code to account for this behavior.

## 💼 Add-Ons For the Portfolio

### (One Credit) Singular vs Plural Units

Currently, the program will output the word "lbs", whether or not your final units are singular or plural (e.g. "1 lbs"). Add in logic to make it so your program correctly outputs the unit "lb" if the value is singular or "lbs" if the value is plural. The output should not change otherwise.

```bash
$ ./ounces.out

Welcome to the Ounce Conversion Program!

How many ounces do you have? 17
Thank you! Converting ounces to pounds.

17 oz is equivalent to 1 lb and 1 oz.
17 oz is equivalent to 1.0625 lbs.

Thank you for using the OCP!
```

### (Two Credits) Validate User Input

Currently, if a user enters a string or symbol for their input, the program will crash or display a strange result. We want to add some validation to the code so that random user inputs are handled gracefully.

1. If a user enters a alphabetic character or a symbol, the program should tell them that their input is incorrect and prompt them for a number again.
2. If a user enters nothing and presses enter, the program should tell them that they need to enter some input and prompt them for a number again.
3. If a user enters a negative number, the program should tell them that they need to enter a positive number and prompt them for a number again.
4. Once the user enters a valid input, the program should execute like before.

```bash
$ ./ounces.out

Welcome to the Ounce Conversion Program!

How many ounces do you have? Foobar
That is not a number! Please enter the number of ounces.

How many ounces do you have? !!!
That is not a number! Please enter the number of ounces.

How many ounces do you have?
Blank values are not allowed. Please enter the number of ounces.

How many ounces do you have? -100
Your input should be a positive number. Please enter the number of ounces.

How many ounces do you have? 62
Thank you! Converting ounces to pounds.

62 oz is equivalent to 3 lbs and 14 oz.
62 oz is equivalent to 3.875 lbs.

Thank you for using the OCP!
```

### (Three Credits) Additional Thought Provoking Questions

For this add-on, you don't need to write any additional code. Instead, answer the following questions.

1. The CPU often does integer 'division' operations as a "two-for-one" deal. That is to say, whenever we request either an integer quotient or an integer remainder, the CPU calculates both. How might you optimize this program given this information?

2. Suppose two integers, \\( m \\) and \\( n \\), share a common factor \\( p \\). What can you tell me about the results of the following calculations? You can assume \\( q \\) is a positive integer greater than \\( m \\) and greater than \\( n\\).

$$
r_1 = q \: \% \: m \: \% \: p
$$

$$
r_2 = q \: \% \: m \: \% \: n
$$

$$
r_3 = q \: \% \: n \: \% \: p
$$

$$
r_4 = q \: \% \: n \: \% \: m;
$$

$$
r_5 = q \: \% \: p;
$$

## 🔗 Useful Links

* [C++ Project Template](https://github.com/cmvandrevala/a-terribly-weighty-subject-cpp-template)
* [Java Project Template](https://github.com/cmvandrevala/a-terribly-weighty-subject-java-template)

## 📘 Works Cited

{% bibliography --cited %}
