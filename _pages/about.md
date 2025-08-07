---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# 👤 Short Bio

<!-- ***Jiayi Wu*** is a member of the [RoboPI](https://robopi.ece.ufl.edu/people.html#Grad) lab, he is a master’s student(thesis) in ECE Department of the University of Florida. His research focus is on low-cost 3D reconstruction and depth estimation in scattering medium. He is currently working on wraping up his master thesis project under the supervision of Prof. Islam. The primaly research goal of his thesis is to formulate a fast and robust underwater 3D reconstruction algorithm based on the fusion of SfM algorithm and deep learning. He is also collaboraing with other students across the lab to make it lightweight and deployable on low-power robotic systems. -->

Hi! Welcome to my website. I'm E. Baker Herrin, ML & Robotics Engineer.

My career interests are in deep learning, embedded/edge devices, robotics software (and their intersection).

## Skills
-  Python, Embedded C, C++, MATLAB, VHDL, ARM assembly, LABVIEW/Teststand
-  Transformers, CNNs, Neural Radiance Fields (NeRF), Gaussian Splatting (deployed on
NVIDIA GPUs)
- PyTorch, Tensorflow, Git, MMDetection3D, Ubuntu Linux, ROS2, Gazebo,
IsaacSim, Blender, Altium

<!-- Add back links when updated -->

[***Latest CV link***](/pdf/Herrin_CV-4.pdf)

[***Latest Resume link***](/pdf/Herrin_Resume.pdf)

<!-- # 📰 News
04/16/2025: Presented our work "Lessons from RAITE: Real-World Evaluation of Robust
Multi-Modal Target Detection and Tracking Under
Adversarial Attacks" at SPIE Defense + Commercial Sensing Conference in Orlando, FL

03/01/2025: Submitted our work "Action Recognition for Underwater Gesture Communication in Human
Diver and Robot Teaming" to IROS 2025 for review

11/17/2024: Released YouTube a 30 minute explainer seminar on Radiance Fields (Neural Radiance Fields and Gaussian Splatting) https://www.youtube.com/watch?v=ilQt81cONXE&t=1749s

10/25/24: Competed in NSWC Crane Division's Robust AI Test event Scenario 2 in Muscatatuck, IN

07/08/2024: Started internship at Texas Instruments in Dallas working on BEVFusion 3D object detection

05/15/2024: Started working on 3D-change detection with Neural Radiance Fields at the UF Research Engineering and Education Facility (REEF) 
-->

# 🎓 Education

 <!-- supervised by [Prof. Jane Shin](https://mae.ufl.edu/people/faculty/primary/profiles/jane-jaejeong-shin/) in the [APRILab (Active Perception and Robot Intelligence Lab)](https://janeshin-website.github.io/), [University of Florida, Gainesville](https://www.ufl.edu/). -->

><a href="https://www.ece.ufl.edu/"><img class="svg" src="/images/UFL_logo.png" width="45pt"></a>  ***University of Florida***
>>- ***M.S. in Mechanical Engineering*** --------- *Aug. 2022- Dec 2024*  
Supervised by [Prof. Jane Shin](https://mae.ufl.edu/people/name/jane-jaejeong-shin/).

><a href="https://www.ece.ufl.edu/"><img class="svg" src="/images/UFL_logo.png" width="45pt"></a>  ***University of Florida***
>>- ***B.S in Electrical and Computer Engineering*** --------- *June. 2017- Dec 2021*  


# 📃 Projects 

## Robust Underwater Robots
<!--
Describe all works related to developing autonomous robots
-->
Developing deployable underwater robots for tasks such as:
- Mapping with Gaussian Splatting (3DGS) and Neural Radiance Fields (NeRF)
- Collaborative diver-robot teaming

### Relevant Publications
- Z. Zhang, E. Baker Herrin, et al., “Action Recognition for Underwater Gesture Communication in Human Diver and
Robot Teaming,” in Proc. IEEE/RSJ Int. Conf. on Intelligent Robots and Systems (IROS), 2025. (accepted)

- E. Baker Herrin, et. al, “SGD11: A Diver Gesture Recognition Dataset for Underwater Human-Robot Collaboration,”
in Proc. ICRA 2025 AQ2UASIM Workshop, Atlanta, GA, USA, May 2025.

- E. Baker Herrin, et. al, “Modularis: Modular Underwater Robot for Rapid Development and Validation of
Autonomous Systems,” in Proc. OCEANS 2023 Gulf Coast, Biloxi, MS, USA, Sep. 2023.
https://doi.org/10.23919/OCEANS52994.2023.10337059 Presented by author.

<div class="paper-row">

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <!-- <div class="badge">A Collaborative Project</div> -->
      <img src='images/deployment_br2.png' alt="deployment" width="100%">
    </div>
  </div>
  <!-- <div class='paper-box-text' markdown="1">
    Field deployment of BlueROV2 collecting data for mapping.
  </div> -->
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <!-- <div class="badge">A Collaborative Project</div> -->
      <img src='images/tinkering_br2.jpg' alt="tinkering" width="100%">
    </div>
  </div>
  <!-- <div class='paper-box-text' markdown="1">
    Lab testing and debugging of perception stack on embedded hardware.
  </div> -->
</div>

</div>

<!-- ## Robust Target Tracking and situational awareness -->

<!-- E. Baker Herrin, “Lessons from RAITE: Real-World Evaluation of Robust Multi-Modal Target Detection and
Tracking Under Adversarial Attacks,” in Proc. SPIE Defense + Commercial Sensing, Orlando, FL, USA, Apr. 2025.
Presented by author. -->

<!-- 
### UDepth
- A monocular underwater depth estimation pipeline, using RMI as the input space, constructs a lightweight domain projection module, a lightweight CNN feature extraction module, and a lightweight Transformer-based depth estimation network. And the depth estimation network is supervised with knowledge of underwater light attenuation as a prior. The results show that our depth estimation accuracy is close to the SOTA model, and much faster than them.  
This is a collaborative project on underwater depth estimation with Boxiao Yu, a Ph.D. student in RoboPI lab.  
[[IEEE Xplore]](https://ieeexplore.ieee.org/abstract/document/10161471) [[arXiv]](https://arxiv.org/abs/2209.12358) [[Code]](https://github.com/uf-robopi/UDepth) [[pre-print]](/pdf/2209.12358.pdf)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Master's Thesis</div><img src='images/FU-SfM_project.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

### SDU-SfM
- A fast depth-guided semi-dense underwater 3D reconstruction pipeline without a deep learning model. Underwater image restoration is implemented through RMI channel and underwater imaging model to improve the number of feature matches. Reduce the computational complexity of feature extraction by using the depth map as a mask. In order to achieve higher quality(semi-dense) underwater 3D reconstruction, the depth maps are used as the supervision to refine the 3D point cloud and remove noise.  
This project is my master's thesis, we have submitted a journal to the IEEE Transactions on Artificial Intelligence (TAI). Here is the [video demo](https://youtu.be/roiOpPyAvZ0).  

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">R&D Internship Project</div><img src='images/infringing_video_retrieval_project.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

### Learning-based Infringing Video Retrieval
- An learning-based infringing video retrieval system based on the fusion of global features and local features. I did a summer internship in the Vobile’s R&D department under the supervision of Dr. Zhao, CTO of Vobile. I built a learning-based infringing video retrieval system based on the fusion of global features and local features. I used Vobile's video database to train the model, and achieved good performance. Before I ended my internship, I put it together into a python package and organize each component in the system into an easy-to-use python toolkit. I also wrote the manual of the package and a document about future optimization steps to finally handed over to the person who took over the project.  

</div>
</div> -->

# 🏭 Job Experience

- ***Graduate Research Assistant - AI/Robotics*** --------- *August. 2022- June 2025*  
Active Perception and Robot Intelligence Lab (APRILab) at University of Florida, Gainesville, FL, United States.

- ***Applications Engineering Intern - 3D Perception*** --------- *July. 2024- August 2024*  
Embedded Processing, Jacinto Software Applications at Texas Instruments, Dallas, TX, United States.

- ***Research Intern - 3D Change Detection*** --------- *May. 2024- July 2024*  
3D Change Detection at UF REEF, Ft. Walton, FL, United States.

- ***Validation Engineering Intern - Transcievers*** --------- *May. 2023- August 2023*  
Analog Signal Chain, Transcievers validation at Texas Instruments, Dallas, TX, United States.

- ***Validation Engineering Intern - Transcievers*** --------- *May. 2022- August 2022*  
Analog Signal Chain, Transcievers validation at Texas Instruments, Dallas, TX, United States.

- ***Teaching Assistant - Analog Circuits*** --------- *August. 2019- May 2022*  
EEL311C Laboratory Instructor at University of Florida, Gainesville, FL, United States.

<!-- # 📝 Publications  -->

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CAI 2023 (Best Paper Award)</div><img src='images/SDU_SfM.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

-	`Wu, Jiayi`, Yu, Boxiao, Islam, Md Jahidul. ***3D Reconstruction of Underwater Scenes using Nonlinear Domain Projection***. *IEEE CAI (Best Paper Award)*. 2023  
[[IEEE Xplore]](https://ieeexplore.ieee.org/document/10195131) [[Poster]](https://robopi.ece.ufl.edu/files/pubs/sdu_sfm.pdf) [[Video demo]](https://youtu.be/roiOpPyAvZ0)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2023 (has been accepted)</div><img src='images/udepth.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

-	Yu, Boxiao, `Wu, Jiayi`, Islam, Md Jahidul. ***UDepth: Fast Monocular Depth Estimation for Visually-guided Underwater Robots***. *ICRA*. 2023, pp. 3116-3123, doi: 10.1109/ICRA48891.2023.10161471.  
[[IEEE Xplore]](https://ieeexplore.ieee.org/abstract/document/10161471) [[arXiv]](https://arxiv.org/abs/2209.12358) [[Code]](https://github.com/uf-robopi/UDepth) [[pre-print]](/pdf/2209.12358.pdf)

</div>
</div>

-	A. Kaleo Roberts, Kamal Sarabandi, Jasmeet Judge, Alejandro Monsivais-Huertero, `Jiayi Wu`. ***VALIDATION OF A FULL-WAVE BACKSCATTER MODEL FOR CORN FIELDS USING MEASUREMENTS FROM A GROUND-BASED SCATTEROMETER***. *IGARSS*. 2023   -->

## ✍️ Blog & Thoughts
I occasionally share technical insights and creative writing. 
[Browse all posts](/blog/){: .btn .btn--primary}

Recent posts:
{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url }}) ({{ post.date | date: "%b %Y" }})
{% endfor %}