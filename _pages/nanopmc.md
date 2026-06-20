---
title: "nanoPMC"
collection: archive
author_profile: true
permalink: /nanopmc/
venue: "nanoDC Lab, IIT Gandhinagar, Electrical Engineering Department"
---

**nanoPMC** is a part of *ComputProcess*, an open-source initiative aimed at developing an end-to-end semiconductor process simulation framework that bridges reactor-scale plasma modeling and feature-scale process evolution. The vision is to create an accessible, transparent, and extensible platform for semiconductor process research and education.

As part of this effort, **nanoPMC** serves as the feature-scale simulation engine, providing GPU-accelerated particle Monte Carlo modeling of particle transport and surface interactions in advanced plasma etching and deposition processes. Written in modern C++, nanoPMC enables efficient simulation of particle transport and surface interactions in advanced plasma etching and deposition processes, providing high-fidelity process profile prediction with significantly reduced computational cost.  

*ComputProcess* (and as an extension, nanoPMC) was inspired by challenges I faced during my Ph.D., where access to semiconductor process simulation tools was often limited by cost, proprietary licensing, or export restrictions. Through *ComputProcess*, we aim to make process simulation more accessible by developing a fast, lightweight, and open-source platform that can run efficiently on everyday hardware, enabling more researchers and students to contribute to this field.

With *ComputProcess*, we aim to build a fast, lightweight, and open-source simulation platform that can run efficiently even on consumer-grade GPUs. Our hope is to lower the barrier to entry and enable more students and researchers to explore, learn, and contribute to semiconductor process modeling.

The development of nanoPMC is being led by **[nanoDC Lab](https://in.linkedin.com/company/nanodc-lab)**, Department of Electrical Engineering, IIT Gandhinagar, with the goal of providing an open, scalable, and extensible platform for semiconductor process simulation and research.  

The project is currently under active development, with a public release planned soon. Stay tuned for documentation, source code, examples, and tutorials.  

nanoPMC contributors: Om Maheshwari (Ph.D. IIT Gandhinagar), Rudra Choubey (B.Tech, IIT Gandhinagar)  
computPlasma contributors: Siddharth Mohanty (Ph.D., IIT Gandhinagar), Om Maheshwari (Ph.D., IIT Gandhinagar), Sandeep Swain (M.Sc., IIT Gandhinagar), Rudra Choubey (B.Tech, IIT Gandhinagar)

## Glimpses
Some glimpses of the Version2 (C++ based with GUI) of nanoPMC: 

- nanoPMC interface
  
<p align="center">
  <img src="/images/glimpse1.webp" width="100%">  

- A 3D NAND pillar etch example in nanoPMC
  
  <img src="/images/glimpse2.webp" width="20%">
  <!-- <img src="/assets/images/nanopmc3.png" width="30%"> -->
</p>

Version1 (pytorch based script):  

- Inner spacer etch simulation  
<p align="center">
  <video width="600" autoplay loop muted playsinline>
    <source src="/images/nsfet.mp4" type="video/mp4">
  </video>
</p>

- Generic ionic etch simulation  

<p align="center">
  <video width="600" autoplay loop muted playsinline>
    <source src="/images/radicals.mp4" type="video/mp4">
  </video>
</p>


## Relevant Publications

- **Om Maheshwari, P. Kumar, S. Barai, and N. Mohapatra**,  
  "*nanoPMC: A GPU-Accelerated Particle Monte Carlo Simulator for Feature-Scale Semiconductor Process Modeling*,"  
  IMECE India, 2025. DOI: 10.1115/IMECE-INDIA2025-160835.

- **S. Mohanty, S. K. Swain, Om Maheshwari, P. Kumar, and N. Mohapatra**,  
  "*ComputPlasma: A Coupled Bulk and Sheath Plasma Reactor Model for Semiconductor Process Modeling*,"  
  IEEE ICEE, 2025.



