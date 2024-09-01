---
title: "Design and Implementation of the Robot Navigation Method Based on Reinforcement Learning"
collection: publications
category: conferences
permalink: /publication/2024-02-17-paper-title-number-4
excerpt: 'This paper is about fixing template issue #693.'
date: 2021-07-01
venue: 'Beijing University of Technology, Bachelor's Thesis'
paperurl: 'http://academicpages.github.io/files/paper3.pdf'
citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

The robot pathfinding method based on Reinforcement Learning (RL) provides the robot with reward signals to perceive the unknown environment through continuous trial and error and eventually learns and selects the optimal behavioral policy to reach the target path. However, reinforcement learning has a balance issue between Exploration and Exploitation. In order to address this issue, this paper proposes a Q(λ)-learning algorithm with a faster convergence speed for robots to find the optimal path autonomously.


The research work and innovations of this paper are summarized as follows:


· The classical Q-learning algorithm was optimized by incorporating the Eligibility Traces learning method, developing a Q(λ)-learning algorithm that unifies the Monte Carlo method with the Temporal Difference (TD) method, effectively extending robot path planning in complex environments.

 · An updated policy for the robot's action-value function was implemented, introducing two exploration methods: ε-greedy and Softmax-Boltzmann Distribution. Combined with the optimized Q(λ)-learning algorithm, the probability distribution between exploration and exploitation was improved, along with the effectiveness and stability of the algorithm.

· Multiple comparative experiments on Reinforcement Learning algorithms were conducted based on the ROS 1 system. The results showed that this algorithm reduced the number of episodes and training by approximately 85%, demonstrating high robustness in finding the optimal path for autonomous robots in various complex environments.