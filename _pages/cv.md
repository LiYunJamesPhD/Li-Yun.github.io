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
  * Extended the desinged pipeline to 




* **Software Engineering Intern (Fall 2017 - Winter 2018)**
  * Individual Contractor
  * Supervisor: Frank Selker
  * mention what I have doen in this work....


Helped a data pipeline and automation team at Samsung Research America (SRA) design and develop an end-to-end automatic data pipeline
framework having an audio data collection, a keyword chunking, and a data storage stage for generating negative hard training examples and
benefiting the machine learning team at SRA.



Helped the data pipeline and automation team (1) investigate the bottlenecks of the existing data pipeline framework and summarize all the
problems in the pipeline framework and (2) maintain and manage a UI labeling audio data examples for domain experts at SRA.






to download audio data from Youtube Channels using the Boto3 Python API and parallel processing APIs in Python and
chunk the downloaded audio files to small pieces of clips with particular audio features that are similar to target audio features by integrating
a machine-learning-based keyword detection module and AWS CLI.

Contributed a program to upload the chunked audio files and the associated metadata such as video titles, video categories, and etc. to non-
SQL databases using Pymongo and parallel processing APIs in Python


3 pieces in Samsung intern......
1. audo pipeline. (youtube audio and devices ==> key works....)
2. kafka (experiments)
3. maintain websies


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

