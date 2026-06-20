---
title: "nanoPMC"
collection: archive
author_profile: true
permalink: /nanopmc/
venue: "nanoDC Lab, IIT Gandhinagar, Electrical Engineering Department"
---



**nanoPMC** is an open-source, GPU-accelerated particle Monte Carlo (PMC) simulator developed for feature-scale semiconductor process modeling. Written in modern C++, nanoPMC enables efficient simulation of particle transport and surface interactions in advanced plasma etching and deposition processes, providing high-fidelity process profile prediction with significantly reduced computational cost.  

The motivation behind nanoPMC stems from challenges encountered during my Ph.D. research. While process simulation plays a critical role in semiconductor technology development, access to advanced simulation tools remains limited. Most process simulation platforms are proprietary, developed and maintained within industry, while commercially available tools are often expensive and subject to export-control restrictions. As a result, academic researchers frequently face significant barriers to entering and contributing to the field.

This lack of accessibility has contributed to a fragmented process simulation ecosystem and comparatively fewer open academic contributions than in device simulation, circuit design, or machine learning. nanoPMC was conceived to help address this gap by providing an open, transparent, and extensible platform for semiconductor process modeling.

Our goal is to develop a simulation framework that is not only physically meaningful and computationally efficient, but also accessible to students, researchers, and educators worldwide. By leveraging modern GPU acceleration, nanoPMC is designed to run efficiently on consumer-grade hardware, including laptops equipped with modest GPUs, eliminating the need for expensive computing infrastructure. We hope this effort lowers the barrier to entry for process simulation research and fosters a broader open-source community around semiconductor manufacturing technologies.



The development of nanoPMC is being led by **[nanoDC Lab](https://in.linkedin.com/company/nanodc-lab)**, Department of Electrical Engineering, IIT Gandhinagar, with the goal of providing an open, scalable, and extensible platform for semiconductor process simulation and research.  

The project is currently under active development, with a public release planned soon. Stay tuned for documentation, source code, examples, and tutorials.  

In parallel, we are also developing *ComputPlasma*, an integrated plasma reactor modeling framework. Together, *ComputPlasma* and *nanoPMC* will form *ComputProcess*, an end-to-end multiscale simulation platform that seamlessly bridges reactor-scale plasma dynamics and feature-scale process evolution.  

nanoPMC contributors: Om Maheshwari (Ph.D. IIT Gandhinagar), Rudra Choubey (B.Tech, IIT Gandhinagar)  
computPlasma contributors: Siddharth Mohanty(Ph.D., IIT Gandhinagar), Om Maheshwari (Ph.D., IIT Gandhinagar), Sandeep Swain (M.Sc., IIT Gandhinagar), Rudra Choubey (B.Tech, IIT Gandhinagar)

## Glimpses
Some glimpses of the Version2 (C++ based with GUI) of nanoPMC: 

<p align="center">
  <img src="/images/glimpse1.webp" width="100%">  
  
  <img src="/images/glimpse2.webp" width="20%">
  <!-- <img src="/assets/images/nanopmc3.png" width="30%"> -->
</p>

Version1:  
<p align="center">
  <video width="600" autoplay loop muted playsinline>
    <source src="/images/nsfet.mp4" type="video/mp4">
  </video>
</p>

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



