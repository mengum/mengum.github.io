---
title: "Design and Implementation of a Robot Pathfinding Method Based on Reinforcement Learning"
collection: publications
category: conferences
permalink: /publication/2021-07-01-paper-1
excerpt: 'This study proposes a faster-converging Q(λ)-learning algorithm, optimizing robot pathfinding by balancing exploration and exploitation in complex environments.'
date: 2021-07-01
venue: 'Beijing University of Technology, Bachelor's Thesis'
paperurl: 'http://academicpages.github.io/files/paper3.pdf'
citation: 'Meng Meng. (2021). &quot;Design and Implementation of a Robot Pathfinding Method Based on Reinforcement Learning.&quot; <i>Beijing University of Technology, Bachelor's Thesis</i>.'


---

The robot pathfinding method based on Reinforcement Learning (RL) provides the robot with reward signals to perceive the unknown environment through continuous trial and error and eventually learns and selects the optimal behavioral policy to reach the target path. However, reinforcement learning has a balance issue between Exploration and Exploitation. In order to address this issue, this paper proposes a Q(λ)-learning algorithm with a faster convergence speed for robots to find the optimal path autonomously.


The research work and innovations of this paper are summarized as follows:


· The classical Q-learning algorithm was optimized by incorporating the Eligibility Traces learning method, developing a Q(λ)-learning algorithm that unifies the Monte Carlo method with the Temporal Difference (TD) method, effectively extending robot path planning in complex environments.

 · An updated policy for the robot's action-value function was implemented, introducing two exploration methods: ε-greedy and Softmax-Boltzmann Distribution. Combined with the optimized Q(λ)-learning algorithm, the probability distribution between exploration and exploitation was improved, along with the effectiveness and stability of the algorithm.

· Multiple comparative experiments on Reinforcement Learning algorithms were conducted based on the ROS 1 system. The results showed that this algorithm reduced the number of episodes and training by approximately 85%, demonstrating high robustness in finding the optimal path for autonomous robots in various complex environments.


基于强化学习（Reinforcement Learning, RL）的机器人寻路方法，通过向机器人提供奖励信号，使其在不断试错中感知未知环境，最终学习并选择最优的行为策略以抵达目标路径。然而，强化学习在“探索”（Exploration）和“利用”（Exploitation）之间存在平衡问题。为了解决这一问题，本文提出了一种收敛速度更快的Q(λ)-learning算法，用于机器人自主寻找最优路径。


本文的研究工作和创新点总结如下：


· 优化了经典的Q-learning算法，结合资格迹（Eligibility Traces）学习方法，开发了统一蒙特卡洛（Monte Carlo）方法与时序差分法（Temporal Difference, TD）的Q(λ)-learning算法，实现了复杂环境下机器人路径规划的有效扩展；

· 实现了机器人动作价值函数的更新策略，提出了ε-greedy和Softmax-Boltzmann分布（Softmax-Boltzmann Distribution）两种探索方法，并结合优化后的Q(λ)-learning算法，提升了探索与利用的概率分配，以及算法的有效性和稳定性；

· 基于ROS 1系统进行了多次强化学习算法对比实验，结果表明，该算法减少了约85%的迭代和训练次数，验证了自主机器人在多种复杂环境下寻找最优路径算法的高鲁棒性。