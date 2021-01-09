---
layout: page
title: Research
permalink: /research/
---

Following is a list of research projects (in no particular order) that I undertook during my time at IIT Bombay.
<br/><br/>

**RF Real-Time Wireless Video Transmitting System**  [(report)]({{ site.url }}/reports/EDL.pdf)

*Guide: [Prof. Shalabh Gupta](https://www.ee.iitb.ac.in/wiki/faculty/shalabh)*

Transmitting videos in real-time through obstacles like buildings is a difficult and yet an important task. Towards this end we develop an efficient lightweight system which transmits and receives PAL (Phase Alternate Line) videos in real-time and is capable of functioning robustly even in the presence of obstacles.
We designed custom subsystems ranging from power boosters, low noise amplification stage to the architectures of upconverter and downconverter, along with all the matching circuits. These were then integrated on PCBs for transmitter, receiver and local oscillator.

This was presented to the Indian Army owing to its efficacy.
<br/><br/>

**Solving IQ Imbalance in Optical Receivers**

*Guide: [Prof. Shalabh Gupta](https://www.ee.iitb.ac.in/wiki/faculty/shalabh)*

IQ imbalance occurs when the sine and cosine wave from the local oscillator are not perfectly 90 degrees apart or/and do not have the same amplitude. Performance for the existing joint equalization and IQ imbalance compensation was tested with changing adaptive algorithms (LMS, RLMS, NLMS), filter sizes used in the algorithm and the algorithms used for carrier phase estimation. We are exploring ways and conducting experiments to develop a method for IQ imbalance which can achieve a faster convergence to the optimal IQ imbalance angle.
<br/><br/>

**A Path to being Ground Truth Free** [(report)]({{ site.url }}/reports/DDP.pdf)

*Guide: [Prof. Amit Sethi](https://www.ee.iitb.ac.in/~asethi/)*

Creating annotations for nuclei segmentation in histopathology images is a very effort and time intensive process. This has resulted in a lack of complete datasets (i.e. images are available but no masks). Our aim in this research project is to remove dependence on the available ground truth masks. W use synthetic image generation to achieve a baseline performance on the model used for performance analysis. We then use a interactive segmentation and synthetic image generation in a cyclic way to achieve the required performance without using the ground truth masks. Experiments are still being conducted.
<br/><br/>

**Color Normalization for H&E Stained Images**  [(paper)](https://arxiv.org/abs/2011.15000)

*Guide: [Prof. Amit Sethi](https://www.ee.iitb.ac.in/~asethi/)*

Labs often follow different protocols for H&E (Hematoxylin and Eosin) tissue cell staining or the process could involve some errors. In either case training on one dataset and testing on another (either from a different lab or with errors) can drastically affect the performance of the model. We develop a fully convolutional self-supervised technique for circumventing the issues caused by a difference and/or errors in cell staining. The pipeline uses a set of WSIs (Whole Slide Images) as a target domain. Our pipeline can be used as an independent pre-processing block and will prevent the task specific network after it to underperform because of staining errors and/or differences.

*Update (Jan 2021)*: This work has been accepted at the IEEE International Symposium on Biomedical Imaging (ISBI) 2021.
<br/><br/>

**Efficient Multiresolution Path Planning** [(report)]({{ site.url }}/reports/Wavelets.pdf)

*Guide: [Prof. Vikram Gadre](https://www.ee.iitb.ac.in/wiki/faculty/vmgadre)*

Path planning finds applications in a lot of tasks like navigating robots and autonomous vehicles. However, path planning algorithms can become very computationally expensive. We develop a multiresolution path planning algorithm (path being represented by an arbitrary graph) and achieves an exponential speedup.


<!-- #### **Research Papers**

[Reformulating Unsupervised Style Transfer as Paraphrase Generation](https://arxiv.org/abs/2010.05700)  
*Kalpesh Krishna*, John Wieting, Mohit Iyyer  
**EMNLP 2020**  
[project page (demo + code + data + talk)](http://style.cs.umass.edu)

[Thieves on Sesame Street! Model Extraction of BERT-based APIs](https://arxiv.org/abs/1910.12366)  
*Kalpesh Krishna*, Gaurav Singh Tomar, Ankur P. Parikh, Nicolas Papernot, Mohit Iyyer  
**ICLR 2020**  
[blog](http://www.cleverhans.io/2020/04/06/stealing-bert.html) // [project page (code + slides + Twitter + external coverage)]({% post_url 2020-04-04-iclr20 %})

[Generating Question-Answer Hierarchies](https://arxiv.org/abs/1906.02622)  
*Kalpesh Krishna*, Mohit Iyyer  
**ACL 2019**  
[project page (demo + code + data)](http://squash.cs.umass.edu/) // [technical note](https://arxiv.org/pdf/1906.02622.pdf#page=15) // [poster]({{ site.url }}/assets/squash-poster.pdf) // [external blog](https://towardsdatascience.com/introducing-squash-a-question-answer-generating-system-71c47b478a16)

[Syntactically Supervised Transformers for Faster Neural Machine Translation](https://arxiv.org/abs/1906.02780)  
Nader Akoury, *Kalpesh Krishna*, Mohit Iyyer  
**ACL 2019**  
[code](https://github.com/dojoteef/synst) // [poster](https://people.cs.umass.edu/~nsa/posters/synst-acl2019.pdf)  

[Trick or TReAT: Thematic Reinforcement for Artistic Typography](https://arxiv.org/abs/1903.07820)  
Purva Tendulkar, *Kalpesh Krishna*, Ramprasaath R. Selvaraju, Devi Parikh  
**ICCC 2019** (*oral presentation*, <a style="color:red" href="https://twitter.com/jmacunha/status/1142184529026662400"><i>Best Presentation Award</i></a>)  
[code](https://github.com/purvaten/treat) // [slides](https://purvaten.github.io/data/TReAT-talk.pdf) // [video](https://photos.google.com/share/AF1QipNFg9TYf2Wk6z6zKg3I3rT7jiWoH97cRVIQ-_JrZwIUUMqkyWHomVc1Lv1UGduraA/photo/AF1QipOm-e6jFA3Im9eiHt79R-A0j36CSVCoqSeU_VZG?key=dDFhdGlYUV9yVkUzOW5YaFlaeXdhMGQ1UHZ0QnZ3) // [demo](http://doodle.cloudcv.org/)  

[Revisiting the Importance of Encoding Logic Rules in Sentiment Classification](https://arxiv.org/abs/1808.07733)  
*Kalpesh Krishna*, Preethi Jyothi, Mohit Iyyer  
**EMNLP 2018** *(oral presentation, short paper)*  
[code + data](https://github.com/martiansideofthemoon/logic-rules-sentiment/) // [slides]({{ site.url }}/assets/emnlp-2018.pdf) // [video](https://vimeo.com/306136412)  

[Hierarchical Multitask Learning for CTC-based Speech Recognition](https://arxiv.org/abs/1807.06234)  
*Kalpesh Krishna*, Shubham Toshniwal, Karen Livescu  
\[[external video](https://www.youtube.com/watch?v=OSpFS8kyibw)\]  

[A Study of All-Convolutional Encoders for Connectionist Temporal Classification](https://arxiv.org/abs/1710.10398)  
*Kalpesh Krishna*, Liang Lu, Kevin Gimpel, Karen Livescu  
**ICASSP 2018** *(Awarded [SPS Travel Grant](https://signalprocessingsociety.org/events/sps-travel-grants))*  
\[[poster](https://sigport.org/sites/default/files/docs/study-convolutional-encoders.pdf)\]  


**Collaborators** (in order of publication date): [Karen Livescu](https://ttic.uchicago.edu/~klivescu), [Kevin Gimpel](https://ttic.uchicago.edu/~kgimpel), [Liang Lu](https://ttic.uchicago.edu/~llu), [Shubham Toshniwal](https://ttic.uchicago.edu/~shtoshni), [Preethi Jyothi](https://www.cse.iitb.ac.in/~pjyothi), [Mohit Iyyer](https://people.cs.umass.edu/~miyyer/), [Purva Tendulkar](http://purvaten.github.io/), [Ramprasaath R. Selvaraju](https://ramprs.github.io/), [Devi Parikh](https://www.cc.gatech.edu/~parikh/), [Nader Akoury](https://people.cs.umass.edu/~nsa/), [Gaurav Singh Tomar](https://scholar.google.com/citations?user=p1SDN0oAAAAJ&hl=en), [Ankur P. Parikh](https://www.cs.cmu.edu/~apparikh/publications.html), [Nicolas Papernot](https://www.papernot.fr/), [John Wieting](https://www.cs.cmu.edu/~jwieting)

#### **Software Papers**

[SunPy: A Python package for Solar Physics](https://joss.theoj.org/papers/10.21105/joss.01832)  
Stuart J. Mumford and others  
**JOSS 2020**

#### **Thesis**

[Undergraduate Thesis - Constraint Driven Learning]({{ site.url }}/assets/bachelor_thesis_final.pdf)  
*(under guidance of [Prof. Preethi Jyothi](https://www.cse.iitb.ac.in/~pjyothi/))*  
IIT Bombay *(2017-2018)*  

#### **Course Materials**

[Homework](https://github.com/martiansideofthemoon/allennlp-probe-hw) on linguistic probe tasks designed for UMass Amherst's grad NLP class using [AllenNLP](https://allennlp.org/).

#### **Other Research (Course Projects)**

[MixMatch on Vision + Language Tasks (NLVR2)](https://github.com/martiansideofthemoon/mixmatch-lxmert): An attempt to integrate the [MixMatch](https://arxiv.org/abs/1905.02249) data augmentation algorithm for semi-supervised image classification to the challenging setting of [NLVR2](http://lil.nlp.cornell.edu/nlvr), where the input space has both images and text ([report](https://sumanvid97.github.io/docs/cv_report.pdf)).

[Research Exchange - A Collaborative Paper Annotation Tool](https://github.com/martiansideofthemoon/research-exchange) - A platform to collaboratively annotate scientific literature to help newcomers understand research papers, built during an Human Computer Interaction course project ([report]({{ site.url }}/assets/research-exchange.pdf)).

[Inference Networks for Structured Prediction](https://github.com/TheShadow29/infnet-spen) - A TensorFlow implementation for the multi-label classification experiments in [Learning Approximate Inference Networks for Structured Prediction](https://arxiv.org/abs/1803.03376). Also contains experiments on the [FIGMENT](http://cistern.cis.lmu.de/figment/) dataset and a extension to Inference Network training algorithm based on [Wasserstein GANs](https://arxiv.org/abs/1704.00028) ([report](https://people.cs.umass.edu/~kalpesh/infnet.pdf)).

[Diversity Sampling in Machine Learning](http://github.com/martiansideofthemoon/diversity-sampling) - An implementation of [Diverse Beam Search for Neural Networks](https://arxiv.org/abs/1610.02424) in Language Modelling. Also contains the original (slightly modified code) for the interactive segmentation experiments in [Diverse M-Best Solutions in MRFs](http://ttic.uchicago.edu/~gregory/papers/MBestModes.pdf) ([report](https://people.cs.umass.edu/~kalpesh/diversity.pdf)).

[Macro Actions in Reinforcement Learning](https://github.com/martiansideofthemoon/macro-action-rl) - A suite of five algorithms (including ideas from "[Learning to Repeat: Fine Grained Action Repetition for Deep Reinforcement Learning](https://arxiv.org/abs/1702.06054)") encouraging agents to repeat actions ([report](https://people.cs.umass.edu/~kalpesh/macro.pdf)).

[Single Image Haze Removal](https://github.com/martiansideofthemoon/blind-dehazing) - An implementation of He et al. 2009, "[Single Image Haze Removal using Dark Channel Prior](https://www.robots.ox.ac.uk/~vgg/rg/papers/hazeremoval.pdf)" and an ongoing implementation of Bahat & Irani 2016, "[Blind Dehazing using Internal Patch Recurrence](http://ieeexplore.ieee.org/document/7492870/)" ([report](https://people.cs.umass.edu/~kalpesh/dehaze.pdf)).

[CNNs for Sentence Classification](https://github.com/martiansideofthemoon/tf-sentence-classification) - A TensorFlow 1.1 implementation of Kim 2014, "[Convolutional Neural Networks for Sentence Classification](https://arxiv.org/abs/1408.5882)".  

[Brittle Fracture Simulation](https://github.com/martiansideofthemoon/brittle-fracture-simulation) - Python implementation of O'Brien and Hodgins 1999, "[Graphical Modeling and Animation of Brittle Fracture](http://graphics.berkeley.edu/papers/Obrien-GMA-1999-08/Obrien-GMA-1999-08.pdf)".  

[ECG Signal Analysis](https://github.com/martiansideofthemoon/ecg-analysis) - Python implementation of parts of Christopher Buck, Aneesh Sampath 2013, “[ECG Signal Analysis for Myocardial Infarction Detection.](https://cnx.org/contents/VZtarYnV@2.1:WO1d4SJW@1/Introduction)”.  

#### **Indian Language Datasets**

As a part of my RnD project at [IIT Bombay](http://www.iitb.ac.in/), I am releasing the dataset used to train my neural network language models. These have been mined from Wikipedia and I hope this will help further research in language modelling for Indian morphologically rich languages. The folder also contains the original PTB dataset.

* Malayalam (denoted by `ml`)
* Tamil (denoted by `ta`)
* Kannada (denoted by `kn`)
* Telugu (denoted by `te`)
* Hindi (denoted by `hi`)
* PTB (denoted by `ptb`)

All these datasets are compatible with [SRILM](http://www.speech.sri.com/projects/srilm/). Files marked with `unk` have replaced all singletons with `<unk>` tokens. Files marked with `char` are character versions. All datasets have a `train`, `valid` and `test` file. You will find the dataset [here](https://drive.google.com/file/d/0B5Y_SiDYwIObaE52dmZ0YVFXckU/view?usp=sharing). -->
