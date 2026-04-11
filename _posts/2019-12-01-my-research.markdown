---
layout: post
title: My Research
date: 2019-10-15 00:00:00 +0300
description: Research on end-to-end ML motion planning, VLA models for autonomous driving, and data-driven navigation among humans.
img: research_cover.png # Add image post (optional)
tags: [Robotics, Motion Planning, Deep Learning, Autonomous Driving] # add tag
---

My work sits at the intersection of **autonomous driving**, **motion planning**, and **large-scale machine learning**. Over the past decade I have progressed from academic research on robot navigation in crowded environments to building production-grade end-to-end ML planners deployed on real vehicles.

---

## Current Work — End-to-End ML Planning at NVIDIA

At NVIDIA I am part of the production team of **[Alpamayo](https://nvidianews.nvidia.com/news/alpamayo-autonomous-vehicle-development)** — a chain-of-thought Vision-Language-Action (VLA) model for end-to-end motion planning built on a state-of-the-art LLM backbone (LLaMA/QWEN), now deployed on Mercedes-Benz vehicles.

My focus areas include:

- **VRU Safety** — Led the Vulnerable Road Users (VRU) Operational Design Domain end-to-end, improving VRU collision handling from 50 % to 91 % while reducing ghost-brake frequency by 50 % and underspeed events by ~90 %.
- **Model Architecture** — Main contributor to the transition to a 0.5B transformer backbone and primary developer of the trajectory decoder.
- **Chain-of-Thought Reasoning** — Improved the model's CoT reasoning by leveraging large LLMs for automated label generation and designing a question-and-answer training strategy.
- **Data Augmentation & Mining** — Developed novel strategies for rare and safety-critical scenarios, reducing front collisions by 20 % and rear collisions by 15 %.
- **Reinforcement Learning** — Developed an open-loop RL approach for trajectory refinement targeting rare and safety-critical events.

---

## ML Motion Planning at Motional (2022–2024)

At Motional I led the trajectory generation ML project and later managed the Motion Planning Research team of nine engineers and researchers. My work focused on bringing ML into the core of the autonomous driving stack:

- **ML Trajectory Generation** — Developed Motional's first ML-based trajectory generator, improving planning performance by **10%**. This involved designing the model architecture, training pipeline, and inference stack for deployment.
- **Continuous Learning** — Contributed to Motional's continuous learning framework through scenario mining and data balancing strategies, novel training techniques to prevent catastrophic forgetting, and enabling continuous refinement of prediction models — achieving a **15% average prediction performance improvement** across multiple metrics.
- **Patents** — Co-invented two patents: one on a learning-based model for predicting the intentions of other vehicles, and another on a novel motion planning approach for unstructured environments.

---

## PhD Research — Interaction-Aware Motion Planning (TU Delft, 2018–2022)

My doctoral thesis — *[Interaction-Aware Motion Planning in Crowded Dynamic Environments](https://repository.tudelft.nl/record/uuid:0bc3677d-dc15-4f93-a079-8d600e967c5a)* — was supervised by Prof. Javier Alonso-Mora at TU Delft's Department of Cognitive Robotics.

The core challenge: how should a robot or autonomous vehicle navigate safely and efficiently when surrounded by humans whose intentions and future movements are uncertain?

My research combined **optimization-based** and **learning-based** methods to tackle this:

1. **Safe & social-aware motion planners** — combining Model Predictive Contouring Control (MPCC) with learned prediction models to produce collision-free, human-aware trajectories.
2. **Deep generative trajectory prediction** — Social-VRNN, a variational approach for multi-modal, interaction-aware pedestrian prediction.
3. **Subgoal-guided planning (GO-MPC)** — a reinforcement-learning policy that recommends navigation subgoals to an online optimizer, enabling globally guided, locally optimal motion.

If you are interested in any of these topics, feel free to [contact me](mailto:brunoffbrito0@gmail.com)!
