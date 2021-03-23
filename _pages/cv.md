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
* B.S. in Electronics Engineering, Danang University of Science and Technology, Danang, Vietnam 2016
* M.Sc. in Computer Applications, Dublin City University, 2021

Work experience
======
* 03/2021 - present: Research Assistant
  * Insight SFI Centre for Data Analytics
  * Duties included: Develop a full-stack machine learning-based pipeline for meantal health 
  * Supervisor: Tomas Ward

* 06/2016 - 11/2019: Design Engineer
  * eSilicon Corporation (now acquired by Synopsis)
  * Duties included: 
    * Built deep learning models for pathological speech classification using TensorFlow
    * Researched solutions to the lack of labelled data in medical applications
    * Implemented semi-supervised learning approach using generative models (GAN and VAE) to improve classification accuracy in the context of lacking labelled data  
    * Published three research papers using CNN and GAN for the task of pathological speech classification
Skills
======
* Machine Learning
  * Frameworks: scikit-learn, TensorFlow, Flask
  * Model Deployment using Amazon Web Service
* Software Engineering
  * Programming Languages: Python/C++
  * Database: NoSQL with MongoDB
* Teamwork

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>


Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

