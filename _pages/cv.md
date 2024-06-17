---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

# Education

- PhD in Computer Applications, Dublin City University, 11/2021 - present (expected graduate in 11/2025). Topic: Machine learning for brain data characterisation under uncertainty
- M.Sc. in Computer Applications, Dublin City University, 2021
- B.S. in Electronics Engineering, Danang University of Science and Technology, Danang, Vietnam, 2016

# Work experience

- 16/02/2022 - 16/12/2022: Research Data Scientist Intern - Huawei

  - Duties included: Researched text-to-speech options for a text-to-video application, built image retrieval applications based on CLIP.
  - Supervisors: Gonzalo Fiz Pontiveros (Principal Research Scientist) and Tri Kurniawan Wijaya (AI Technical Director)

- 03/2021 - 11/2021: Machine Learning Engineer - Insight SFI Centre for Data Analytics

  - Duties included: Develop a full-stack machine learning-based pipeline on AWS for mental health diagnosis from speech.
  - Supervisors: Prof. Tomas Ward and Dr. Gerard Derosiere

- 06/2016 - 11/2019: Hardware Design Engineer - eSilicon Corporation (now acquired by Synopsis)

  - Duties included: Built hardware specialised in deep neural network training

# Skills

- Machine Learning
  - Topics: Speech recognition, text-to-speech, large language model, EEG, MRI
  - ML Frameworks: scikit-learn, TensorFlow, PyTorch, HuggingFace
  - Cloud: AWS, Azure, GCP
- Software Engineering
  - Frontend: ReactJS, Streamlit
  - Backend: FastAPI
  - Programming Languages: Python/C++
  - Database: NoSQL with MongoDB, SQL

# Publications

  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

# Teaching

  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
