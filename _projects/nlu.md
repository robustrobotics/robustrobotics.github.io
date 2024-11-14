---
title: Natural Language Understanding for Human-Robot Interaction
status: inactive

# description: |
#   Using global information to improve navigation in uncertain environments.
people:
  - jarkin
  - rpaul
  - thoward
  - stellex
  - tkollar

layout: project
last-updated: 2024-11-07
# image: "https://rrg-test.csail.mit.edu/uploads/Main/Research/zoom.png"

---
Advances in robot autonomy have moved humans to a different level of interaction, where the ultimate success hinges on how effectively and intuitively humans and robots can work together to correctly accomplish a task. However, most service robots currently require fairly detailed low-level guidance from a trained operator, which often leads to constrained and non-intuitive interaction.

Alternatively, natural language provides a rich, intuitive and flexible medium for humans and robots to communicate information. Our goal is to enable robots to understand natural language utterances in the context of their workspaces. We seek algorithmic models that bridge the semantic gap between high-level concepts (e.g. entities, events, routes, etc.) embedded in language utterances and their low-level metric representations (e.g. cost maps and point clouds) necessary for a robot to act in the world.

We have developed probabilistic models like Generalized Grounding Graphs and Distributed Correspondence Graphs to infer a grounding for language descriptions in the context of the agent’s perceived representation. In recent work, we introduced Adaptive Distributed Correspondence Graphs for efficient reasoning about abstract spatial concepts.

Our ongoing research focuses on acquiring semantic knowledge about the environment from observations or language descriptions. This allows the robot to ground commands that refer to past events or acquired factual knowledge. Another area of research addresses language understanding for specifying high-level tasks like search and rescue operations. Further, we are also investigating language understanding in partially known environments and exploration strategies for acquiring new and unknown concepts.

## Publications
- R. Paul, J. Arkin, N. Roy, T. M. Howard, “Efficient Grounding of Abstract Spatial Concepts for Natural Language Interaction with Robot Manipulators”. Robotics Science and Systems 2016. (Best conference paper)
- Thomas Howard, Stefanie Tellex, Nicholas Roy. "A Natural Language Planner Interface for Mobile Manipulators." International Conference on Robotics and Automation (ICRA), Hong Kong, 2014.
- Stefanie Tellex, Ross Knepper, Adrian Li, Daniela Rus and Nicholas Roy. "Asking for Help Using Inverse Semantics." Proceedings of Robotics Science and Systems (RSS), Berkeley, CA, 2014. (Best conference paper)
- S. Tellex, T. Kollar, S. Dickerson, M. R. Walter, A. G. Banerjee, S. Teller, N. Roy. "Understanding Natural Language Commands for Robotic Navigation and Mobile Manipulation", Proceedings of the National Conference on Artificial Intelligence (AAAI), San Francisco, CA, 2011.