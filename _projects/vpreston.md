---
title: Robotic Expeditionary Science
status: inactive

# description: |
#   Using global information to improve navigation in uncertain environments.

people:
  - vpreston
  - gflaspohler

layout: project
last-updated: 2024-11-10
image: "https://rrg-test.csail.mit.edu/uploads/Main/Research/spatiotemporal_dynamics.png"

---

In the expeditionary sciences, spatiotemporally varying environments --- hydrothermal plumes, algal blooms, lava flows, or animal migrations --- are ubiquitous. Mobile robots are uniquely well-suited to study and sample from these dynamic, mesoscale natural environments, however to collect elucidating observations of unknown, partially-observed spatiotemporal distributions for scientific inquiry requires decision-making under uncertainty and sometimes severe operational constraints. For instance, some of the most advanced autonomous underwater vehicles (AUVs) used in oceanographic research operate with open-loop controllers and have severely limited acoustic communication with external actors (i.e., a ship).

We formalize expeditionary science as a **sequential decision-making problem**, modeled using the language of partially-observable Markov decision processes (POMDPs). Solving the expeditionary science POMDP under real-world constraints requires efficient probabilistic modeling and decision-making in problems with complex dynamics and observational models. Previous work in informative path planning, adaptive sampling, and experimental design have shown compelling results, largely in static environments, using data-driven models and information-based rewards. However, these methodologies do not trivially extend to expeditionary science in spatiotemporal environments: they generally do not make use of scientific knowledge such as equations of state dynamics, they focus on information gathering as opposed to scientific task execution, and they make use of decision-making approaches that scale poorly to large, continuous problems with long planning horizons and real-time operational constraints.

In our work, we tackle these and other challenges related to probabilistic modeling and decision-making in expeditionary science. In particular, we look for ways to exploit scientific intuition to overcome challenges in sample efficient dynamics learning under partial observability and leverage notions of uncertainty in dynamic planning windows. We ground our work in specific scientific contexts, such as deep sea hydrothermal vent charting.

## Research Themes
Informative path planning, planning under uncertainty, adaptive sampling, belief representations, physics-informed learning, field robotics

## Publications
- G. Flaspohler*, V. Preston*, A.P.M. Michel, Y. Girdhar, and N. Roy. "Information-Guided Robotic Maximum Seek-and-Sample in Partially Observable Continuous Environments" Robotics and Automation Letters, 2019.PDF
- V. Preston, "Adaptive Sampling of Transient Environmental Phenomena with Autonomous Mobile Platforms" Massachusetts Institute of Technology, Master's Thesis, 2019. PDF
- G. Flaspohler, N. Roy, and J.W. Fisher III. "Belief-dependent macro-action discovery in POMDPs using the value of information" Advances in Neural Information Processing Systems, 2020. PDF
- V. Preston*, G. Flaspohler*, A.P.M. Michel, J.W. Fisher III, N. Roy. "Robotic Planning under Uncertainty in Spatiotemporal Environments for Expeditionary Science" Conference on Reinforcement Learning and Decision Making, 2022.

