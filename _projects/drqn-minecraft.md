---
title: "DRQN vs DQN in Minecraft"
excerpt: "Deep Recurrent Q-Learning vs Deep Q Learning on a simple Partially Observable Markov Decision Process with Minecraft."
collection: projects
date: 2018-09-10
---

[Vincent Beraud](https://www.linkedin.com/in/vincent-beraud/), [Pierre Leroy](https://www.linkedin.com/in/pierreleroyfr/) and I made a research work on applying Deep Reinforcement and more specially Deep Recurrent Q-Learning to a Minecraft environment.

We compared Deep Recurrent Q-Learning and Deep Q-Learning on two simple missions in a Partially Observable Markov Decision Process (POMDP) based on Minecraft environment. We used gym-minecraft which allows the use of the MalmoProject with an OpenAI like API.

We used [gym-minecraft](https://github.com/tambetm/gym-minecraft) to access the [Malmo project](https://github.com/Microsoft/malmo) with an [OpenAI Gym](https://gym.openai.com/) like API. We also used Tensorflow.

Our paper can be found [here]({{ site.url }}/publication/2019-03-11-DQRN_vs_DQN_Minecraft).

You can find all our work on [our repository](https://github.com/vincentberaud/Minecraft-Reinforcement-Learning).

You can also find the talk we made about this project [here]({{ site.url }}/talks/2018-06-08-minecraft-drqn).


### References :
- [Human-level control through deep reinforcement learning](https://storage.googleapis.com/deepmind-media/dqn/DQNNaturePaper.pdf)
- [Deep Recurrent Q-Learning for Partially Observable MDPs - Matthew Hausknecht and Peter Stone](https://arxiv.org/pdf/1507.06527.pdf)
- [Deep Reinforcement Learning with Double Q-learning - Hado van Hasselt and Arthur Guez and David Silver](https://arxiv.org/pdf/1509.06461.pdf)
- [Teacher-Student Curriculum Learning - Tambet Matiisen and Avital Oliver and Taco Cohen and John Schulman](https://arxiv.org/pdf/1707.00183.pdf)
- [Deep Learning for Video Game Playing - Niels Justesen and Philip Bontrager and Julian Togelius and Sebastian Risi](https://arxiv.org/pdf/1708.07902.pdf)