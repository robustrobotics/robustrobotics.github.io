---
title: Planning Under Uncertainty
status: inactive

people:
  - ebrunskill
  - fdoshi

# description: |
#   Using global information to improve navigation in uncertain environments.

layout: project
last-updated: 2024-11-02
# image: "https://rrg-test.csail.mit.edu/uploads/Main/Research/zoom.png"

---
Continuous-state POMDPs provide a natural representation for a variety of tasks, including many in robotics. However, existing continuous-state POMDP approaches are limited by their reliance on a single linear model to represent the world dynamics. We have developed new switching-state (hybrid) dynamics models that can represent multi-modal state-dependent dynamics, and a new point-based POMDP planning algorithm for solving continuous-state POMDPs using this dynamics model. Additionally, POMDPs have succeeded in many planning domains because they can optimally trade between actions that increase an agent's knowledge and actions that increase an agent's reward. Unfortunately, most real-world POMDPs are defined with a large number of parameters which are difficult to specify from domain knowledge alone.

We have shown that the POMDP model parameters can be incorporated as additional hidden states in a larger 'model-uncertainty' POMDP, and we have developed an approximate algorithm for planning in the induced `model-uncertainty' POMDP. This approximation, coupled with model-directed queries, allows the planner to actively learn the true underlying POMDP and the accompanying policy.

## Publications
- E. Brunskill, L. Kaelbling, T. Lozano-Perez and Nicholas Roy. "Continuous-State POMDPs with Hybrid Dynamics''. Proceedings of the Tenth International Symposium on Artificial Intelligence and Mathematics, Fort Lauderdale, FL, 2008.
- F. Doshi, J. Pineau and N. Roy. "Bayes Risk for Active Learning in POMDPs''. Proceedings of the International Conference on Machine Learning (ICML), Helsinki, Finland, 2008, pp. 256-263.