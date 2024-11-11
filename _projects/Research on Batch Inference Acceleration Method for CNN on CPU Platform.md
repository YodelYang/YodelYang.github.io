---
title: "Research on Batch Inference Acceleration Method for CNN on CPU Platform"
layout: project
collection: projects
permalink: /project/cnn-cpu-batch-inference
excerpt: "This project focuses on improving batch processing flow for convolution and pooling operations in CNN, reducing Cache Miss rate, and enhancing CPU computational efficiency."
date: 2023-04-01
# link: 'http://example.com/project-link'
---

## Project Details

This project addresses the long reuse distance problem in current batch processing methods, aiming to reduce Cache Miss rates and improve CPU efficiency in convolutional neural networks. A new **Batched Data Layout Optimization (BDLO)** scheme was designed and implemented to redefine data layout, minimizing memory access. The BDLO operation was embedded within other batch operators, reducing overhead, and achieving up to a **1.28x acceleration** using Libtorch and Eigen libraries. This project has been awarded as a Beijing-level student innovation project, and the research results have been submitted as **“BDLO: Batched-Data-Layout-Optimization Method for Batched Im2col-based Convolution on CPUs”**.

## Project Files

<!-- ### Project Screenshot
![Project Screenshot](assets/images/project-screenshot.png) -->

### Project Guide PDF
<iframe src="../files/Research on Batch Inference Acceleration Method for CNN on CPU Platform/IEEE_Journals_and_Transactions.pdf" width="100%" height="600px">
    Your browser does not support PDF viewing. Please download the file <a href="../files/Research on Batch Inference Acceleration Method for CNN on CPU Platform/IEEE_Journals_and_Transactions.pdf">Click here to download the PDF</a>
</iframe>

<!-- ### Project Report DOCX
[Download Project Report (DOCX)](assets/files/project-report.docx)

### Project Video
<video width="100%" controls>
  <source src="{{ site.baseurl }}/assets/videos/project-video.mp4" type="video/mp4">
  Your browser does not support the video tag. Please download the video file <a href="{{ site.baseurl }}/assets/videos/project-video.mp4">Click here to download the video</a>.
</video>

### Source Code
[Download Source Code (ZIP)](assets/files/project-source-code.zip) -->

