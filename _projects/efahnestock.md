---
title: Navigating Outdoor Environments

# description: |
#   Using global information to improve navigation in uncertain environments.

people:
  - efahnestock

layout: project
last-updated: 2024-11-11
image: "https://rrg-test.csail.mit.edu/uploads/Main/Research/zoom.png"

---

Natural outdoor environments present unique challenges to robot navigation and control. Safely traversing forests, deserts, or other natural scenes requires approaches that can learn or encode properties of these environments not reasoned about in traditional robotic planners. For example, purely geometric planners consider all obstacles identically, and will attempt to avoid grass or small bushes that are not in reality obstacles for the robot, leading to suboptimal plans and unnecessarily longer trajectories.

New advances in machine learning that improve on the ability of robots to extract the semantics of their surroundings hold promise for context-informed outdoor robot navigation. In our current research we are looking at ways to exploit the underlying semantic correlations in the environment, in order to allow global motion planners to more efficiently navigate previously unobserved areas. To ensure safety, we are also exploring ways to represent the semantic structure of the robot's surroundings within the context of online vector field-based local motion planners, that can guarantee obstacle avoidance and convergence to a local goal by exploiting the topological properties of the environment.

## Research Themes
Semantic planning, outdoor navigation, field robotics