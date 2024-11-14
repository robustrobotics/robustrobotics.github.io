---
title: Enabling Semantic Understanding for Autonomous Marine Robots
status: inactive

# description: |
#   Using global information to improve navigation in uncertain environments.

layout: project
last-updated: 2024-11-06
# image: "https://rrg-test.csail.mit.edu/uploads/Main/Research/zoom.png"

---
The oceans cover over 70% of the Earth’s surface, yet less than five percent of this important biosphere has been explored to date. Much of the vast marine environment is dangerous or inaccessible to human divers. Thus, the task of exploring Earth’s oceans will fall to marine robots. However, the development of exploratory marine robots has been stymied by the marine environment's unique challenges. The lack of radio communication forces all human control to pass through high latency, low-bandwidth acoustic channels or hardwire tethers. These conditions necessitate the development of comprehensive and robust robot autonomy.

Our work in this area is split between two complementary thrusts: 1) learning an abstract representation of underwater image data that is conducive to semantic reasoning, and 2) using that abstract representation to build probabilistic models of the robot’s visual environment that allow more efficient exploratory path planning, anomaly detection, and mission data summarization.

We plan to address the problem of learning a meaningful feature representation of underwater images using deep learning. Even given the impressive performance of deep learning algorithms on computer vision problems, this is still challenging. Underwater images are very visually distinct from standard image datasets and there are no large corpora of labeled underwater image data available. Our current research direction involves using unsupervised convolutional autoencoders or minimally-supervised transfer learning frameworks to learn a latent feature representation of underwater image data.

Given this abstract feature representation, we are applying various probabilistic models to represent the robot’s knowledge about the observable world. Topic models provide a natural probabilistic framework for both anomaly detection and data summarization. Much of our previous work has focused on extending the Hierarchical Dirichlet Process (HDP), a Bayesian nonparametric topic model, to the real-time, spatiotemporal image data from a marine robot’s video stream. Our ongoing research direction involves building more sophisticated hierarchical topic models that allow a robot to understand the environment at multiple levels of abstraction.