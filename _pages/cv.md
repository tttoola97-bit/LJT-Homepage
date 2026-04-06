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
* Ph.D. in Computer Science, Hong Kong University of Science and Technology, 2024-Present
* B.Eng., Shanghai Jiao Tong University, 2020-2024

Work experience
======
* February 2025 - Present: Research Intern
  * MINIMAX
  * Conducting advanced AI research

* June 2024 - September 2024: Research Intern
  * Tencent WXG
  * Advisor: Zifei Shan
  * Research on natural language processing

* June 2023 - December 2023: Research Intern
  * Shanghai AI Lab
  * Advisor: Prof. Yu Cheng
  * Machine learning and AI research

Skills
======
* Programming Languages: Python, C++, Java, JavaScript
* Machine Learning Frameworks: PyTorch, TensorFlow, Hugging Face Transformers
* Research Areas: Natural Language Processing, Machine Learning, Computer Vision, Reinforcement Learning
* Tools & Technologies: Git, Linux, LaTeX, Jupyter Notebooks

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
