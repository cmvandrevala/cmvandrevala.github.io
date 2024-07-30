---
layout: course
title: Lab Grading Rubric
course_number: CSC 122
semester: Fall 2024
---

The rubric for how I grade labs is presented below. Each lab is worth 10 points, with the grade broken down into five categories. Most labs follow this structure very nicely, but there will be occasional labs that do not (e.g. the [Hello World!]({{ "/teaching/csc/labs/hello-world.html" | absolute_url }}) lab). For those, I will adjust the rubric on a case-by-case basis.

| Grading Item | Points | Percent |
| ---- | ---- | ---- |
| Code Passes All Acceptance Criteria (Instructor Specs) | 3 | 30% |
| Code is Well Tested | 3 | 30% |
| Answers to Thought-Provoking Questions | 2 | 20% |
| Assignment-Specific Requirements | 1 | 10% |
| Clean and Organized Code | 1 | 10% |

## Code Passes All Acceptance Criteria (Instructor Specs)

When I grade the lab assignments, I test your code via a combination of automated tests, manual checks, and code review.

| Earned | Description |
|--------|-------------|
| 0 | The code does not compile, run, or pass any of my tests / checks. |
| 1 | The code compiles and runs, but it has substantial problems. It does not pass the majority of the automated tests, manual checks, or code review. |
| 2 | The code compiles, runs, and passes more than half of the automated tests, manual checks, and code review. |
| 3 | The code compiles, runs, and passes all of the automated tests, manual checks, and code review with no issues. |

## Code is Well Tested

You are expected to thoroughly test your code for each assignment. There are a variety of strategies we might use, including `assert` statements, driver programs, and testing frameworks.

| Earned | Description |
|--------|-------------|
| 0 | The code is not tested, the program does not compile, or the tests do not run. |
| 1 | The code has a test suite or driver function, but there are many glaring holes in the tests. Alternatively, the tests are largely manual rather than automated. |
| 2 | The code has an automated test suite that covers most of the cases outlined by the ZOMBIES acronym. |
| 3 | The code has an automated test suite that covers all of the cases outlined by the ZOMBIES acronym. |

## Answers to Thought-Provoking Questions

| Earned | Description |
|--------|-------------|
| 0 | The questions have not been answered on the corresponding discussion board on Blackboard. |
| 1 | Answers are terse, incorrect, or do not have much thought put into them. Alternatively, no responses have been given to other student's answers. |
| 2 | Answers are well thought out and apply directly to the problem at hand. The student has responded to other student's answers with additional thoughts, comments, and questions. |

## Assignment-Specific Requirements

Most assignments have additional requirements included within them. For example, I might specify that students perform a code-review on their classmate's work, pair program on a given problem, use a particular C++ library, or avoid the use of certain functions. Most of the time, this is a binary "you accomplished the task or not" part of the grade. I might give partial credit in this section on a case-by-case basis.

| Earned | Description |
|--------|-------------|
| 0 | Student has not accomplished the assignment-specific requirements as outlined in the problem statement. |
| 1 | Student has accomplished the assignment-specific requirements as outlined in the problem statement. |

## Clean and Organized Code

There are many things that I look for when assessing clean and organized code. For example:

* Is the code well-written, well-organized and easy to follow?
* Are different functions / classes split up into separate files, where appropriate?
* Is the execution of the problem easy to understand and follow?
* Are comments kept to a minimum and describe why something is implemented in a certain way, rather than how it is implemented?
* And more...

| Earned | Description |
|--------|-------------|
| 0 | The code is very difficult or impossible to follow due to the project organization or formatting choices. |
| 1 | The code is well-organized and easy to follow. The student uses canonical C++ formatting guidelines. |
