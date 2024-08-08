---
layout: lab
title: A Terribly Weighty Subject
---

## 🔖 Background Information

In the Imperial system of measurements, weight can be measured using ounces and pounds. There are 16 ounces in one pound. Ounce is abbreviated as "oz" and pound is abbreviated as "lb" (singular) or "lbs" (plural).

This problem is available courtesy of {% cite jamesTERRIBLYWeightySubject2017 %}.

## 🎯 Problem Statement

Given a user's input of some number of ounces, convert their input to units of pounds and ounces as well as a decimal number of pounds.

## ✅ Acceptance Criteria

* Create a function called `toPounds` that converts some integer number of ounces to a decimal number of pounds.
  * The output of the function should be a string that gives the result.
  * Use four decimal places when expressing the decimal number of pounds.
  * Be sure to use the correct units of "many lbs" or "one lb".
* Create a second function called `toPoundsAndOunces` that converts some integer number of ounces to an integer number of pounds and an integer number of ounces.
  * The output of the function should be a string that gives the result.
  * Be sure to use the correct units of "many lbs" or "one lb".

## 📋 Dev Notes

N/A

## 🖥️ Example Output

Suppose we house our methods in a class called `Converter`. Some code that implements the converter might look like:

```java
Converter converter = new Converter();

converter.toPounds(0); // will return the string "0.0000 lbs"
converter.toPounds(16); // will return the string "1.0000 lb"
converter.toPoundsAndOunces(18); // will return the string "1 lb 2 oz"
converter.toPoundsAndOunces(36); // will return the string "2 lbs 4 oz"
```

## 📝 Thought Provoking Questions

1. Why are the functions `toPounds` and `toPoundsAndOunces` marked with the keyword "public"? What does the keyword "public" do?
2. The `Converter` class does not contain `public static void main() { ... }`, yet the code still compiles and tests still run. What is going on here?
3. What happens if the user accidentally types a decimal number for the ounces argument when using either the `toPounds` or `toPoundsAndOunces` functions?
4. What happens if the user accidentally types a string instead of an integer for the ounces argument when using either the `toPounds` or `toPoundsAndOunces` functions?

## 💼 Add-Ons For the Portfolio

## (One Credit) Overloaded Methods

You can't directly set default arguments in Java. For example, you CANNOT do this (which would be valid in other languages):

```java
public class MyClass {
  public String someFunction(int ounces = 0) { // INVALID!
    // implement the function here
  }
}
```

However, we can get around that problem by overloading the method:

```java
public class MyClass {
  public String someFunction() {
    // implement the function here using a default value of 0
  }
  public String someFunction(int ounces) {
    // implement the function here using the argument "ounces"
  }
}
```

Update the `toPounds` and `toPoundsAndOunces` methods to default to 0 ounces if no argument is passed in. Be sure to add additional test cases that cover this new functionality.

### (Two Credits) Convert the Other Way

Create a function called `toOunces` that takes two arguments - an integer number of pounds and an integer number of ounces. The function should return a string that calculates the total number of ounces from the arguments. Be sure to add additional test cases that cover this new function.

Some code that implements the new method in the converter might look like:

```java
Converter converter = new Converter();

converter.toOunces(0, 12); // will return the string "12 ounces"
converter.toOunces(1, 15); // will return the string "31 ounces"
```

## 📘 Works Cited

{% bibliography --cited %}
