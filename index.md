---
layout: splash
title: Nanorobotics Group
header:
  image: /assets/images/header.jpg
people:
  - image_path: https://idsia-robotics.github.io/assets/images/daniele_palossi.png
    alt: Dr. Daniele Palossi
    title: Dr. Daniele Palossi
    excerpt: 'Group Leader<br/> [Webpage](https://scholar.google.ch/citations?user=5v_dElkAAAAJ)'
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

Thanks to the close partnership with Parallelel Ultra-low Power international research project ([PULP Platform](https://pulp-platform.org/)), the nanorobotic group at IDSIA boasts strong collaborations with the ETH Zürich, the University of Bologna, and the Polytechnic University of Torino.

# People

{% include feature_row id="people" class="people_feature_row" %}
  
# Publications

## Handling Pitch Variations for Visual Perception in MAVs: Synthetic Augmentation and State Fusion

E. Cereda, D. Palossi, and A. Giusti<br/>
_in Proceedings of the 13th International Micro Air Vehicle Conference, pp. 59–65, 2022_

<div>
  <a href="{{'/assets/pdf/2022_imav_pitch_augmentation.pdf'| relative_url }}">
    <div class="csl-pdf"></div>
  </a>
  <a href="https://www.imavs.org/tag/imav2022/">
    <div class="csl-doi">DOI</div>
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
pages = {59--65},
note = {Paper no. IMAV2022-7}
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
    <div class="csl-ieee"></div>
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
