# Skill-ShowDown-System-Design-Challenge


![bc5710f9-9d97-47a4-9cf7-a6d0e1e1fc03](https://github.com/shivscaler/Lecture2_Asgn2_EditorialRepo/assets/129844674/0f861d5d-e464-4a0b-992d-e5a729b9b2a0)

# TicTacToe

## How to participate?
Join the Scaler Discord #system-design-breakdown Channel. 
When you start the challenge, create a Github Issue on this repository by providing your name, and the date when you start the challenge. Keep sharing your progress on the issue. Once you have made the submission, you can close this Github issue. 

## What is TicTacToe?

TicTacToe is a 2-player game played on a 3 x 3 board. Each player is allotted a symbol (one X and one O). Initially, the board is empty. Alternatively, each player takes a turn and puts their symbol at any empty slot. The first player to get their symbol over a complete row OR a complete column OR a diagonal wins. You can play the game within Google Search by just searching for “tic-tac-toe”!

![TicTacToe Image](https://github.com/shivscaler/Lecture2_Asgn2_EditorialRepo/assets/129844674/1b355805-caca-4c9a-a22f-0ee44d61dc32)


## Problem Statement
Create a Low-Level Design for a common TicTacToe game with the following constraints as shared. 

## Problem Requirements

- Board can be of any NxN size.
- There can be any number of players. Each player will be allotted a symbol.
- The players can be either humans or bots. Each human player will have a name.
- Only one Bot is allowed per game.
- We should allow support to undo any number of moves.
- Try to implement the winner detection algorithm in O(1).

## Expectations

- The code should be working and functionally correct
- Good software design practices should be followed:
  - Code should be modular, readable, extensible
  - Separation of concern should be addressed
  - Project structured well across multiple files/ packages
- Write unit tests.
- No need for GUI.

## Interaction Format

Command Line based interactive application.

## Input/ Outputs

### Game Start

Allows to start the game with a given number of players, board size, and symbols of every player.

![Game Start Image](https://github.com/shivscaler/Lecture2_Asgn2_EditorialRepo/assets/129844674/225c613f-c026-4083-a361-633e172463f6)

**Example:**

![Example Image](https://github.com/shivscaler/Lecture2_Asgn2_EditorialRepo/assets/129844674/50ffecbc-1cc8-4309-a87f-63f5957e29ba)

If a player is a computer, their user id will be C.
