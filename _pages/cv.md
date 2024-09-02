---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======

* Sep 2021-Jul 2022 \| University of Malaya, Malaysia \| Master of Engineering Science by Research

* Sep 2019 – Jul 2021 | Beijing University of Technology, China | Undergraduate (2+2 joint education)<br>
  Major: Computer Science and Technology | GPA: 82.39/100.00 | Graduation Project Grade: 90.00/100.00 (Outstanding Graduate)

* Sep 2017- Aug 2019 | Qinghai Nationalities University, China | Bachelor of Engineering (Joint Education with Beijing University of Technology)<br>
  Major: Computer Science and Technology | GPA: 87.97/100.00<br>

<!-- * Ph.D in Version Control Theory, GitHub University, 2018 (expected) -->


Work Experience
======
## Automotive Intelligence and Control of China (Beijing) Technology Co., Ltd.(AICC)
**Senior Motion Planning Algorithm Engineer**  
*July 2023 – Present*

**Project 1: Implementation of L3 Autonomous Driving System for Urban/Highway NOA Based on Self-developed Computing Brain Development System (CBDES)**

- Designed lateral and longitudinal control algorithms based on the ROS 2 system. In longitudinal control, implemented a cascaded PID controller (position-velocity PID and velocity-acceleration PID), reducing the vehicle's longitudinal speed control error to ±0.5 km/h; in lateral control, optimized the LQR control algorithm with vehicle speed-adaptive matrix updates, refined error calculation, and real-time discretization, reducing lateral error to ±0.2 m.

- Developed and optimized the Lattice Planner algorithm. Integrated state machine management for decision processes, multi-constraint checking, collision detection modules, and path smoothing processes, reducing path planning time and improving vehicle safety and path planning performance in complex dynamic environments.

- Developed and implemented vehicle dynamics models and intelligent traffic flow models. Built and integrated simulation platforms such as Carla, VTD, and CarSim, supporting the testing of over 50 scenarios; deployed and debugged PnC algorithms in real vehicles, improving vehicle planning and control accuracy and response speed.

**Project 2: Implementation of L3 Autonomous Driving System for Yutong BRT B7 Line Based on Huawei MDC 610 Domain Control Platform**

- Developed and optimized a multi-agent interactive behavior planning framework based on the POMDP algorithm. Built collision prediction models for surrounding vehicles, designed and updated evaluation functions; implemented the Nudge function for vehicle driving, increasing the success rate of pedestrian avoidance and temporary obstacle avoidance to 90%.

- Developed and optimized motion planning algorithms based on the SSC structure, uniformly modeling constraints in the driving environment; built communication and integration between the SSC structure model and the ROS 2 system, enabling the visualization and transmission of semantic maps, control signals, and planned trajectories.

- Led the construction of a multi-vehicle simulation Docker environment and real-vehicle driving scenarios for the Yutong BRT B7 line, optimizing vehicle docking logic and reducing docking time by 30%; developed global path publishing, lane line parsing and display, as well as obstacle and traffic sign visualization functions.

## Beijing Sihetiandi Technology Co., Ltd.(SHTD) 
**Autonomous Driving R&D Engineer**  
*September 2022 – June 2023*

- Led the development of L4 autonomous driving architecture based on the NVIDIA Orin platform and ROS 1, designing communication methods between the chassis and various sensors.

- Implemented indoor and outdoor real-time mapping and navigation systems using SLAM algorithms such as Cartographer and LIO-SAM, and GNSS-based positioning.

- Designed and developed global path planning algorithms based on Hybrid A* and RRT*, as well as local path planning algorithms based on TEB and DWA.

Research Experience
======
## University of Malaya, Malaysia  
**Research Assistant in Autonomous Driving PnC Algorithms**  
*September 2021 – July 2022*  
Supervisors: **Chuah Joon Huang** (Professor, University of Cambridge) | **Rafidah Binti Md Noor** (Dean, Faculty of Computer Science)

- Achieved efficient convergence in autonomous driving by implementing the DDPG algorithm through techniques such as prioritized experience replay, reward function optimization, and hyperparameter tuning.

- Developed and implemented a robot autonomous planning and navigation method based on the A3C algorithm, optimizing the CNN data processing pipeline and reward function design.

## Design and Implementation of a Robot Pathfinding Method Based on Reinforcement Learning  
**Beijing University of Technology, Bachelor's Thesis (Project supported by the National Natural Science Foundation of China)**  
*September 2020 – July 2021*

- Optimized the classical Q-learning algorithm by incorporating eligibility traces and exploration strategies like ε-greedy and Softmax-Boltzmann distribution, proposing a rapidly converging Q(λ)-learning algorithm that improved the effectiveness and stability of robot path planning in complex environments.

- Conducted multiple comparative experiments on reinforcement learning algorithms using the ROS 1 system. The results showed that the algorithm reduced the number of iterations and training times by approximately 85%, demonstrating the high robustness of the optimal pathfinding algorithm for autonomous robots in various complex environments.
  
Personal Strengths
======
Proficient in autonomous driving decision-making, planning, and control algorithms. Skilled in advanced planning algorithms such as Lattice Planner, EM Planner, and reinforcement learning algorithms (DQN, DDPG, A3C, etc.), as well as classical path planning algorithms like Dijkstra, A*, and RRT. Expertise in vehicle lateral and longitudinal control algorithms, including PID, LQR, and MPC. Experienced with simulation platforms such as VTD, Carla, CarSim, Matlab, and Simulink. Proficient in using and developing on industrial computers based on the Linux system.

Professional Skills
======
**Programming Languages:** C, C++, Java, Python, Matlab, SQL, LabVIEW  
**Software Tools and Frameworks:** ROS 1/2, Carla, CarSim, AirSim, VTD, Protobuf, OpenAI Gym, OpenCV, PyTorch, TensorFlow, UML, NumPy, Pandas  
**English Proficiency:** IELTS Academic: 6.0

<!-- Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams -->
