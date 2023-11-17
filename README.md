# Reinforcement Learning Tic-Tac-Toe

This project implements a Tic-Tac-Toe game with a reinforcement learning agent using Q-learning. The agent learns to play by playing against itself and updating its value function based on the outcomes of the games.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [How to Play](#how-to-play)
- [Training the Agent](#training-the-agent)
- [Playing Against the Agent](#playing-against-the-agent)
- [License](#license)

## Introduction

This project consists of a Tic-Tac-Toe game where an agent learns to make optimal moves through reinforcement learning. The agent uses a Q-learning algorithm to update its value function based on the outcomes of games played against itself.

## Features
- Interactive command-line interface for playing Tic-Tac-Toe.
- Q-learning algorithm for the agent to learn optimal strategies.
- Option to play against the trained agent.

## HOW TO PLAY 
- To play the Tic-Tac-Toe game, run the following command:
- python tic_tac_toe.py
- Follow the on-screen instructions to make moves and play the game.

## Training the Agent
- To train the agent by playing against itself, run the following command:
- python tic_tac_toe.py --learn
- The agent will play 10,000 games against itself to learn optimal strategies.

## Playing Against the Agent
- After training the agent, you can play against it by running the following command:
- python tic_tac_toe.py --play
-  When playing Tic-Tac-Toe on this GitHub project, the game board is represented as a 3x3 grid. Each cell in the grid is identified by its row and column indices. 
  Players take turns placing their symbols, 'X' or 'O', in an empty cell of the grid.
  - For instance, if you want to place your symbol in the center of the board, you should enter "1,1." Here, the indices start from 0, so "1,1" corresponds to the 
    second row and second column.
    To make your move, specify the row and column where you'd like to place your symbol in the format "i,j". This input format allows you to interact with the Tic- 
     Tac-Toe game and make strategic moves during your turn.
