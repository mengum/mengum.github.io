---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Contact
======

Meng Meng (孟猛) &nbsp;|&nbsp; +86 13756221062 (WhatsApp/WeChat) &nbsp;|&nbsp; meng.bjut@gmail.com &nbsp;|&nbsp; [https://mengum.github.io/](https://mengum.github.io/)

Education
======

## [University of Malaya, Malaysia](https://www.um.edu.my/)
*Sep. 2022 - Present* &nbsp;|&nbsp; Master of Engineering Science by Research (MPhil / Full-time)  
Supervisors: [Dr. Chuah Joon Huang](https://umexpert.um.edu.my/jhchuah.html) and [Dr. Anis Salwa Binti Mohd Khairuddin](https://umexpert.um.edu.my/anissalwa.html)

## Beijing University of Technology (BJUT), China
*Sep. 2017 - July 2021* &nbsp;|&nbsp; Computer Science and Technology | GPA: 87.97/100.00 (3.65/4.0) | Outstanding Graduate  
B.Eng. (2+2 Joint Degree with Qinghai Nationalities University), Full-time | National Project 211 University

Publication
======

## DBP-Plan: A Driving-Experience Layer for Reference-Line Generation at Urban Intersections
*IEEE Transactions on Intelligent Transportation Systems (T-ITS) | SCI Q1*

Research Experience
======

## [University of Malaya, Malaysia](https://www.um.edu.my/)
**Multimodal Embodied Policy Co-Training with Imitation and Reinforcement Learning**  
*Master of Engineering Science by Research, Sep. 2022 - Present*

- Integrated expert demonstration trajectories based on multimodal visual perception and joint state sequences to construct a continuous action-chunked decision space tailored for long-horizon manipulation. Adopted a two-stage co-training paradigm that extracts human manipulation priors via supervised imitation learning before incorporating progressively weighted Proximal Policy Optimization (PPO) for online interactive trial-and-error, effectively mitigating single-step error accumulation and enhancing manipulation robustness in unseen scenarios.

Work Experience (Full-time)
======

## [Neolix Technologies Co., Ltd.](https://www.neolix.ai/) (新石器慧通科技股份有限公司)
**Senior Autonomous Driving Algorithm Engineer**  
*Mar. 2026 - Present*

**Project 1: Online Visual Mapping and Environmental Reasoning System**

- **Online Visual Mapping & Algorithm Deployment**: Spearheaded the production deployment of a vision-only mapping and environmental reasoning solution. Designed a robust mapping pipeline incorporating lane segment merging, head-to-tail stitching, Catmull-Rom spline smoothing, and same-side assembly to handle incomplete and noisy multi-source perception inputs; constructed a stable, unified environmental representation tailored for downstream decision-making and planning, enabling continuous autonomous logistics delivery across over 20 kilometers of mapless road sections.

- **Road Network Topology Construction & RL Exploration**: Built a road network search graph from lane geometry and lateral reachability for lane-level localization. Explored Reinforcement Learning (RL) to optimize mapless environmental reasoning by formulating lane completion as autoregressive graph node generation; designed connectivity rewards to replace heuristic geometric matching, significantly enhancing topological connectivity and robustness at complex intersections.

**Project 2: Navigation Pipeline Governance and Reference Line System Optimization**

- **Navigation Intent Parsing & Lane-Change Planning Optimization**: Optimized global routing parsing and mapping logic to bridge macroscopic navigation intents with microscopic lane-change reference lines. Refined reference line generation and smoothing algorithms to provide a high-quality trajectory search space for motion planning; enhanced lane selection and lane-change decisions in complex road geometries (e.g., merging/diverging zones), substantially improving autonomous lane-change success rates and stability in dynamic traffic.

## [Guangzhou Automobile Group Co., Ltd.](https://www.gac.com.cn/) (GAC Group)
**Senior Autonomous Driving Algorithm Engineer**  
*Oct. 2024 - Feb. 2026*

**Project 1: Trajectory Planning and Reference-Line Generation in Complex Scenarios**

- **Driving-Experience Layer Construction**: Partitioned crowdsourced trajectories based on origin-destination topological relationships to form human driving experience corridors. Decoupled trajectory support from directional consistency, characterizing empirical driving trajectories via a coherence-aware anisotropic tensor field to provide behavioral priors for complex intersection planning.

- **Intersection Reference Line Search & Generation**: Transformed the empirical tensor field into arc-length-integrated edge costs, leveraging both density and directional tensors to guide node expansion and analytical goal connection in Hybrid A*; ensured path search convergence toward human-like driving corridors between topological poses, outputting continuous reference lines after post-smoothing.

**Project 2: Automated Topology Generation and Perception Post-Processing for SD Pro Maps**

- **Lane Topology Completion & Merge/Diverge Construction**: Constructed lane geometric topology by matching vehicle trajectories with perceived centerlines to auto-generate self-consistent virtual lanes, boosting urban map completeness to over 90%. Designed a perception post-processing framework to suppress upstream noise, leveraging geometric cues like curb-to-lane distances to accurately localize and reliably connect complex merging and diverging zones into smooth, topologically valid structures.

## [Automotive Intelligence and Control of China Co., Ltd.](https://www.china-icv.cn/) (AICC)
**Senior Autonomous Driving Motion Planning Engineer**  
*July 2023 - Aug. 2024*

**Project 1: Implementation of L3 Autonomous Driving System for Urban/Highway NOA based on the Computational Base and DevElopment System (CBDES)**

- **Longitudinal Control Algorithm**: Designed a high-performance longitudinal control algorithm for highway scenarios, employing a cascaded PID (position–velocity PID and velocity–acceleration PID) strategy. This system consistently maintained a speed-tracking error within ±0.5 km/h.

- **Decision-making and Planning Algorithm**: Developed and optimized the Lattice Planner algorithm. Integrated multi-layer FSM decision-making, multi-constraint checks, collision-detection modules and path smoothing, reducing planning time and improving safety and decisions in dynamic environments.

**Project 2: Implementation of L3 Autonomous Driving System for Yutong B7 Rapid Transit Line**

- **Multi-Agent Behavior Planning**: Developed and optimized a behavior planning framework based on the POMDP algorithm, constructed a collision prediction model for surrounding vehicles, and designed and updated the evaluation function. Implemented the vehicle's Nudge function, increasing pedestrian avoidance and temporary obstacle avoidance success rates to 90%.

- **Motion Planning and Communication Integration**: Optimized motion planning algorithms based on the Spatio-Spatial Semantic Corridor (SSC) structure, uniformly modelled driving environment constraints, and refined planned trajectories. Established communication between the SSC structure and the ROS 2 system, enabling the publication and transmission of planned trajectories and other data.

Key Strengths
======
Specialized in end-to-end decision-making, planning, and multimodal embodied algorithms for structured and unstructured environments, bridging academic research depth and engineering deployment. Well-versed in Reinforcement Learning (PPO, SAC, etc.), POMDP, and hybrid imitation-RL training paradigms, as well as action generation models such as VLA, Diffusion, and Flow Matching. Adept at fusing data-driven end-to-end policies with classical motion planning (Hybrid A*, numerical optimization) for safety assurance, effectively resolving generalization bottlenecks in complex interactions. Familiar with low-level closed-loop control (PID/LQR) and proficient in constructing simulation and transfer loops via ROS 1/2, MuJoCo, Isaac, and Gazebo to drive the deployment of general embodied systems.

Technical Skills
======
**Programming Languages:** C/C++, Python <br>
**Software Tools:** ROS 1/2, MuJoCo, Isaac, Gazebo, CARLA, CarSim, VTD, OpenAI Gym, PyTorch <br>
**English Proficiency:** IELTS Academic: 6.5

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