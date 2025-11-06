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

* Sep 2022 - Present | University of Malaya, Malaysia \| Master of Engineering Science by Research (Equivalent to the MPhil)<br>
  Research Area: Autonomous Driving Planning and Decision-making Algorithm

* Sep 2019 – Jul 2021 \| Beijing University of Technology, China \| Undergraduate (2+2 joint education)<br>
  Major: Computer Science and Technology \| GPA: 82.39/100.00 \| Graduation Project Grade: 90.00/100.00 (Outstanding Graduate)

* Sep 2017- Aug 2019 \| Qinghai Nationalities University, China \| Bachelor's Degree in Engineering (Joint Education with BJUT)<br>
  Major: Computer Science and Technology \| GPA: 87.97/100.00<br>
<!-- * Ph.D in Version Control Theory, GitHub University, 2018 (expected) -->


Work Experience
======
## Guangzhou Qichen Technology Co., Ltd. (GAC Group - Ruqi Chuxing)
**Senior Autonomous Driving Algorithm Engineer**  
*Oct. – Present* 
**Project 1: Two-Stage Decision-Planning Architecture for Complex Urban Scenarios (Intersections & Merging)**
- **Decision-making Stage**: Engineered using Soft Actor-Critic (SAC) to produce robust merging and yielding behaviors at complex intersections and merging lanes. The optimized reward heavily penalizes time-to-collision while rewarding efficiency, enabling decisive navigation at unprotected intersections and in dense traffic.

- **Planning Stage**: Implemented via an EM Planner that performs trajectory-level refinement and arbitration among SAC candidates. Improved planner efficiency by incorporating the model’s predicted intent as a prior for heuristic search and by tuning the Quadratic Programming (QP) constraints to guarantee dynamic feasibility and safety during complex maneuvers (e.g., gap insertion).

**Project 2: Automated Topological Generation and Perception Post-Processing for the Crowdsourced Mapping (in Guangzhou, China)**
- **Automated Topo Generation**: Constructed geometric topological relationships between lane lines, generating self-consistent virtual lanes from trajectories (60% completion). Utilized perception centerlines matching actual lanes, establishing spatial correspondence, enhancing completion to 80%.

- **Diverge/Merge Detection and Connection**: Devised a post-processing framework to mitigate perception errors and reliably detect and connect complex diverging and merging areas. It analyzes geometric cues such as curb and lane distances to locate connection zones and construct smooth, topologically sound geometry. In a test on the 30 km map dataset from the GAC Group, it achieved 89.71% diverging detection (63.93% overall correct connection) and 71.68% merging detection (58.15% overall correct connection).

**Project 3: Planning-Based Reference Path Generation for Complex Intersections from Multi-Source Experience Trajectory Data**
- **Traffic Flow Model**: Contributed to a system for processing multi-source vehicular experience trajectories (UBM, MOT) to enhance path generation. It involved applying clustering algorithms (e.g., on crosswalks) and convex hull computations for automated recognition of intersections. Abstracted massive trajectory data into scalar density and vector direction fields, creating a traffic flow model.   

- **Planning generates the reference path**: A planning algorithm integrated traffic flow density and direction with QP and Bézier curves to ensure kinematic feasibility and robust, efficient trajectory generation, producing the intersection reference line. To improve stability and efficiency, an adaptive dual-planner strategy was used: Reeds-Shepp (simple scenarios) and hybrid A* (complex turns).

## Automotive Intelligence and Control of China (Beijing) Technology Co., Ltd.(AICC)
**Senior Motion Planning Algorithm Engineer**  
*July 2023 – Aug. 2024*

**Project 1: Implementation of L3 Autonomous Driving System for Urban/Highway NOA Based on Self-developed Computing Brain Development System (CBDES)**

 - **Longitudinal Control Algorithm**: Designed a high-performance longitudinal control algorithm for highway scenarios, employing a cascaded PID (position–velocity PID and velocity–acceleration PID) strategy. This system consistently maintained a speed-tracking error within ±0.5 km/h.

 - **Decision-making and Planning Algorithm**: Developed and optimized the Lattice Planner algorithm. Integrated multi-layer FSM decision-making, multi-constraint checks, collision-detection modules and path smoothing, reducing planning time and improving safety and decisions in dynamic environments.

**Project 2: Implementation of L3 Autonomous Driving System for Yutong BRT B7 Line Based on Huawei MDC 610 Domain Control Platform**

- **Multi-Agent Behavior Planning**: Developed and optimized a behavior planning framework based on the POMDP algorithm, constructed a collision prediction model for surrounding vehicles, and designed and updated the evaluation function. Implemented the vehicle’s Nudge function, increasing pedestrian avoidance and temporary obstacle avoidance success rates to 90%.

- **Motion Planning and Communication Integration**: Optimize motion planning algorithms based on the Spatio-Spatial Semantic Corridor (SSC) structure, uniformly model driving environment constraints, and refine planned trajectories. Established communication between the SSC structure and the ROS 2 system, enabling the publication and transmission of planned trajectories and other data.

## Beijing Sihetiandi Technology Co., Ltd.(SHTD) 
**Autonomous Driving R&D Engineer**  
*Sep. 2022 – June 2023*
- Coordinated mass-production deployment of an L4 autonomous driving stack on NVIDIA Orin; defined communication protocols between chassis and heterogeneous sensors; provided real-time mapping and navigation solutions based on SLAM (e.g., Cartographer) and GNSS for indoor and outdoor positioning.

- Architected global path-planning based on Hybrid A* and local planning modules employing Timed Elastic Band (TEB) to ensure kinematic feasibility and meet real-time performance requirements.

Research Experience
======
## University of Malaya, Malaysia  
**Implementation of End-to-End Autonomous Driving Decision-Making Technology Based on Deep Reinforcement Learning**  
*September 2022 – Present*  
Supervisors: **Chuah Joon Huang** - President & CEO, Southern University College (Malaysia) | **Anis Salwa Binti Mohd Khairuddin** - Head of Department, Electrical Engineering, Faculty of Engineering, University of Malaya (Malaysia)

- Enhanced the sample efficiency of the DDPG algorithm and accelerated end-to-end convergence by employing prioritized experience replay, dynamic hyperparameter adjustment, and staged parallel training.

- Designed an adaptive reward function and introduced multi-objective balancing strategies (e.g., trade-offs among safety, comfort, and efficiency), improving decision-making and planning performance.

## Design and Implementation of a Robot Pathfinding Method Based on Reinforcement Learning  
**Beijing University of Technology, Bachelor's Thesis (Project supported by the National Natural Science Foundation of China)**  
*Sep. 2020 – Jun. 2021*

- Proposed and evaluated two action-selection mechanisms (ε-greedy and Boltzmann-softmax), integrating them with an eligibility-trace Q(λ) learner to improve convergence and robustness.
- Built a Python simulation with interactive visualization to display policy evolution, action probabilities, and cumulative rewards in real time, enabling parameter tuning and reproducible experiments.
  
Key Strengths
======
Specialize in the design, optimization, and validation of decision-making and planning algorithms for autonomous vehicles, with hands-on expertise in reinforcement learning methods (DQN, SAC), advanced planners (Lattice Planner, EM Planner, POMDP frameworks) and classical graph/search algorithms (Dijkstra, A*), as well as longitudinal and lateral vehicle controllers (PID). Conduct large-scale simulation studies and performance validation on platforms such as VTD, Carla, and CarSim, and manage system integration and deployment on Linux-based industrial computers.

Technical Skills
======
**Programming Languages:** C/C++, Java, Python, Matlab <br>
**Software Tools and Frameworks:** ROS 1/2, Carla, CarSim, AirSim, VTD, Protobuf, OpenAI Gym, OpenCV, PyTorch <br>
**English Proficiency:** Master’s programme conducted entirely in English

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
