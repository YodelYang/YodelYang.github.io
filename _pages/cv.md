---
layout: archive
title: "Deyang Wang"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

- **Phone:** (+86) 18130768920 | **Email:** [deyangwang@bjtu.edu.cn](mailto:deyangwang@bjtu.edu.cn) | **Website:** [deyangwang.github.io](https://yodelyang.github.io/)

# Education

## Beijing Jiaotong University | Undergraduate  
**Bachelor of Engineering** in Computer Science and Technology, School of Computer Science and Technology  
*September 2021 – June 2025 (Expected)*  

- **Weighted Average Score:** 87.1/100.0 (Top 25% of the major)
- **Competition Awards:**
  - Second Prize in C/C++ Programming, Blue Bridge Cup, 15th Provincial Software Competition (University A Group)
  - Second Prize in Beijing Jiaotong University Programming Competition
  - Third Prize in C/C++ Programming, Blue Bridge Cup, 14th Provincial Software Competition (University A Group)
- **Honors and Scholarships:**
  - Second-Class Scholarship (2021-2022) (Top 10%)
  - "Three Good Student" Award (2021-2022) (Top 20%)
- **Relevant Courses:**
  - C Programming (95), Comprehensive Training in Computational Thinking (A), Python Programming Practice (A), Object-Oriented Programming and C++ (93), Machine Learning (92), Software Engineering (90), Compiler Principles (94), Computer Networks (91)

## Beijing Jiaotong University | Graduate  
**Master's in Artificial Intelligence** (Professional Master's Degree), School of Computer Science and Technology  
*September 2025 (Expected) – June 2028 (Expected)*

# Technical Skills

- **Programming Languages:** Proficient in C/C++; Familiar with Python; Basic knowledge of Java
- **Workflow Tools:** Proficient in Linux, Shell scripting, Git, and GitHub
- **Languages:** CET-6: 509, CET-4: 621, IELTS: 6.5
- **Technological Stack:** Libtorch, ONNX, Eigen, HTML, MySQL, Flask, Mace, Hexagon DSP, etc.

# Project Experience

## Research on Batch Inference Acceleration Method for Convolution on CPU Platforms  
*University Innovation and Entrepreneurship Training Program*  
&nbsp; \hfill  *April 2023 – May 2024*  
- Focused on improving the batch processing of convolution and pooling operations to reduce cache misses and improve CPU computational efficiency.
- Designed and implemented a new **Batched Data Layout Optimization (BDLO)** scheme, which optimized data layout and transformed multi-matrix computations into single-matrix and kernel calculations, reducing memory accesses.
- Integrated the BDLO rearrangement into other operators in batch processing (e.g., Batch Normalization and Pooling), reducing performance overhead from separate rearrangement steps.
- Tested using the Libtorch framework and Eigen acceleration libraries, with ablation experiments showing an **acceleration of up to 1.28x**.
- **Project awarded as a Beijing-level University Innovation and Entrepreneurship Training Program**.
- Related research paper submitted: **"BDLO: Batched-Data-Layout-Optimization Method for Batched Im2col-based Convolution on CPUs"**.

## Deployment and Optimization of Inference Engine on cDSP Platform  
*Collaboration with NIO Inc.*  
&nbsp; \hfill  *February 2023 – May 2024*  
- Deployed deep neural network models on NIO's in-vehicle chips (cDSP module) for use in the vehicle's voice system, optimizing the model for over a **40% reduction in inference time**.
- Analyzed the operators and architecture of the HiFi-GAN model, evaluating performance on different platforms using tools like ONNX.
- Used and modified the open-source MACE mobile framework to deploy the HiFi-GAN model on Snapdragon DSP modules.
- Quantified model weights to int8 and employed optimization techniques such as operator fusion, reducing inference time by **up to 1.5x** for Transformer models.

## Zero-shot Driven Interactive Video Stream Object Removal  
*Professional Practice and Training Course Development Project*  
&nbsp; \hfill  *June 2023 – August 2023*  
- Developed an automated system for object removal and restoration in video streams, reducing manual intervention and ensuring natural restoration results.
- Combined advanced **automatic segmentation (SAM), mask propagation (AOT), and video restoration (E2FGVI)** techniques into an efficient, automated pipeline for object removal and repair.
- Demonstrated the effectiveness of the system through various experiments, showcasing superior performance across different video materials.

# Personal Summary

- **Personality:** Optimistic and open-minded with a strong foundation in computer science and technology, excelling in self-driven problem-solving and effective team collaboration.
- **Skills:** Familiar with Linux and essential development tools, with substantial project experience. Adept at applying technology to solve real-world problems.
- **Research Interests:** In-depth knowledge in deep learning, computer vision, and model optimization, demonstrating strong learning capabilities to quickly master and apply new knowledge to projects.

