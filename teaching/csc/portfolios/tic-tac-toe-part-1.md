---
layout: page
title: Tic-Tac-Toe (Part 1)
---

## 🔖 Background Information

Tic-tac-toe is a game for two players who take turns marking the spaces in a three-by-three grid with an "X" or "O". The player who puts three of their marks in a horizontal, vertical, or diagonal row is the winner. You can see a full writeup of the rules and a bit of game theory behind tic-tac-toe on its wiki page {% cite Tictactoe2024 %}.

## 🎯 Problem Statement

Implement a human versus human game of tic-tac-toe that can be played on the command line.

## ✅ Acceptance Criteria

* Two human players should be able to start a game of tic-tac-toe and play it on the command line
* The tic-tac-toe board should be displayed in the console (not just an array of numbers / marks)
* The program should accurately implement all of the rules of tic-tac-toe
* The program should warn a user when an input is invalid:
  * Greater than largest cell
  * Less than smallest cell
  * Cell already taken
* The game should end when there is a win, lose, or draw
* The program should print out the winner of the game or a draw message
* The program should exit gracefully after the game ends

## 📋 Dev Notes

* We spent a lot of time going through tic-tac-toe in class and spiking out some basic design of the game. You are welcome to use any and all of the code that we developed together in class. However, the code must be tidied up for the final submission - e.g. put different classes in different files, have different files for testing, have a dedicated main file for starting the game.
* You do not have to use any of the code that we developed in class if you wish not to. You are free to implement this program as you desire, as long as you fulfill the acceptance criteria and implement the code in C++.
* Keep the idea of an MVP (minimal viable product) in mind as you write your code. If you have to ask "should I include this feature?", the answer is probably "no" unless specifically outlined in the Acceptance Criteria.
* The goal of the tic-tac-toe project is to build on previous submissions. For portfolios 2 and 3, you will build on this same submission to implement more features. You CANNOT rewrite tic-tac-toe from scratch in future submissions.

## 🖥️ Example Output

```bash
./tictactoe.out

 1 | 2 | 3
-----------
 4 | 5 | 6
-----------
 7 | 8 | 9

Player one - where would you like to move? 2

 1 | X | 3
-----------
 4 | 5 | 6
-----------
 7 | 8 | 9

Player two - where would you like to move? 4

 1 | X | 3
-----------
 O | 5 | 6
-----------
 7 | 8 | 9

Player one - where would you like to move? 3

 1 | X | X
-----------
 O | 5 | 6
-----------
 7 | 8 | 9

Player two - where would you like to move? 3

That move is invalid!

Player two - where would you like to move? 9

 1 | X | X
-----------
 O | 5 | 6
-----------
 7 | 8 | O

Player one - where would you like to move? 1000

That move is invalid!

Player one - where would you like to move? 1

 X | X | X
-----------
 O | 5 | 6
-----------
 7 | 8 | O

Player one wins!
```

## 📘 Works Cited

{% bibliography --cited %}
