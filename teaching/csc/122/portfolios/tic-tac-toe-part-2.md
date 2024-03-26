---
layout: page
title: Tic-Tac-Toe (Part 2)
---

## 🔖 Background Information

Tic-tac-toe is a game for two players who take turns marking the spaces in a three-by-three grid with an "X" or "O". The player who puts three of their marks in a horizontal, vertical, or diagonal row is the winner. You can see a full writeup of the rules and a bit of game theory behind tic-tac-toe on its wiki page {% cite Tictactoe2024 %}.

## 🎯 Problem Statement

Expand on the human-vs-human game of tic-tac-toe from portfolio one with a few new features:

* A random computer player that always makes random moves on the tic-tac-toe board, regardless of the state of the game
* A main menu to choose between one of two options - do you want to play against a human or computer player?
* An exit menu asking the player if they want to play the same game again after the current game ends

## ✅ Acceptance Criteria

This submission must be built on top of the code from portfolio one. You cannot start over from scratch!

### Random Computer Player

If a player chooses to play against the computer, a random computer player will be selected as player two. This computer player will make random moves, regardless of the current state of the game. The console output may or may not need to be adjusted to fit this new random computer player.

### Main Menu

When a player starts the tic-tac-toe program, they should see a main menu that welcomes them to play a game of tic-tac-toe. They should be able to select one of two options: (1) a human vs. human game or (2) a human vs. computer game where they are always player one. If the user selects an invalid option, the menu should alert them to their mistake and prompt them again.

### Exit Menu

The exit menu should appear after a player finishes a game of tic-tac-toe. It should ask the user if they want to play the exact same game again (i.e. the player cannot change their selection of human vs. human or human vs. computer). If the player declines, the program should print a confirmation message and exit gracefully. If the user selects an invalid option, the menu should alert them to their mistake and prompt them again.

## 📋 Dev Notes

* We spent a lot of time going through tic-tac-toe in class and spiking out some basic design of the game. You are welcome to use any and all of the code that we developed together in class. However, the code must be tidied up for the final submission - e.g. put different classes in different files, have different files for testing, have a dedicated main file for starting the game.
* You do not have to use any of the code that we developed in class if you wish not to. You are free to implement this program as you desire, as long as you fulfill the acceptance criteria and implement the code in C++.
* Keep the idea of an MVP (minimal viable product) in mind as you write your code. If you have to ask "should I include this feature?", the answer is probably "no" unless specifically outlined in the Acceptance Criteria.
* The goal of the tic-tac-toe project is to build on previous submissions. For portfolio 3, you will build on this same submission to implement more features. You CANNOT rewrite tic-tac-toe from scratch in future submissions.

## 🖥️ Example Output

```bash
./tictactoe.out

Welcome to Tic-Tac-Toe!

Plase choose a game mode:

(1) Human vs. human
(2) Human vs. computer

3

That is not a valid choice!

Plase choose a game mode:

(1) Human vs. human
(2) Human vs. computer

2

Let's begin!

 1 | 2 | 3
-----------
 4 | 5 | 6
-----------
 7 | 8 | 9

Player one - where would you like to move? 2

 1 | X | 3
-----------
 O | 5 | 6
-----------
 7 | 8 | 9

The computer player moved in space 4.
Player one - where would you like to move? 3

 1 | X | X
-----------
 O | 5 | 6
-----------
 7 | 8 | O

The computer player moved in space 9.
Player one - where would you like to move? 1

 X | X | X
-----------
 O | 5 | 6
-----------
 7 | 8 | O

Player one wins!

Would you like to play again?

(1) Yes
(2) No

3

That is not a valid choice!

Would you like to play again?

(1) Yes
(2) No

2

Goodbye!
```

## 📘 Works Cited

{% bibliography --cited %}
