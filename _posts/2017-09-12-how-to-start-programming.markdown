---
layout: post
title: My software
date: 2017-09-12 00:00:00 +0300
description: Open-source implementations of motion planning and trajectory prediction algorithms for autonomous robots and vehicles.
img: how-to-start.jpg # Add image post (optional)
tags: [Programming, Robotics, Motion Planning] # add tag
---

A collection of open-source repositories from my research on motion planning and trajectory prediction for autonomous robots and vehicles.

---

### MPCC — Model Predictive Contouring Control
**[github.com/tud-cor/amr-lmpcc](https://github.com/tud-cor/amr-lmpcc)**

A local motion planner based on Model Predictive Contouring Control (MPCC) for safe navigation in dynamic, unstructured environments. The planner generates smooth, collision-free trajectories in real time by tracking a reference path while simultaneously avoiding dynamic obstacles. Published in IEEE RA-L + IROS 2019.

<div style="text-align: center; margin: 16px 0;">
<iframe width="560" height="315" src="https://www.youtube.com/embed/2ulhqQIXFqQ" frameborder="0" allowfullscreen></iframe>
</div>

---

### Social-VRNN — Multi-modal Pedestrian Trajectory Prediction
**[github.com/tud-amr/social_vrnn](https://github.com/tud-amr/social_vrnn)**

A deep generative model for interaction-aware, multi-modal trajectory prediction of pedestrians. Social-VRNN uses a variational recurrent neural network to capture the uncertainty and social dynamics of pedestrian motion in one-shot predictions. Published at CoRL 2020.

<div style="text-align: center; margin: 16px 0;">
<iframe width="560" height="315" src="https://www.youtube.com/embed/tBr5v7TXyG0" frameborder="0" allowfullscreen></iframe>
</div>

---

### GO-MPC — Goal-Oriented Model Predictive Control
**[github.com/tud-amr/go-mpc](https://github.com/tud-amr/go-mpc)**

Combines a learned global guidance policy (trained with deep RL) with an online MPC planner. The RL policy recommends subgoals that steer the optimizer toward globally good solutions, enabling efficient navigation through complex, crowded environments. Published in IEEE RA-L + ICRA 2021.

<div style="text-align: center; margin: 16px 0;">
<iframe width="560" height="315" src="https://www.youtube.com/embed/sZBbWMnwle8" frameborder="0" allowfullscreen></iframe>
</div>

---

### MRCA-MAV — Multi-Robot Collision Avoidance
**[github.com/tud-amr/mrca-mav](https://github.com/tud-amr/mrca-mav)**

A decentralized trajectory optimization framework for multi-robot motion planning in dynamic environments. Each robot learns interaction-aware trajectory predictions and uses them inside a local optimizer to avoid collisions with other robots and dynamic agents. Published in IEEE RA-L + ICRA 2021.

<div style="text-align: center; margin: 16px 0;">
<iframe width="560" height="315" src="https://www.youtube.com/embed/i8HRGeOmcH4" frameborder="0" allowfullscreen></iframe>
</div>
