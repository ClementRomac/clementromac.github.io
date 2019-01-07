---
title: "Minecraft Reinforcement Learning"
excerpt: "Applying Deep Recurrent Q-Learning to a Minecraft environment."
collection: projects
date: 2018-09-10
---

Vincent Beraud, Pierre Leroy and I made a research work on applying Deep Reinforcement and more specially Deep Recurrent Q-Learning to a Minecraft environment.

We used [gym-minecraft](https://github.com/tambetm/gym-minecraft) to access the [Malmo project](https://github.com/Microsoft/malmo) with an [OpenAI Gym](https://gym.openai.com/) like API. We also used Tensorflow.

Minecraft can be viewed as a Partially Observable Markov Decision Process (POMDP), we thus used a Convolutional Neural Network with LSTM cells. We also used Deep Q-Learning techniques such as experience replay buffer, Double Q-Learning and ε-greedy exploration.

Our work was inspired by [the work of Arthur Juliani](https://github.com/awjuliani/DeepRL-Agents).

You can find all our work on [our repository](https://github.com/vincentberaud/Minecraft-Reinforcement-Learning).

You can also find the talk we made about this project [here](http://localhost:4000/talks/2018-06-08-minecraft-drqn).