---
title: Mobile Manipulation
status: inactive

people:
  - jglover

# description: |
#   Using global information to improve navigation in uncertain environments.

layout: project
last-updated: 2024-10-31
# image: "https://rrg-test.csail.mit.edu/uploads/Main/Research/zoom.png"

---
Robot manipulators largely rely on complete knowledge of object geometry in order to plan their motion and compute successful grasps. If an object is fully in view, the object geometry can be inferred from sensor data and a grasp computed directly. If the object is occluded by other entities in the environment, manipulation based on the visible part of the object may fail; therefore, to compensate, object recognition is often used to identify the location of the object and compute the grasp from a prior model. We are developing algorithms for geometric inference and manipulation planning that allow grasp plans to be computed with only partial information about the objects in the environment and their geometry. We are developing these ideas both for small-object manipulation in the home, and large-object supply-chain manipulation.

## Publications
- J. Glover, D. Rus and N. Roy. "Manipulation using Probabilistic Models of Object Geometry''. Proceedings of Robotics: Science and Systems (R:SS), 2008.