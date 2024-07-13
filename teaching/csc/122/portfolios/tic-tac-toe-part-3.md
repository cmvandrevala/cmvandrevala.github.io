---
layout: lab
title: Tic-Tac-Toe (Part 3)
---

## 🔖 Background Information

Tic-tac-toe is a game for two players who take turns marking the spaces in a three-by-three grid with an "X" or "O". The player who puts three of their marks in a horizontal, vertical, or diagonal row is the winner. You can see a full writeup of the rules and a bit of game theory behind tic-tac-toe on its wiki page {% cite Tictactoe2024 %}.

## 🎯 Problem Statement

Expand on the game of tic-tac-toe from portfolio two; a player should now be able to choose to play tic-tac-toe on a 3 x 3 or a 4 x 4 board. All of the features implemented in the previous iterations of the problem should still work! For example, I should still be able to play against a human or random computer player on either board, and those players should make valid moves. Additionally, if you decided to implement additional features in portfolio two, those must also still work in portfolio three.

## ✅ Acceptance Criteria

This submission must be built on top of the code from portfolio two. You cannot start over from scratch!

### Main Menu

When a player starts the tic-tac-toe program, they should see a main menu that welcomes them to play a game of tic-tac-toe. They should be able to select one of two options: (1) a human vs. human game or (2) a human vs. computer game where they are always player one. If the user selects an invalid option, the menu should alert them to their mistake and prompt them again.

After the initial selection, the player should be able to select one of two options for board type: (1) a 3 x 3 board or (2) a 4 x 4 board. If the user selects an invalid option, the menu should alert them to their mistake and prompt them again.

### The 4 x 4 Board

The game of tic-tac-toe should proceed like normal on a 4 x 4 board, but as we discussed in class, a winning player will get four marks in a row, instead of three.

## 📋 Dev Notes

* We spent a lot of time going through tic-tac-toe in class and spiking out some basic design of the game. You are welcome to use any and all of the code that we developed together in class. However, the code must be tidied up for the final submission - e.g. put different classes in different files, have different files for testing, have a dedicated main file for starting the game.
* You do not have to use any of the code that we developed in class if you wish not to. You are free to implement this program as you desire, as long as you fulfill the acceptance criteria and implement the code in C++.
* Keep the idea of an MVP (minimal viable product) in mind as you write your code. If you have to ask "should I include this feature?", the answer is probably "no" unless specifically outlined in the Acceptance Criteria.

## 🖥️ Example Output

```bash
./tictactoe.out

Welcome to Tic-Tac-Toe!

Plase choose a game mode:

(1) Human vs. human
(2) Human vs. computer

2

Please choose a board:

(1) 3 x 3
(2) 4 x 4

2

Let's begin!

 1  | 2  | 3  | 4
-------------------
 5  | 6  | 7  | 8
-------------------
 9  | 10 | 11 | 12
-------------------
 13 | 14 | 15 | 16

Player one - where would you like to move? 1

 X  | 2  | 3  | 4
-------------------
 5  | 6  | 7  | 8
-------------------
 9  | 10 | 11 | 12
-------------------
 13 | 14 | 15 | 16

The computer player moved in space 5.
Player one - where would you like to move? 2

 X  | X  | 3  | 4
-------------------
 O  | 6  | 7  | 8
-------------------
 9  | 10 | 11 | 12
-------------------
 13 | 14 | 15 | 16

The computer player moved in space 9.
Player one - where would you like to move? 3

 X  | X  | X  | 4
-------------------
 O  | 6  | 7  | 8
-------------------
 O  | 10 | 11 | 12
-------------------
 13 | 14 | 15 | 16

The computer player moved in space 16.
Player one - where would you like to move? 4

 X  | X  | X  | X
-------------------
 O  | 6  | 7  | 8
-------------------
 O  | 10 | 11 | 12
-------------------
 O  | 14 | 15 | 16

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
