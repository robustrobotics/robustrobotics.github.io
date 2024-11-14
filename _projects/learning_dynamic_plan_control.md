---
title: Learning for Highly Dynamic Planning and Control
status: inactive

# description: |
#   Using global information to improve navigation in uncertain environments.
people:
  - crichter

layout: project
last-updated: 2024-11-08
# image: "https://rrg-test.csail.mit.edu/uploads/Main/Research/zoom.png"

---
Navigation in unknown environments is difficult. As an autonomous robot explores an environment it has never seen, it must construct a map as it travels and replan its route as obstacles are discovered. Traditional planning algorithms require that the robot avoid situations that might cause it to crash, and therefore treat unobserved space as potential unseen obstacles. Naturally, navigation can be slow in cluttered spaces or even hallways, in which most robots must slow dramatically whenever rounding a corner.

Some of our recent work has involved using machine learning to capture (at training time) the local environmental geometry so that we may predict (at run time) the probability that taking an action that guides it into unknown space will cause the robot to collide. Consequently, though the robot is now allowed to violate strict safety constraints, we maintain 100% empirical safety, yet see impressive improvements in speed (see here for video). Relatedly, we have also developed an adaptation of this technique that re-introduces empirical safety guarantees. The learning algorithm instead predicts which actions will give the robot an information gain so that it may reach the goal faster (e.g. taking wider turns around corners so that it need not slow down as much).

Our ongoing research direction involves using learning to augment the performance of autonomous planning and control tasks, including intelligent navigation of more topologically complex environments and using monocular camera images to predict collision probability at high speeds.

## Publications
- Charlie Richter and Nicholas Roy. "Bayesian Learning for Safe High-Speed Navigation in Unknown Environments''. In Proceedings of the International Symposium on Experimental Robotics (ISER), Tokyo, 2016. [PDF]
- Charlie Richter, William Vega-Brown, and Nicholas Roy. "Bayesian Learning for Safe High-Speed Navigation in Unknown Environments''. In Proceedings of the International Symposium on Robotics Research (ISRR), Sestri Levante, 2015. [PDF]