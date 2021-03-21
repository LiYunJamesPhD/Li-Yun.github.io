---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. Computer Science and Information Engineering, Fu Jen Catholic University, New Taipei, Taiwan, 2006 - 2010
* M.S. Computer Science and Information Engineering, Fu Jen Catholic University, New Taipei, Taiwan, 2010 - 2012
* M.S. Computer Science, Portland State University, Portland, Oregon, USA, 2015 - 2017
* Ph.D Computer Science, Portland State University, Portland, Oregon, USA, 2016 - 2022 (expected)


Work experience
======
* **Graduate Student Researcher (Sep. 2016 - Present)**
  * Portland State University
  * **Video as Text: A New Paradigm for Video Processing:**
    (1) test
    (2) test
  * **Adversarial Deep Learning:**
    (1) The project aims to study what an adversarial example and adversarial perturbation is and how we can alleviate perturbation deterioration to the images.
    (2) We understood the perturbation noise is high frequency information by trying to maximize a loss between an input image and a deep
learning model. According to this observation, our hypothesis is that perturbed images contain more numbers of colors compared to unperturbed images.
    (3) We proposed three color-reduction approaches (e.g., GPCR, GK-means, and Fast GK-means) to reduce the number of image colors containing the perburation in the image. Compared to other image processing approaches, the proposed approaches achieve over 85% top-1 classfiication accuracy on a customized Imagenet dataset with 1000 images.
    (4) We extended the proposed approaches by replacing a standard Gaussian filter with an adaptive Gaussian algorithm. The new color-reduction approaches achive over 78% and 90% top-1 classification accuracy on a customized Imagenet dataset with 2000 images underlying different network architectures and adversarial attacks.
  * **Image Deblurring: (Collaboration Project)**
    (1) It is an on-going project, and the aim of this project is researching and developing new image deblurring techniques by Generative Adversarial Networks (GANs).
    (2) My contribution comprises (a) studying relevant GAN-based techniuqes and discussing the papers with the other researcher, (b) providing a new idea and implementing the idea in Pytorch, and (c) Evaluating the new idea and discussing expeirments with the other researcher.
  * **Cross Domain Model Compression: (In Progress)**
    (1) It is an on-going project. It aims to research and develop novel neural-network compression techniques for crafting domain-specific neural networks with few FLOPs (Number of float-pointing operations) and the number of model's parameters.
    (2) Studying relevant research papers and conceptualize research problems. I also narrow the research problems to possible research topics and start working on a new solution in Pytorch.
  * **Frame Interpolation Video Compression:**
    (1) test
    (2) test

* **Bixby Data Pipeline Engineer Intern (Oct. 2019 - Apr. 2020)**
  * [Samsung Research America](https://www.sra.samsung.com/)
  * Supervisor: Sridhar Kocharlakota
  * Designed and implemented an end-to-end automatic audio data pipeline that comprises data collection, keyword chunking, and data storage for generating negative hard training examples to benefit the Automatic Speech Recongition (ASR) team using the Boto3 Python package, parallel processing Python APIs, and a learning-based keyword detection program. The chunked audio data are then uploaed to MongoDB using AWS CLI and Boto3. The implemented pipeline can collect the negative hard exmpales from thousands youtube channels in 3 to 4 days.
  * Designed and implemented an end-to-end generic keyword extraction pipeline with a generic keyword extraction algorithm using PyMongo and PySpark. The pipeline can parse millions of audio data and complete the task in one day.
  * Investiaged the bottlenecks of the existing data pipeline framework that comprises the Kafka package and summarized the issues of Kafka in the existing pipeline.
  * Maintained and managed a data ladeling system that is implemented in React and Node.js for domain experts.

* **Software Engineering Intern (Sep. 2017 - Mar. 2018)**
  * Individual Contractor
  * Supervisor: Frank Selker
  * mention what I have doen in this work.......

* **Graduate Student Researcher (Sep. 2010 - June 2012)**
  * [Academia Sinica, Taiwan](https://www.sinica.edu.tw/en)
  * Laboratory Director: Mark Liao
  * Joined weekly group meetings and learned researcher ideas from different PhD students.
  * Presented personal research progress in each year.
  * Discussed personal research progress with postdoc students in Multimedia Technologies Laboratory.


Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>


Skills
======
* **Programming Language:** C/C++, Java, Python, Matlab, SQL, Shell, Scala, Lua
* **Libraries/Tools:**
  * **Image Processing and Computer vision:** OpenCV (C++ and Python), Matlab, and Pytorch
  * **Machine Learning and Deep Learning:** NumPy, Pytorch, Scikit-learn, Tensorflow, and Torch
  * **Big Data and Data Engineering:** PySpark, MongoDB (PyMongo), Multiprocessing (Python), Boto3, Matplotlib, Apache Kafka,
                                       Kibana, and Kubernetes
  * **Video Processing:** OpenCV, Matlab, and FFmpeg
  * **Documentation and Version Control:** Git and Latex
* **Perfessonal Knowledge:** Computer Vision, Machine Learning, Deep Learning, and Image Processing


Service and leadership
======
* Google DSC, and Critigen project......




<!--
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
-->
<!--
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
-->


