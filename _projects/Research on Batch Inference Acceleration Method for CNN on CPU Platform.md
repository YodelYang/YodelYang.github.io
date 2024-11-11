---
title: "Research on Batch Inference Acceleration Method for CNN on CPU Platform"
layout: project
collection: projects
permalink: /project/cnn-cpu-batch-inference
excerpt: "This project focuses on improving batch processing flow for convolution and pooling operations in CNN, reducing Cache Miss rate, and enhancing CPU computational efficiency."
date: 2023-04-01
# link: 'http://example.com/project-link'
---

### Project Details

This project addresses the long reuse distance problem in current batch processing methods, aiming to reduce Cache Miss rates and improve CPU efficiency in convolutional neural networks. A new **Batched Data Layout Optimization (BDLO)** scheme was designed and implemented to redefine data layout, minimizing memory access. The BDLO operation was embedded within other batch operators, reducing overhead, and achieving up to a **1.28x acceleration** using Libtorch and Eigen libraries. This project has been awarded as a Beijing-level student innovation project, and the research results have been submitted as **“BDLO: Batched-Data-Layout-Optimization Method for Batched Im2col-based Convolution on CPUs”**.
