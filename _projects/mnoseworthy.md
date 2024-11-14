---
title: Exploration and Curiosity for Robotic Manipulation

# description: |
#   Using global information to improve navigation in uncertain environments.

people:
  - mnoseworthy
  - sshaw
  - ibrand

layout: project
last-updated: 2024-11-11
---

In many environments such as households or office buildings, robots frequently have to interact with unknown objects or perform novel tasks. However, models that support these interactions often require large amounts of carefully curated training data from known object models and struggle to adapt to new object instances. In this line of work, we explore how robots can efficiently adapt to novel scenarios by leveraging prior experience and self-supervision.

Our research has focussed on developing adaptive versions of learned modules which allow a robot to successfully interact with previously unseen objects after only a handful of attempts. One difficulty of interacting with novel objects is the diversity of visual features. For example, even though doors share common structure, their visual features vary significantly between instances. We develop a learning paradigm that combines the adaptivity of Gaussian Processes with learned features from CNNs to allow a robot to quickly integrate prior experience with online data [1]. Another difficulty with unknown object interaction arises from non-visual properties such as mass and friction. We develop object-centric models which allow a robot to separately reason about object-specific properties and shared global dynamics [3]. This factorization allows a robot to quickly adapt to new objects by only reasoning about relevant variation. Finally, all this work is done within a self-supervision paradigm where the robot can explicitly reason about information gain [2].

## Research Themes
Planning under uncertainty, manipulation, online adaptation, active learning

## Publications
- C. Moses\*, M. Noseworthy\*, L. Kaelbling, T. Lozano-Pérez and N. Roy. "Visual Prediction of Priors for Articulated Object Interaction." International Conference on Robotics and Automation (ICRA), 2020.
- M. Noseworthy\*, C. Moses\*, I. Brand\*, S. Castro, L. Kaelbling, T. Lozano-Pérez and N. Roy. "Active Learning of Abstract Plan Feasibility." Robotics Science and Systems (RSS), 2021.
- I. Brand\*, M. Noseworthy\*, S. Castro, and N. Roy. “Object-Factored Models with Partially Observable State.” Object-Factored Models with Partially Observable State (RLDM), 2022.
