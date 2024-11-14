---
title: Exploration
status: inactive

people:
  - tkollar
  - fdoshi

# description: |
#   Using global information to improve navigation in uncertain environments.

layout: project
last-updated: 2024-11-01
# image: "https://rrg-test.csail.mit.edu/uploads/Main/Research/zoom.png"

---
Mapping as a research problem has received considerable attention in robotics recently. Mature mapping techniques now allow practitioners to reliably and consistently generate 2-D and 3-D maps of objects, office buildings, city blocks and metropolitan areas with a comparatively small number of errors. Nevertheless, the ease of construction and quality of map are strongly dependent on the exploration strategy used to acquire sensor data. We have shown that reinforcement learning can be used to optimize the trajectory of a vehicle exploring an unknown environment. One of the primary technical challenges of exploration is being able to predict the value of different sensing strategies efficiently. We have shown that a robot can learn the effect of sensing strategies from past experience using kernel-based regression techniques. The local regression model can then be used inside a global planner to optimize a trajectory. We have demonstrated this technique both for a mobile robot building a map of an unknown environment, and an airborne mobile sensor collecting data for weather prediction.

## Publications
- T. Kollar and N. Roy. "Trajectory Optimization using Reinforcement Learning for Map Exploration''. International Journal of Robotics Research, 27(2): 175-197, 2008.
- N. Roy, H. Choi, D. Gombos, J. Hansen, J. How and S. Park. "Adaptive Observation Strategies for Forecast Error Minimization''. Proceedings of the International Conference on Computational Science, Beijing, 2007.