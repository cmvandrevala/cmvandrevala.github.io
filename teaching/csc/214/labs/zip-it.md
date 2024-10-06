---
layout: lab
title: Zip It!
---

## 🔖 Background Information

There is no background information needed for this problem.

## 🎯 Problem Statement

Write a Java method called `zip(...)` that takes two lists containing elements of the same type and merges them into a single list. The outputed list should alternate between elements of each list - e.g. an element from the first, then the second, then the first, then the second, etc.

## ✅ Acceptance Criteria

* Your `zip(...)` method must merge two lists containing elements of the same type into one list that alternates between elements of each.
* If one list has more elements than the other, the leftover elements should all be placed at the end of the outputed list, in their original order.
* Write a set of JUnit tests that ensure that your `zip(...)` function works as expected.
* You can optionally create a driver program to manually test your `zip(...)` method, though it is not required.

## 📋 Dev Notes

* The `zip(...)` function must use generics.

## 🖥️ Example Output

Suppose I use the `zip(...)` method in a `main(...)` method as shown below:

```java
public static void main(String[] args) {
  List<Integer> nums1 = List.of(1, 3, 5, 7);
  List<Integer> nums2 = List.of(2, 4, 6, 8);
  List<Integer> mergedNumbers = zip(nums1, nums2);
  System.out.println(mergedNumbers); // [1, 2, 3, 4, 5, 6, 7, 8]

  List<String> colors1 = List.of("Red", "Green", "Blue");
  List<String> colors2 = List.of("White", "Black", "Orange", "Pink");
  List<String> mergedWords = zip(colors1, colors2);
  System.out.println(mergedWords); // [Red, White, Green, Black, Blue, Orange, Pink]
}
```

## 📝 Thought Provoking Questions

1. How would your code change if you decided to use method overloading rather than generics in this problem?
2. Why must the elements of the two lists be of the same type in the `zip(...)` function?

## 💼 Add-Ons For the Portfolio

### (Three Credits) Lists to HashMap

Create a new method called `hashmapify(...)` that takes two arguments. The first argument should be a list of strings and the second should be a list of elements, all having some generic type. The method should create a HashMap where the keys come from the first argument and the values come from the second. If the two list arguments do not have the same size, throw an exception.

```java
public static void main(String[] args) {
  List<String> colors = List.of("White", "Black", "Orange", "Pink");
  List<Integer> nums = List.of(1, 3, 5, 7);

  // This should create {"White" => 1, "Black" => 3, "Orange" => 5, "Pink" => 7}
  HashMap<String, Integer> map = hashmapify(colors, nums);
}
```

## 📘 Works Cited

N/A
