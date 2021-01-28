---
layout: page
title: Research
permalink: /research/
---

Following is a list of research projects (in no particular order) that I undertook during my time at IIT Bombay.
<br/><br/>

 **#### RF Real-Time Wireless Video Transmitting System**  [(report)]({{ site.url }}/reports/EDL.pdf)
*Guide: [Prof. Shalabh Gupta](https://www.ee.iitb.ac.in/wiki/faculty/shalabh)*

Transmitting videos in real-time through obstacles like buildings is a difficult and yet an important task. Towards this end we develop an efficient lightweight system which transmits and receives PAL (Phase Alternate Line) videos in real-time and is capable of functioning robustly even in the presence of obstacles.
We designed custom subsystems ranging from power boosters, low noise amplification stage to the architectures of upconverter and downconverter, along with all the matching circuits. These were then integrated on PCBs for transmitter, receiver and local oscillator.

This was presented to the Indian Army owing to its efficacy.
<br/><br/>

#### **Solving IQ Imbalance in Optical Receivers**

*Guide: [Prof. Shalabh Gupta](https://www.ee.iitb.ac.in/wiki/faculty/shalabh)*

IQ imbalance occurs when the sine and cosine wave from the local oscillator are not perfectly 90 degrees apart or/and do not have the same amplitude. Performance for the existing joint equalization and IQ imbalance compensation was tested with changing adaptive algorithms (LMS, RLMS, NLMS), filter sizes used in the algorithm and the algorithms used for carrier phase estimation. We are exploring ways and conducting experiments to develop a method for IQ imbalance which can achieve a faster convergence to the optimal IQ imbalance angle.
<br/><br/>

#### **A Path to being Ground Truth Free** [(report)]({{ site.url }}/reports/DDP.pdf)

*Guide: [Prof. Amit Sethi](https://www.ee.iitb.ac.in/~asethi/)*

Creating annotations for nuclei segmentation in histopathology images is a very effort and time intensive process. This has resulted in a lack of complete datasets (i.e. images are available but no masks). Our aim in this research project is to remove dependence on the available ground truth masks. W use synthetic image generation to achieve a baseline performance on the model used for performance analysis. We then use a interactive segmentation and synthetic image generation in a cyclic way to achieve the required performance without using the ground truth masks. Experiments are still being conducted.
<br/><br/>

#### **Color Normalization for H&E Stained Images**  [(paper)](https://arxiv.org/abs/2011.15000)

*Guide: [Prof. Amit Sethi](https://www.ee.iitb.ac.in/~asethi/)*

Labs often follow different protocols for H&E (Hematoxylin and Eosin) tissue cell staining or the process could involve some errors. In either case training on one dataset and testing on another (either from a different lab or with errors) can drastically affect the performance of the model. We develop a fully convolutional self-supervised technique for circumventing the issues caused by a difference and/or errors in cell staining. The pipeline uses a set of WSIs (Whole Slide Images) as a target domain. Our pipeline can be used as an independent pre-processing block and will prevent the task specific network after it to underperform because of staining errors and/or differences.

*Update (Jan 2021)*: This work has been **accepted** at the [IEEE International Symposium on Biomedical Imaging (ISBI) 2021](https://biomedicalimaging.org/2021/).
<br/><br/>

#### **Efficient Multiresolution Path Planning** [(report)]({{ site.url }}/reports/Wavelets.pdf)

*Guide: [Prof. Vikram Gadre](https://www.ee.iitb.ac.in/wiki/faculty/vmgadre)*

Path planning finds applications in a lot of tasks like navigating robots and autonomous vehicles. However, path planning algorithms can become very computationally expensive. We develop a multiresolution path planning algorithm (path being represented by an arbitrary graph) and achieves an exponential speedup.
