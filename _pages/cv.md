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

* Sep 2019 – Jul 2021 \| Beijing University of Technology, China \| Undergraduate (2+2 joint education)
  Major: Computer Science and Technology \| GPA: 82.39/100.00 \| Graduation Project Grade: 90.00/100.00 (Outstanding Graduate)

* Sep 2017- Aug 2019 \| Qinghai Nationalities University, China \| Bachelor's Degree in Engineering (Joint Education with Beijing University of Technology)
  Major: Computer Science and Technology \| GPA: 87.97/100.00


<!-- * Ph.D in Version Control Theory, GitHub University, 2018 (expected) -->

Work Experience
======

#### Automotive Intelligence and Control of China Co., Ltd. (Beijing)  
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

#### Beijing SinoPark Technologies Co., Ltd.  
**Autonomous Driving R&D Engineer**  
*September 2022 – June 2023*

- Led the development of L4 autonomous driving architecture based on the NVIDIA Orin platform and ROS 1, designing communication methods between the chassis and various sensors.

- Implemented indoor and outdoor real-time mapping and navigation systems using SLAM algorithms such as Cartographer and LIO-SAM, and GNSS-based positioning.

- Designed and developed global path planning algorithms based on Hybrid A* and RRT*, as well as local path planning algorithms based on TEB and DWA.

Work experience
======
* Spring 2024: Academic Pages Collaborator
  * Github University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
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
* Currently signed in to 43 different slack teams
