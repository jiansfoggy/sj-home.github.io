---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Click <a href="../files/JS-CV.pdf" target="_blank">**here**</a> to read PDF file.

Education
=========
* Ph.D in Computer Science, University of Denver, 2018 -- Present
* M.S. in Statistics, The George Washington University, 2017
* B.S. in Mathematics and Applied Mathematics, Shandong Agricultural University, 2014

Publications
============
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Conferences
===========
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Work Experience
===============
* January 2025 - August 2025: Navigation Engineer
  * Medtronic
  * Lafayette, CO
  * Duties included:
    
    **<u>EM Localization</u>**
      1. Developed a real-time deep learning-based Electromagnetic Localization System for catheter-based tasks used in Hugo Surgical Robotic. This system is designed for critical tasks like lung cancer biopsies and cardiac valve placement.
      2. Trained MS-ResNet+MHSA models on HPC clusters and deployed on NVIDIA Jetson Orin Nano with TensorRT acceleration, achieving real-time inference of catheter position and orientation.
      3. The model’s performance is highly competitive with existing methods. The distance error's 25% to 75% quantile is [2.44mm, 5.57mm], and the angle error is 0.49 to 1.22 degrees.
      4. Generated large-scale simulated training data through interpolation, using a base map of electromagnetic field values.
    
    **<u>3D Cardiac Reconstruction</u>**
      1. Designed a NeRF-based 3D cardiac reconstruction pipeline by analyzing multi-modal data, including Clarius ultrasound image, IMU, optical tracker data, and Computerized Tomography (CT) scan image.
      2. Developed an efficient method for synchronizing the start times of the Clarius probe and optical tracker.
    
    **<u>Workflow & Conference</u>**
      1. Standardized EM Localization and 3D reconstruction workflows, from model training on HPC to embedded deployment on the  Jetson board, and synchronized data collection.
      2. The work on EM Localization was accepted for an oral presentation at the 2025 44th Annual Medtronic Science & Technology Conference: U.S. Session.
    
    **<u>Used Skills</u>**
      * **Programming & Libraries**: Python, Bash, Pytorch, TensorRT.
      * **Project Management**: Git (Bitbucket)
      * **Theory & Model**: Biot-Savart Law, CNNs, Transformers, Gaussian Mixture Model.
      * **Computation & Embedded Systems**: High Performance Computing (HPC), Jetson Orin Nano, Signal Transmit.
      * **Medical Data & Devices**: Clarius Ultrasound Probe, Medtronic Optical Tracking System.
      * **Research Areas**: Electromagnetic Localization, Inverse Problems for Partial Differential Equations, 3D Reconstruction.

* June 2023 – January 2024: Project Supervisor
  * 2023 Vision and Robotic Lab Summer Research in the University of Denver 
  * Denver, CO                                                             
  * Duties included:
    * Supervised a research project using the RoBERTa-CNN model to detect suicidal ideation from social media posts.
    * Guided dataset cleaning, model training, and academic writing; results published in IEEE EMBC 2024 [IEEE Xplore](https://ieeexplore.ieee.org/abstract/document/10782647).
    
    **<u>Used Skills</u>**
      * **Programming & Libraries**: Python, Bash, Pytorch
      * **Theory & Model**: CNNs, BERTs
      * **Computations**: GPUs
      * **Research Directions**: NLP, Suicidal Intention Detection

* June 2022 – August 2022: Software Engineering Intern
  * Dream Face Technologies, LLC
  * Denver, CO   
  * Duties included: 
    * Developed deep learning models to analyze visual data of older adults to distinguish Mild Cognitive Impairment from healthy controls.
    * Collaborated with the engineering team to analyze I-CONECT video dataset and integrate the model with other systems (Ryan Apps).
    * Published paper, [MC-ViViT](https://www.sciencedirect.com/science/article/pii/S0957417423024314): Multi-branch Classifier-ViViT to Detect Mild Cognitive Impairment in Older Adults Using Facial Videos.
    
    **<u>Used Skills</u>**
      * **Programming & Libraries**: Python, Bash, Pytorch
      * **Theory & Model**: CNNs, ViViT
      * **Computations**: GPUs
      * **Research Directions**: Computer Vision, Video Recognition, Intra- and Inter-Class Imbalanced Issues, MCI

* July 2019 – August 2019: Computer Vision Engineer Intern
  * Tsinghua University Big Data Laboratory at Qingdao Center
  * Qingdao, China     
  * Duties included: 
    * Developed models to classify different rat species from blurred videos and recognize small objects in pictures (around 63% accuracy).
    * **Used Models & Libraries**: Tensorflow, Keras, SVM, GrabCut, alpha matte, Poisson Matting, CNNs, LibSVM.

* July 2017 – January 2018: Placement Intern, Data Analyst
  * United States Peace Corps
  * Washington, DC    
  * Duties included:  
    * Developed models to evaluate qualified candidates, whether they would accept or decline the invitation, reduced the padding rate in the delivery process, and evaluated candidates’ language level.
    * Prediction Accuracy is 98.37%; R Shiny Data visualization link: http://keepcreation.shinyapps.io/summerize/.
    * Used Models & Libraries: R, R Shiny, SQL, Pivot Tables; random forest, weighted linear regression, Naïve Bayes Classifier. 

Skills
======
* **Research Branch of Deep Learing:** Computer Vision, Natural Language Processing, Signal Processing.
* **Research Direction:** Image and Video Recognition, Model Optimization, Representation Learning, Sentence Classification, Electromagnetic Localization.
  * **Core Research Problem:** Data Imbalanced, Optimization.
  * **Application Scenarios:** Affective Computing, Mild Cognitive Impairment Detection, Protein Function Detection, Suicide Intention Detection, Violence Detection, Robotic Navigation.
* **Common-used Framework:** PyTorch, Tensorflow, Keras, PyTorch Lightening, .
* **Common-used Package:** Matplotlib, Numpy, OpenCV, Pandas, Pillow, Sci-kit Learn, TensorRT.
* **Common-used Neural Networks:** Convolutional Neural Networks (ResNet, MobileNet, EfficentNet, etc), Transformers (ViT, ViViT, Swin Transformer, RoBERTa).
* **Programming Language:** Python, Bash
* **Embedded & Edge AI:** NVIDIA Jetson Series, TensorRT, Signal Processing
* **Cloud & HPC:** AWS (EC2, S3, DynamoDB, Lambda, EBS), Google Cloud Platform, Docker, HPC
* **MLOps & DevOps:** WandB, Streamlit, FastAPI, Postman, CI/CD (Github Actions)
* **Version Control:** Git, Github, Gitlab, Bitbucket
* **SQL & NoSQL:** SAS, SPSS, MySQL, PostgreSQL, MongoDB, Neo4J, Redis
* **Big Data & Distributed Systems:** Spark, Hadoop/MapReduce, HBase
* **Data Visualization:** Tableau.
* **Certifications**: [HackerRank](https://www.hackerrank.com/jian_sun) Python (Intermediate) Certificate (14BA6D47EC75), 5-star Gold Badge (SQL & Python)

Service and leadership
======================
* Currently signed in to 43 different slack teams
