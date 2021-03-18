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
* **Graduate Student Researcher (Fall 2016 - Present)**
  * Portland State University
  * Advisor: Wu-chi Feng
  * mention different projects........

* **Bixby Data Pipeline Engineer Intern (Fall 2019 - Winter 2020)**
  * [Samsung Research America](https://www.sra.samsung.com/)
  * Supervisor: Sridhar Kocharlakota
  * Designed and implemented an end-to-end automatic audio data pipeline that comprises data collection, keyword chunking, and data storage for generating negative hard training examples to benefit the Automatic Speech Recongition (ASR) team using the Boto3 Python package, parallel processing Python APIs, and a learning-based keyword detection program. The chunked audio data are then uploaed to MongoDB using AWS CLI and Boto3. The implemented pipeline can collect the negative hard exmpales from thousands youtube channels in 3 to 4 days.
  * Designed and implemented an end-to-end generic keyword extraction pipeline with a generic keyword extraction algorithm using PyMongo and PySpark. The pipeline can parse millions of audio data and complete the task in one day.
  * Investiaged the bottlenecks of the existing data pipeline framework that comprises the Kafka package and summarized the issues of Kafka in the existing pipeline.
  * Maintained and managed a data ladeling system that is implemented in React and Node.js for domain experts.

* **Software Engineering Intern (Fall 2017 - Winter 2018)**
  * Individual Contractor
  * Supervisor: Frank Selker
  * mention what I have doen in this work......



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
<!--
Service and leadership
======
* Currently signed in to 43 different slack teams
-->

