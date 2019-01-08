---
title: "Deep Q-Learning TicTacToe"
excerpt: "Deep Q-Learning applied to Tic-Tac-Toe."
collection: projects
date: 2017-05-15
---

During my third year at Ingésup, I used Deep Q-Learning to solve a Tic-Tac-Toe game. I wanted to use Reinforcement Learning, a domain I'm very interested in, through a project for the first time. I made this project in collaboration with [Nicolas Luvison](https://www.linkedin.com/in/nicolas-luvison/), another Ingésup student.

We implemented in Python a light version of the Tic-Tac-Toe game and used a FeedForward Neural Network (with Keras) with an experience replay buffer to approximate the Q-Value. We used an ε-greedy strategy to handle the exploration.

We first trained the Agent to play against a player plating randomly and then trained it against itself. The best trained version was able to defend against the majority of strategies and was also able to win with strategies such as diagonals for instance. 

You can find the details and the code on our [GitHub repository](https://github.com/ClementRomac/DeepQLearning-TicTacToe).
