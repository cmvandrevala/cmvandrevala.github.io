---
layout: course
title: Lab Grading Rubric
course_number: CSC 121
semester: Spring 2025
---

## Background

The rubric for how I grade labs is presented below. Each lab is worth 10 points, with the grade broken down into four categories. Most labs follow this structure very nicely, but there will be occasional labs that do not (e.g. the [Hello World!]({{ "/teaching/csc/shared/labs/hello-world.html" | absolute_url }}) lab). For those, I will adjust the rubric on a case-by-case basis.

| Grading Item | Points |
| ---- | ---- | ---- |
| Passes All Acceptance Criteria | 5 |
| Follows Assignment-Specific Requirements | 2 |
| Well Tested | 2 |
| Clean and Organized | 1 |

## Passes All Acceptance Criteria

When I grade the lab assignments, I test your code via a combination of automated tests, manual checks, and code review.

| Earned | Description |
|--------|-------------|
| 0 | The code does not compile or run. Furthermore, I cannot get the code to run no matter how I try to adjust imports and `include` statements. |
| 1 | The code compiles and runs, but it does not pass any of my checks. In other words, it does not fulfill any of the Acceptance Criteria in the assignment. The code might also use non-standard libraries that do not work on different systems. |
| 2 | The code compiles and runs, but it has substantial problems. It does not pass the majority of the automated tests, manual checks, and code review. |
| 3 | The code compiles, runs, and passes half of the automated tests, manual checks, and code review. |
| 4 | The code compiles, runs, and passes most of the automated tests, manual checks, and code review. |
| 5 | The code compiles, runs, and passes all of the automated tests, manual checks, and code review. |

## Follows Assignment-Specific Requirements

Most assignments have additional requirements included within them. For example, I might specify that students perform a code-review on their classmate's work, pair program on a given problem, use a particular C++ library, or avoid the use of certain functions.

| Earned | Description |
|--------|-------------|
| 0 | The code does not follow the assignment-specific requirements. |
| 1 | The code follows some, but not all, of the assignment-specific requirements. |
| 2 | The code follows all of the assignment-specific requirements. |

## Well Tested

You are expected to thoroughly test your code for each assignment. There are a variety of strategies we might use, including `assert` statements, driver programs, and testing frameworks.

| Earned | Description |
|--------|-------------|
| 0 | The code is not tested, the program does not compile, or the tests do not run. |
| 1 | The code has a test suite or driver function, but there are gaps in the testing logic. |
| 2 | The code has a test suite that covers many of the edge cases as well as the "happy path". |

## Clean and Organized

There are many things that I look for when assessing clean and organized code. For example:

* Is the code well-written, well-organized and easy to follow?
* Are different functions / classes split up into separate files, where appropriate?
* Is the execution of the problem easy to understand and follow?
* Are comments kept to a minimum and describe why something is implemented in a certain way, rather than how it is implemented?
* And more...

| Earned | Description |
|--------|-------------|
| 0 | The code is difficult or impossible to follow due to the project organization or formatting choices. |
| 1 | The code is well-organized and easy to follow. The code uses canonical C++ formatting guidelines. |
