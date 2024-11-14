---
title: Learning to Guide Planning under Uncertainty

# description: |
#   Using global information to improve navigation in uncertain environments.

people:
  - cbradley
  - gstein

layout: project
last-updated: 2024-11-11
image: "https://rrg-test.csail.mit.edu/uploads/Main/Research/ltl_lsp_overview.png"

---

We aim to enable robots to plan efficiently and optimally across a number of different domains in the presence of uncertainty. In particular, we are interested in problems where the environment is revealed as the robot acts within it, and using learning to better plan in those problems.

This research is focused on learning models to predict the outcomes and costs of executing high-level actions. Initially, we focused primarily on the problem of goal-directed navigation in partially revealed environments, considering actions which lead the robot to enter previously unknown space. By predicting if the agent's goal can be reached via a particular subgoal (as well as the associated cost), we were able to incorporate prior experience into our planner, and improve the decision making process. Expanding on this, we considered learning to model the outcomes of actions in temporally extended tasks, in particular those expressed in Linear Temporal Logic. Once again, we were able to plan using past experience to outperform an uninformed baseline. To support these planners, this line of work has also considered how best to model an environment as it is being explored. To that end, we designed and implemented a mapping representation, built directly from RGB input, that builds a topological representation of an environment which is well suited for planning with high-level, exploratory actions.

Currently, we are investigating applying these methods to the domain of task and motion planning.

## Research Themes
Planning under Uncertainty, Deep Learning, Planning with Learned Models, Hierarchical Planning, Linear Temporal Logic, Task and Motion Planning

## Publications
- Christopher Bradley, Adam Pacheck, Gregory J. Stein, Sebastian Castro, Hadas Kress-Gazit, and Nicholas Roy. "Learning and planning for temporally extended tasks in unknown environments." 2021 IEEE International Conference on Robotics and Automation (ICRA). IEEE, 2021. PDF Video
- Gregory J. Stein\*, Christopher Bradley\*, Victoria Preston\*, Nicholas Roy. "Enabling topological planning with monocular vision." 2020 IEEE International Conference on Robotics and Automation (ICRA). IEEE, 2020. PDF Video
- Gregory J. Stein\*, Christopher Bradley\*, and Nicholas Roy. "Learning over subgoals for efficient navigation of structured, unknown environments." Conference on robot learning. PMLR, 2018. PDF Video