---
layout: splash
author_profile: false
classes: wide
title: "Student projects"
permalink: /student-projects/
---

# Student projects

<figure style="width: 20%" class="align-left"><img src="/nanorobotics/assets/images/theses/vo.png"></figure>

## Learning-based Visual Odometry aboard Nano-drones
Any autonomous robots, including palm-sized nano-drones, navigate thanks to the interaction of three fundamental functional blocks.
The state estimator determines the current state of the system.
Then, what we call the onboard intelligence is responsible for solving the decision-making problem of choosing the next target state.
Finally, the control part brings the system from the current state to the target one.
This project focuses on the state estimation functionality via visual odometry (VO) algorithms for resource-constrained nano-drones. 
Traditional pipelines [1] for visual odometry rely on computationally costly feature extraction, matching, and geometric motion estimation stages, making them not yet fully exploitable aboard nano-drones.
In this project, the candidate will explore deep neural networks (DNN) [2, 3] to mitigate these limitations on a visual odometry pipeline, allowing for the in-field evaluation of trade-offs between accuracy and computational cost.
The resulting system will be integrated aboard a [Crazyflie 2.1 brushless nano-drone](https://www.bitcraze.io/products/crazyflie-2-1-brushless/), leveraging the [GAP9](https://arxiv.org/abs/2407.13706v1) ultra-low power multi-core System-on-Chip for high-performance parallel onboard computation.

**Contacts:**
Elia Cereda [elia.cereda@idsia.ch](elia.cereda@idsia.ch),
Daniele Palossi [daniele.palossi@idsia.ch](daniele.palossi@idsia.ch).

<figure style="width: 20%" class="align-left"><img src="/nanorobotics/assets/images/theses/mpc.svg"></figure>

## Embedded Learning-based Model Predictive Control on Agile Nano-drones
Agile flight and acrobatic maneuvers on quadrotors deal with hard-to-model dynamics and significant disturbances, while operating at the edge of the physical capabilities of the system.
Model Predictive Controllers (MPC) that combine physics- and learning-based dynamic models achieved great success on larger drones, but nano-drones face much tighter power and weight constraints that make these approaches prohibitive.
While their sub-10cm and sub-50g form factor constrains onboard computation to just embedded microcontroller units, [recent advances](https://ieeexplore.ieee.org/abstract/document/10610987) have shown MPC is achievable on nano-drones, albeit in ideal circumstances (linear MPC near hover, low speed flight).
This thesis aims to relax these constraints, leveraging learning-based dynamics models  for the first time on an agile nano-drone.
The resulting system will be integrated aboard a [Crazyflie 2.1 brushless nano-drone](https://www.bitcraze.io/products/crazyflie-2-1-brushless/), leveraging the [GAP9](https://arxiv.org/abs/2407.13706v1) ultra-low power multi-core System-on-Chip for high-performance parallel onboard computation.

**Contacts:**
Elia Cereda [elia.cereda@idsia.ch](elia.cereda@idsia.ch),
Daniele Palossi [daniele.palossi@idsia.ch](daniele.palossi@idsia.ch),
Dario Piga [dario.piga@idsia.ch](dario.piga@idsia.ch).
