---
layout: splash
author_profile: false
classes: wide
title: "Student projects"
permalink: /student-projects/
---

# Student projects

<figure style="width: 45%" class="align-right"><img src="/nanorobotics/assets/images/theses/insect.png"></figure>

## AI-based Maze Escape with an Insect-sized Autonomous Robot
Autonomous insect-scale robots, such as [mCLARI](https://ieeexplore.ieee.org/document/10341588), hold great potential for navigating and interacting within constrained, cluttered, and hazardous environments, such as collapsed structures, narrow pipelines, radioactive sites, and disaster areas—environments inaccessible to larger robots and unsafe for humans.
However, achieving robust [autonomous onboard intelligence](https://ieeexplore.ieee.org/document/8715489) at insect scales (sub-5 grams, sub-100 milliwatts) remains an unsolved challenge, as their form factor heavily restricts the resources available onboard, including memory, computation, and sensors.
Leveraging advances in ultra-low-power hardware architectures and highly optimized TinyML algorithms, this thesis aims to take the first steps toward enabling AI-driven perception capabilities aboard insect-scale robotic platforms.
Specifically, the project focuses on developing an autonomous visual navigation pipeline for insect-scale legged robots, using the [IsaacLab simulator](https://isaac-sim.github.io/IsaacLab/main/index.html).
The robot will be tasked with navigating a maze while avoiding collisions with walls. We will also develop optimized on-device continual learning techniques, enabling the robots to adapt to new scenarios autonomously.
We will explore self-supervised learning through a "learning from crashing" paradigm, mimicking insects that safely bump into objects; these collision events will provide training labels for on-device learning.
 
<figure style="width: 45%" class="align-left"><img src="/nanorobotics/assets/images/theses/vo.png"></figure>

## Learning-based Visual Odometry aboard Nano-drones
Any autonomous robots, including palm-sized nano-drones, navigate thanks to the interaction of three fundamental functional blocks.
The state estimator determines the current state of the system.
Then, what we call the onboard intelligence is responsible for solving the decision-making problem of choosing the next target state.
Finally, the control part brings the system from the current state to the target one.
This project focuses on the state estimation functionality via visual odometry (VO) algorithms for resource-constrained nano-drones. 
[Traditional pipelines](https://ieeexplore.ieee.org/document/6096039) for visual odometry rely on computationally costly feature extraction, matching, and geometric motion estimation stages, making them not yet fully exploitable aboard nano-drones.
In this project, the candidate will explore learning-based approaches, e.g., [DPVO](https://github.com/princeton-vl/DPVO) and [DEVO](https://github.com/tum-vision/DEVO), and work to mitigate these limitations on a visual odometry pipeline, allowing for the in-field evaluation of trade-offs between accuracy and computational cost.
The resulting system will be integrated aboard a [Crazyflie 2.1 brushless nano-drone](https://www.bitcraze.io/products/crazyflie-2-1-brushless/), leveraging the [GAP9](https://arxiv.org/abs/2407.13706v1) ultra-low power multi-core System-on-Chip for high-performance parallel onboard computation.

**Contacts:**
Ilenia Carboni [ilenia.carboni@supsi.ch](ilenia.carboni@supsi.ch),
Elia Cereda [elia.cereda@supsi.ch](elia.cereda@supsi.ch),
Daniele Palossi [daniele.palossi@supsi.ch](daniele.palossi@supsi.ch).

<figure style="width: 45%" class="align-right"><img src="/nanorobotics/assets/images/theses/mpc.svg"></figure>

## Embedded Learning-based Model Predictive Control on Agile Nano-drones
Agile flight and acrobatic maneuvers on quadrotors deal with hard-to-model dynamics and significant disturbances, while operating at the edge of the physical capabilities of the system.
Model Predictive Controllers (MPC) that combine physics- and learning-based dynamic models achieved great success on larger drones, but nano-drones face much tighter power and weight constraints that make these approaches prohibitive.
While their sub-10cm and sub-50g form factor constrains onboard computation to just embedded microcontroller units, [recent advances](https://ieeexplore.ieee.org/abstract/document/10610987) have shown MPC is achievable on nano-drones, albeit in ideal circumstances (linear MPC near hover, low speed flight).
This thesis aims to relax these constraints, leveraging learning-based dynamics models  for the first time on an agile nano-drone.
The resulting system will be integrated aboard a [Crazyflie 2.1 brushless nano-drone](https://www.bitcraze.io/products/crazyflie-2-1-brushless/), leveraging the [GAP9](https://arxiv.org/abs/2407.13706v1) ultra-low power multi-core System-on-Chip for high-performance parallel onboard computation.

**Contacts:**
Elia Cereda [elia.cereda@supsi.ch](elia.cereda@supsi.ch),
Daniele Palossi [daniele.palossi@supsi.ch](daniele.palossi@supsi.ch),
Dario Piga [dario.piga@supsi.ch](dario.piga@supsi.ch).
