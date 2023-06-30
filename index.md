---
layout: splash
title: Nanorobotics Group
header:
  image: /assets/images/header.jpg
people:
  - image_path: https://idsia-robotics.github.io/assets/images/daniele_palossi.png
    alt: Dr. Daniele Palossi
    title: Dr. Daniele Palossi
    excerpt: 'Senior Researcher, Group lead<br/> [Webpage](https://scholar.google.ch/citations?user=5v_dElkAAAAJ)'
  - image_path: https://idsia-robotics.github.io/assets/images/elia_cereda.jpg
    alt: Elia Cereda
    title: Elia Cereda
    excerpt: 'PhD Student<br/> [Webpage](https://scholar.google.ch/citations?user=GPJziQsAAAAJ)'
  - image_path: https://idsia-robotics.github.io/assets/images/luca_crupi.jpg
    alt: Luca Crupi
    title: Luca Crupi
    excerpt: 'PhD Student<br/> [Webpage](https://scholar.google.ch/citations?user=yO4B8GkAAAAJ)'
---

<script type="text/javascript" async
    src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/MathJax.js?config=TeX-AMS-MML_HTMLorMML">
</script>

<script type="text/javascript" src="https://npmcdn.com/flickity@2/dist/flickity.pkgd.js"></script>

<link rel="stylesheet" href="//maxcdn.bootstrapcdn.com/font-awesome/4.3.0/css/font-awesome.min.css">
<link rel="stylesheet" href="//cdn.rawgit.com/jpswalsh/academicons/master/css/academicons.min.css">
<link rel="stylesheet" href="{{'/assets/css/flickity.css'| relative_url }}">
<link rel="stylesheet" href="{{'/assets/css/csl-blocks.css'| relative_url }}">

<style>
  
  body {text-align: justify}

  .feature__wrapper {
    border-bottom: none;
  }

  .feature__item{
    margin-bottom: 0.3em;
  }
  .feature__item .archive__item{
    width: 100%;
    overflow: auto;
  }
  .feature__item .archive__item .archive__item-teaser{
    float: left;
    width: 35%;
    padding: 0em;
    margin: 0em;
    margin-right: 0.3em;
  }

  .feature__item .archive__item .archive__item-body{
    float: left;
    padding: 0em;
    margin: 0em;
    width: 60%;
    overflow: auto;
  }
  .feature__item .archive__item .archive__item-body .archive__item-title{
    padding-top: 0em;
    font-size: 0.8em;
    margin-top: 0em;
  }

  .feature__item .archive__item .archive__item-body .archive__item-excerpt{
    display: block;
    overflow: auto;
    font-size: 0.75em;
  }

  .feature__item .archive__item .archive__item-body .archive__item-excerpt p a::before{
    content: none;
  }

  .feature__item img {
    aspect-ratio: 1;
    object-fit: cover;
    object-position: top;
  }

  @media (min-width: 37.5em) {
    .feature__item {
      float: left;
      margin-bottom: 0;
      width: 32%; /* update depending on number of columns */
    }
  
    /* 4-column grid instead of 3-column */
    /* .feature__item:nth-child(3n + 1) {
      clear: none;
    }

    .feature__item:nth-child(4n + 1) {
      clear: both;
      margin-left: 0;
    }

    .feature__item:nth-child(4n + 2) {
      clear: none;
      margin-left:1.6949152542%
    }

    .feature__item:nth-child(4n + 3) {
        clear: none;
        margin-left:1.6949152542%
    } */

    .feature__item .feature__item-teaser {
      max-height: 200px;
      overflow: hidden
    }
  }
</style>

# About

The nanorobotics research group at IDSIA focuses its scientific effort on improving the onboard intelligence of ultra-constrained miniaturized robotic platforms aiming at the same capability as biological systems.
By leveraging Artificial Intelligence-based (AI) algorithms, some of the research areas encompass optimized ultra-low power embedded Cyber-Physical Systems (CPS), deep learning models for energy-efficient perception pipelines, multi-modal ultra-low power sensor fusion, Human-Robot Interaction (HRI) applications, and Cyber-secure systems for Microcontroller Units-class (MCUs).

Thanks to the close partnership with Parallelel Ultra-low Power international research project ([PULP Platform](https://pulp-platform.org/)), the nanorobotics group at IDSIA boasts strong collaborations with the ETH Zürich, the University of Bologna, and the Polytechnic University of Torino.

# People

{% include feature_row id="people" class="people_feature_row" %}

# News

<figure style="width: 30%" class="align-right"><img src="/files/iros23.png"></figure>
## Jun 21, 2023
Our new paper, "Sim-to-Real Vision-depth Fusion CNNs for Robust Pose Estimation Aboard Autonomous Nano-quadcopters," has just been accepted at [IROS'23](https://ieee-iros.org/). [arXiv preprint]() [demo-video](https://youtu.be/cxgk2rugLWA).

<figure style="width: 30%" class="align-right"><img src="/files/hotchips23.png"></figure>
## May 4, 2023
We contributed to the novel paper "Shaheen: An Open, Secure, and Scalable RV64 SoC for Autonomous Nano-UAVs," just accepted at [HotChips'23](https://hotchips.org/).

<figure style="width: 30%" class="align-right"><img src="/files/icra23.png"></figure>
## Jan 17, 2023
Two new papers have just been accepted at [ICRA'23](https://www.icra2023.org/). "Deep Neural Network Architecture Search for Accurate Visual Pose Estimation aboard Nano-UAVs," [arXiv preprint](https://arxiv.org/abs/2303.01931) [demo-video](https://youtu.be/dVCScckvcg8) and "Ultra-low Power Deep Learning-based Monocular Relative Localization Onboard Nano-quadrotors" [arXiv preprint](https://arxiv.org/abs/2303.01940) [demo-video](https://youtu.be/pUGL1qu3Z1k).

# Publications

## Deep Neural Network Architecture Search for Accurate Visual Pose Estimation aboard Nano-UAVs
E. Cereda, L. Crupi, M. Risso, A. Burrello, L. Benini, A. Giusti, D. Jahier Pagliari, and D. Palossi<br/>
_in Proceedings of the 2023 International Conference on Robotics and Automation (ICRA), 2023_

<div>
  <a href="{{'/assets/pdf/2023_icra_nas.pdf'| relative_url }}">
    <div class="csl-pdf"></div>
  </a>
  <a href="">
    <div class="csl-ieee"></div>
  </a>
  <a href="https://arxiv.org/abs/2303.01931">
    <div class="csl-arxiv"></div>
  </a>
  <style type="text/css">
    input[type='checkbox']:checked ~ #cereda2023deep-bibtex {
        display: block;
    }
    input[type='checkbox'] ~ #cereda2023deep-bibtex, #cereda2023deep-show {
        display: none;
    }
  </style>

  <input type="checkbox" id="cereda2023deep-show" />
  <div class="csl-bibtex"><label class="csl-label" for="cereda2023deep-show"><span /></label></div>
  <div id="cereda2023deep-bibtex">
<!-- careful, whitespace inside <pre> appears as-is on the page -->
<pre>@inproceedings{cereda2023deep,
  author={Cereda, Elia and Crupi, Luca and Risso, Matteo and Burrello, Alessio and Benini, Luca and Giusti, Alessandro and Pagliari, Daniele Jahier and Palossi, Daniele},
  booktitle={2023 International Conference on Robotics and Automation (ICRA)}, 
  title={Deep Neural Network Architecture Search for Accurate Visual Pose Estimation aboard Nano-UAVs}, 
  year={2023}
}</pre>
  </div>

  <details>
    <summary>Abstract</summary>
    <p>
    Miniaturized autonomous unmanned aerial vehicles (UAVs) are an emerging and trending topic. With their form factor as big as the palm of one hand, they can reach spots otherwise inaccessible to bigger robots and safely operate in human surroundings. The simple electronics aboard such robots (sub-100mW) make them particularly cheap and attractive but pose significant challenges in enabling onboard sophisticated intelligence. In this work, we leverage a novel neural architecture search (NAS) technique to automatically identify several Pareto-optimal convolutional neural networks (CNNs) for a visual pose estimation task. Our work demonstrates how real-life and field-tested robotics applications can concretely leverage NAS technologies to automatically and efficiently optimize CNNs for the specific hardware constraints of small UAVs. We deploy several NAS-optimized CNNs and run them in closed-loop aboard a 27-g Crazyflie nano-UAV equipped with a parallel ultra-low power System-on-Chip. Our results improve the State-of-the-Art by reducing the in-field control error of 32% while achieving a real-time onboard inference-rate of ~10Hz@10mW and ~50Hz@90mW.
    </p>
  </details>

  <iframe width="560" height="315" src="https://www.youtube.com/embed/dVCScckvcg8" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
</div>


## Ultra-low Power Deep Learning-based Monocular Relative Localization Onboard Nano-quadrotors
S. Bonato, S. C. Lambertenghi, E. Cereda, A. Giusti, and D. Palossi<br/>
_in Proceedings of the 2023 International Conference on Robotics and Automation (ICRA), 2023_

<div>
  <a href="{{'/assets/pdf/2023_icra_drone2drone.pdf'| relative_url }}">
    <div class="csl-pdf"></div>
  </a>
  <a href="">
    <div class="csl-ieee"></div>
  </a>
  <a href="https://arxiv.org/abs/2303.01940">
    <div class="csl-arxiv"></div>
  </a>
  <style type="text/css">
    input[type='checkbox']:checked ~ #bonato2023ultra-bibtex {
        display: block;
    }
    input[type='checkbox'] ~ #bonato2023ultra-bibtex, #bonato2023ultra-show {
        display: none;
    }
  </style>

  <input type="checkbox" id="bonato2023ultra-show" />
  <div class="csl-bibtex"><label class="csl-label" for="bonato2023ultra-show"><span /></label></div>
  <div id="bonato2023ultra-bibtex">
<!-- careful, whitespace inside <pre> appears as-is on the page -->
<pre>@inproceedings{bonato2023ultra,
  author={Bonato, Stefano and Lambertenghi, Stefano Carlo and Cereda, Elia and Giusti, Alessandro and Palossi, Daniele},
  booktitle={2023 International Conference on Robotics and Automation (ICRA)}, 
  title={Ultra-low Power Deep Learning-based Monocular Relative Localization Onboard Nano-quadrotors}, 
  year={2023}
}</pre>
  </div>

  <details>
    <summary>Abstract</summary>
    <p>
    Precise relative localization is a crucial functional block for swarm robotics. This work presents a novel autonomous end-to-end system that addresses the monocular relative localization, through deep neural networks (DNNs), of two peer nano-drones, i.e., sub-40g of weight and sub-100mW processing power. To cope with the ultra-constrained nano-drone platform, we propose a vertically-integrated framework, from the dataset collection to the final in-field deployment, including dataset augmentation, quantization, and system optimizations. Experimental results show that our DNN can precisely localize a 10cm-size target nano-drone by employing only low-resolution monochrome images, up to ~2m distance. On a disjoint testing dataset our model yields a mean R2 score of 0.42 and a root mean square error of 18cm, which results in a mean in-field prediction error of 15cm and in a closed-loop control error of 17cm, over a ~60s-flight test. Ultimately, the proposed system improves the State-of-the-Art by showing long-endurance tracking performance (up to 2min continuous tracking), generalization capabilities being deployed in a never-seen-before environment, and requiring a minimal power consumption of 95mW for an onboard real-time inference-rate of 48Hz.
    </p>
  </details>

  <iframe width="560" height="315" src="https://www.youtube.com/embed/pUGL1qu3Z1k" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
</div>


## Cyber Security aboard Micro Aerial Vehicles: An OpenTitan-based Visual Communication Use Case
M. Ciani, S. Bonato, R. Psiakis, A. Garofalo, L. Valente, S. Sugumar, A. Giusti, D. Rossi, and D. Palossi<br/>
_in Proceedings of the 2023 IEEE International Symposium on Circuits and Systems (ISCAS), 2023_

<div>
  <a href="{{'/assets/pdf/2023_iscas_opentitan_uvc.pdf'| relative_url }}">
    <div class="csl-pdf"></div>
  </a>
  <a href="">
    <div class="csl-ieee"></div>
  </a>
  <a href="https://arxiv.org/abs/2303.16554">
    <div class="csl-arxiv"></div>
  </a>
  <style type="text/css">
    input[type='checkbox']:checked ~ #ciani2023cyber-bibtex {
        display: block;
    }
    input[type='checkbox'] ~ #ciani2023cyber-bibtex, #ciani2023cyber-show {
        display: none;
    }
  </style>

  <input type="checkbox" id="ciani2023cyber-show" />
  <div class="csl-bibtex"><label class="csl-label" for="ciani2023cyber-show"><span /></label></div>
  <div id="ciani2023cyber-bibtex">
<!-- careful, whitespace inside <pre> appears as-is on the page -->
<pre>@inproceedings{ciani2023cyber,
  title={Cyber Security aboard Micro Aerial Vehicles: An OpenTitan-based Visual Communication Use Case},
  author={Ciani, Maicol and Bonato, Stefano and Psiakis, Rafail and Garofalo, Angelo and Valente, Luca and Sugumar, Suresh and Giusti, Alessandro and Rossi, Davide and Palossi, Daniele},
  booktitle={2023 International Symposium on Circuits and Systems (ISCAS)},
  year={2023}
}</pre>
  </div>

  <details>
    <summary>Abstract</summary>
    <p>
    Autonomous Micro Aerial Vehicles (MAVs), with a form factor of 10cm in diameter, are an emerging technology thanks to the broad applicability enabled by their onboard intelligence. However, these platforms are strongly limited in the onboard power envelope for processing, i.e., less than a few hundred mW, which confines the onboard processors to the class of simple microcontroller units (MCUs). These MCUs lack advanced security features opening the way to a wide range of cyber security vulnerabilities, from the communication between agents of the same fleet to the onboard execution of malicious code. This work presents an open-source System on Chip (SoC) design that integrates a 64 bit Linux capable host processor accelerated by an 8 core 32 bit parallel programmable accelerator. The heterogeneous system architecture is coupled with a security enclave based on an open-source OpenTitan root of trust. To demonstrate our design, we propose a use case where OpenTitan detects a security breach on the SoC aboard the MAV and drives its exclusive GPIOs to start a LED blinking routine. This procedure embodies an unconventional visual communication between two palm-sized MAVs: the receiver MAV classifies the LED state of the sender (on or off) with an onboard convolutional neural network running on the parallel accelerator. Then, it reconstructs a high-level message in 1.3s, 2.3 times faster than current commercial solutions.
    </p>
  </details>

  <iframe width="560" height="315" src="https://www.youtube.com/embed/TClcuUWJe0U" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
</div>


## Handling Pitch Variations for Visual Perception in MAVs: Synthetic Augmentation and State Fusion

E. Cereda, D. Palossi, and A. Giusti<br/>
_in Proceedings of the 13th International Micro Air Vehicle Conference, pp. 59–65, 2022_

<div>
  <a href="{{'/assets/pdf/2022_imav_pitch_augmentation.pdf'| relative_url }}">
    <div class="csl-pdf"></div>
  </a>
  <a href="https://www.imavs.org/tag/imav2022/">
    <div class="csl-doi"></div>
  </a>
  <style type="text/css">
    input[type='checkbox']:checked ~ #cereda2022handling-bibtex {
        display: block;
    }
    input[type='checkbox'] ~ #cereda2022handling-bibtex, #cereda2022handling-show {
        display: none;
    }
  </style>

  <input type="checkbox" id="cereda2022handling-show" />
  <div class="csl-bibtex"><label class="csl-label" for="cereda2022handling-show"><span /></label></div>
  <div id="cereda2022handling-bibtex">
<!-- careful, whitespace inside <pre> appears as-is on the page -->
<pre>@inproceedings{cereda2022handling,
author = {Elia Cereda and Daniele Palossi and Alessandro Giusti},
editor = {G. de Croon and C. De Wagter},
title = {Handling Pitch Variations for Visual Perception in MAVs: Synthetic Augmentation and State Fusion},
year = {2022},
month = {Sep},
day = {12-16},
booktitle = {13$^{th}$ International Micro Air Vehicle Conference},
address = {Delft, the Netherlands},
pages = {59--65}
}</pre>
  </div>

  <details>
    <summary>Abstract</summary>
    <p>
    Variations in the pitch of a Micro Aerial Vehicle affect the geometry of the images acquired by its on-board cameras. We propose and evaluate two orthogonal approaches to handle this source of variability, in the context of visual perception using Convolutional Neural Networks. The first is a training data augmentation method that generates synthetic images simulating a different pitch than the one at which the original training image was acquired; the second is a neural network architecture that takes the drone’s estimated pitch as an auxiliary input. Real-robot quantitative experiments tackle the task of visually estimating the pose of a human from a nearby nanoquadrotor; in this context, the two proposed approaches yield significant performance improvements, up to +0.15 in the R2 regression score when applied together.
    </p>
  </details>

</div>


## A Deep Learning-Based Face Mask Detector for Autonomous Nano-Drones

E. AlNuaimi, E. Cereda, R. Psiakis, S. Sugumar, A. Giusti, and D. Palossi<br/>
_in Proceedings of the AAAI Conference on Artificial Intelligence, vol. 36, no. 11, pp. 12903-12904, 2022_

<div>
  <a href="{{'/assets/pdf/2022_aaai_student_abstract.pdf'| relative_url }}">
    <div class="csl-pdf"></div>
  </a>
  <a href="https://ojs.aaai.org/index.php/AAAI/article/view/21588">
    <div class="csl-doi"></div>
  </a>
  <style type="text/css">
    input[type='checkbox']:checked ~ #alnuaimi2022deep-bibtex {
        display: block;
    }
    input[type='checkbox'] ~ #alnuaimi2022deep-bibtex, #alnuaimi2022deep-show {
        display: none;
    }
  </style>

  <input type="checkbox" id="alnuaimi2022deep-show" />
  <div class="csl-bibtex"><label class="csl-label" for="alnuaimi2022deep-show"><span /></label></div>
  <div id="alnuaimi2022deep-bibtex">
<!-- careful, whitespace inside <pre> appears as-is on the page -->
<pre>@inproceedings{alnuaimi2022deep,
  title={A Deep Learning-Based Face Mask Detector for Autonomous Nano-Drones (Student Abstract)},
  author={AlNuaimi, Eiman and Cereda, Elia and Psiakis, Rafail and Sugumar, Suresh and Giusti, Alessandro and Palossi, Daniele},
  booktitle={Proceedings of the AAAI Conference on Artificial Intelligence},
  volume={36},
  number={11},
  pages={12903--12904},
  year={2022}
}</pre>
  </div>

  <details>
    <summary>Abstract</summary>
    <p>
   We present a deep neural network (DNN) for visually classifying whether a person is wearing a protective face mask. Our DNN can be deployed on a resource-limited, sub-10-cm nano-drone: this robotic platform is an ideal candidate to fly in human proximity and perform ubiquitous visual perception safely. This paper describes our pipeline, starting from the dataset collection; the selection and training of a full-precision (i.e., float32) DNN; a quantization phase (i.e., int8), enabling the DNN's deployment on a parallel ultra-low power (PULP) system-on-chip aboard our target nano-drone. Results demonstrate the efficacy of our pipeline with a mean area under the ROC curve score of 0.81, which drops by only ~2% when quantized to 8-bit for deployment.
    </p>
  </details>

</div>


## Improving the Generalization Capability of DNNs for Ultra-low Power Autonomous Nano-UAVs

E. Cereda, M. Ferri, D. Mantegazza, N. Zimmerman, L. M. Gambardella, J. Guzzi, A. Giusti, and D. Palossi<br/>
_in 2021 17th IEEE International Conference on Distributed Computing in Sensor Systems (DCOSS), pp. 327-334, 2021_

<div>
  <a href="{{'/assets/pdf/2021_dcoss_domain_randomization.pdf'| relative_url }}">
    <div class="csl-pdf"></div>
  </a>
  <a href="https://ieeexplore.ieee.org/abstract/document/9600024">
    <div class="csl-ieee"></div>
  </a>
  <a href="https://arxiv.org/abs/2110.14491">
    <div class="csl-arxiv"></div>
  </a>
  <style type="text/css">
    input[type='checkbox']:checked ~ #cereda2021improving-bibtex {
        display: block;
    }
    input[type='checkbox'] ~ #cereda2021improving-bibtex, #cereda2021improving-show {
        display: none;
    }
  </style>

  <input type="checkbox" id="cereda2021improving-show" />
  <div class="csl-bibtex"><label class="csl-label" for="cereda2021improving-show"><span /></label></div>
  <div id="cereda2021improving-bibtex">
<!-- careful, whitespace inside <pre> appears as-is on the page -->
<pre>@inproceedings{cereda2021improving,
  title={Improving the generalization capability of DNNs for ultra-low power autonomous nano-UAVs},
  author={Cereda, Elia and Ferri, Marco and Mantegazza, Dario and Zimmerman, Nicky and Gambardella, Luca M and Guzzi, J{\'e}r{\^o}me and Giusti, Alessandro and Palossi, Daniele},
  booktitle={2021 17th International Conference on Distributed Computing in Sensor Systems (DCOSS)},
  pages={327--334},
  year={2021},
  organization={IEEE}
}</pre>
  </div>

  <details>
    <summary>Abstract</summary>
    <p>
    Deep neural networks (DNNs) are becoming the first-class solution for autonomous unmanned aerial vehicles (UAVs) applications, especially for tiny, resource-constrained, nano-UAVs, with a few tens of grams in weight and subten centimeters in diameter. DNN visual pipelines have been proven capable of delivering high intelligence aboard nanoUAVs, efficiently exploiting novel multi-core microcontroller units. However, one severe limitation of this class of solutions is the generalization challenge, i.e., the visual cues learned on the specific training domain hardly predict with the same accuracy on different ones. Ultimately, it results in very limited applicability of State-of-the-Art (SoA) autonomous navigation DNNs outside controlled environments. In this work, we tackle this problem in the context of the human pose estimation task with a SoA vision-based DNN [1]. We propose a novel methodology that leverages synthetic domain randomization by applying a simple but effective image background replacement technique to augment our training dataset. Our results demonstrate how the augmentation forces the learning process to focus on what matters most: the pose of the human subject. Our approach reduces the DNN’s mean square error — vs. a non-augmented baseline — by up to 40%, on a never-seen-before testing environment. Since our methodology tackles the DNN’s training stage, the improved generalization capabilities come at zero-cost for the computational/memory burdens aboard the nano-UAV.
    </p>
  </details>

</div>


## Fully Onboard AI-powered Human-drone Pose Estimation on Ultra-low-power Autonomous Flying Nano-UAVs

D. Palossi, N. Zimmerman, A. Burrello, F. Conti, H. Müller, L. M. Gambardella, L. Benini, A. Giusti, and J. Guzzi<br/>
_in IEEE Internet of Things Journal, vol. 9, no. 3, pp. 1913-1929, 2021_

<div>
  <a href="{{'/assets/pdf/2021_iotj_pulp_frontnet.pdf'| relative_url }}">
    <div class="csl-pdf"></div>
  </a>
  <a href="https://ieeexplore.ieee.org/abstract/document/9462495">
    <div class="csl-ieee"></div>
  </a>
  <a href="https://arxiv.org/abs/2103.10873">
    <div class="csl-arxiv"></div>
  </a>
  <a href="https://github.com/idsia-robotics/pulp-frontnet">
    <div class="csl-github"></div>
  </a>
  <style type="text/css">
    input[type='checkbox']:checked ~ #palossi2021fully-bibtex {
        display: block;
    }
    input[type='checkbox'] ~ #palossi2021fully-bibtex, #palossi2021fully-show {
        display: none;
    }
  </style>

  <input type="checkbox" id="palossi2021fully-show" />
  <div class="csl-bibtex"><label class="csl-label" for="palossi2021fully-show"><span /></label></div>
  <div id="palossi2021fully-bibtex">
<!-- careful, whitespace inside <pre> appears as-is on the page -->
<pre>@article{palossi2021fully,
    title={Fully onboard ai-powered human-drone pose estimation on ultralow-power autonomous flying nano-uavs},
    author={Palossi, Daniele and Zimmerman, Nicky and Burrello, Alessio and Conti, Francesco and M{\"u}ller, Hanna and Gambardella, Luca Maria and Benini, Luca and Giusti, Alessandro and Guzzi, J{\'e}r{\^o}me},
    journal={IEEE Internet of Things Journal},
    volume={9},
    number={3},
    pages={1913--1929},
    year={2021},
    publisher={IEEE}
}</pre>
  </div>

  <details>
    <summary>Abstract</summary>
    <p>
    Many emerging applications of nano-sized unmanned aerial vehicles (UAVs), with a few cm2 form-factor, revolve around safely interacting with humans in complex scenarios, for example, monitoring their activities or looking after people needing care. Such sophisticated autonomous functionality must be achieved while dealing with severe constraints in payload, battery, and power budget (~100mW). In this work, we attack a complex task going from perception to control: to estimate and maintain the nano-UAV’s relative 3-D pose with respect to a person while they freely move in the environment—a task that, to the best of our knowledge, has never previously been targeted with fully onboard computation on a nano-sized UAV. Our approach is centered around a novel vision-based deep neural network (DNN), called Frontnet, designed for deployment on top of a parallel ultra-low power (PULP) processor aboard a nano-UAV. We present a vertically integrated approach starting from the DNN model design, training, and dataset augmentation down to 8-bit quantization and deployment in-field. PULP-Frontnet can operate in real-time (up to 135 frame/s), consuming less than 87 mW for processing at peak throughput and down to 0.43 mJ/frame in the most energy-efficient operating point. Field experiments demonstrate a closed-loop top-notch autonomous navigation capability, with a tiny 27-g Crazyflie 2.1 nano-UAV. Compared against an ideal sensing setup, onboard pose inference yields excellent drone behavior in terms of median absolute errors, such as positional (onboard: 41cm, ideal: 26 cm) and angular (onboard: 3.7°, ideal: 4.1°). We publicly release videos and the source code of our work.
    </p>
  </details>

  <iframe width="560" height="315" src="https://www.youtube.com/embed/_kmDDYoNA3g" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
</div>
