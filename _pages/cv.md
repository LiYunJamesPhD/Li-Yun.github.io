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
    (1) The project aims to research and develop a novel content-based video processing with popular image processing and computer vision functionalities for people who do not have prior programming knowledge.
    (2) Took the advantages of traditional content-based video processing frameworks and multimedia middleware frameworks to design and implement a hybrid content-based video processing tool with multiple tailored modules for different purposes.
    (3) Designed and implemented all the modules in the way of leveraging the middleware concepts to perform different functionalities in different modules but have generic inputs and outputs for passing intermediate results in between the modules.
    (4) Designed and implemented an adaptive naming mechanism that can dynamically store intermediate results and reuse it. The proposed framework was tested on two popular computer vision applications: facial and object detection. The proposed framework can conduct the object detection task in 57.14 ms for a given video with frame resolution 640x480 and 8900 video frames.
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
    (1) This project aims to research and develop new video compression frameworks that have high compression quality but low bitrates.
    (2) My contribution in this project was helping debug the code and check expeirmental results. I also helped out writing a research paper. The proposed framework with threshold 36 achieves 44dB PSNR and only encodes 21% macro blocks for anchor-frame distance 4.

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
  * trobuleshooted the highlight video generation programs that are implemented by Python, HTML, Javascript, and AngularJS.
  * Modified the existing input video parser to enhance the parser's scalability that can process distinct video segments.
  * Modified the exisiting preference functioanlity to craft precise hightligh video segments for users using a logarithmic function.
  * Deployed the entire application (e.g., programs) to Amazon Web Services (AWS).

* **Graduate Research Assistant (Sep. 2010 - June 2012)**
  * [Fu Jen Catholic University](https://www.fju.edu.tw/indexEN.jsp)
  * Supervisor: Liang-Hua Chen (Computer Vision Lab)
  * Helped Principle Inverstigator (PI) survey relevent research papers for different research projects.
  * Helped PI and other lab's students implement pieces of code and evaluate the performance of the proposed approaches.
  * Conducted a pedestrian detection project and proposed an integrated approach that comprises histogram of oriented gradient features nd Fourier descriptor features to extract two types of features and trained two SVM detectors for two different features to detect pedestrian in video. The proposed approach achived over 80% F-1 score in the CAVIAR and PETS2000 dataset.

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
* **Programming Language:** C/C++, Java, Python, Matlab, SQL, Shell, Scala, Lua, and Julia
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
* **Open Source Developer (Jun. 2018 - Dec. 2018)**
  * Critigen
  * This project aims to visualize map coming from OpenStreeMap (OSM) data quality by summarizing map error indicators within relevant grids. By doing this, it is easy for map analysts to focus on the grids with high error numbers.
  * Designed and implemented a Map Quality Measure (MQM) tool that represents the map quality for a given geographic unit (an OSM data input) by a heat map style representation in python.
  * Designed and implemented an automated process to find the optimal heat map grid size and display the quality in the heat representations by leveraging a K-D tree-like structure to virtually partition the coordinates of the map input into multiple grids and represent a range of the coordinates as a node. To reduce error counts the tool applies another tree to refine the grid size for some specific grids.
  * Designed and implemented an OSM preprocessing wrapper to acquire the OSM data, extract coordinates and feature flags, and pass all of them to the map analysis and visualization.
  * Designed and implmented a cascade K-D tree-like structure framework to be able to perform error correction tasks. The MQM tool can process over 750GM OSM data without having errors.
* **Google Developer Student Club Lead (Aug. 2020 - Present)
  * Google Developer Student Club Community, [PDX's DSC Chapter](https://dsc.community.dev/portland-state-university/)
  * Set up and manage a core team at the DSC.
  * Hold events and workshops or collaborate DSC leads at different universities/colleges to establish events.
  * Search real-world projects and provide them to PDX's students.




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


