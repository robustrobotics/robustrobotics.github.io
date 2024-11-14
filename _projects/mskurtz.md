---
title: Uncertainty-Aware Navigation in Structured, Unknown Environments

description: |
  Using global information to improve navigation in uncertain environments.

people:
  - mskurtz
  - yveys
  - hbiggie
  - sprentice
  - jbanfi

layout: project
last-updated: 2024-11-04

---

We would like for robots to navigate efficiently in structured, unknown environments which have large state spaces for planning, either due to their lengthscale or the presence of uncertainty in the environment. We recognize that environmental structure, like doors, hallways, and exit signs in office buildings, and roads, forests, bodies of water, and bridges in outdoor environments can provide cues which better enable agents to infer high-quality navigation strategies.

Our research develops uncertainty-aware models and planners which use implicit and explicit environmental structure to improve planning efficiency and quality. We have used geometric and explicit object-level information to learned sampling distributions for sampling-based motion planners which enable efficient planning at longer horizons in partially known environments. We have proposed a hierarchical planning representation for multi-query robot navigation which uses previous planning experience to coarsely capture implicit environmental structure and prune regions of the environment which are unlikely to lead to low cost solutions for hierarchical, multi-query robot navigation. In our current work, we are developing collaborative multiagent planning algorithms which explicitly consider the team costs and benefits of taking sensing actions in stochastic environments when we have access to stale environmental data.

## Research Themes
Semantic planning, hierarchical planning, planning under uncertainty, multiagent planning under uncertainty

## Publications
- M. Stadler, K. Liu, N. Roy. "Online High-Level Model Estimation for Efficient Hierarchical Robot Navigation." IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2021. PDF

- K. Liu\*, M. Stadler\*, and N. Roy. "Learned Sampling Distributions for Efficient Planning in Hybrid Geometric and Object-Level Representations." International Conference on Robotics and Automation (ICRA), 2020. PDF Video

