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
* **PhD in Computer Science**, University of Colorado Boulder, Spring 2024 — Present
* **Master of Science in Computer Science**, University of Colorado Boulder, Fall 2022 — Present
  * GPA: 3.9/4.0
* **Bachelor of Technology in Computer Science and Engineering**, PES University, Graduated May 2020
  * GPA: 9.25/10.0
  * Awarded the Professor MRD Merit Scholarship

Work experience
======
* **Research Assistant**, University of Colorado Boulder, May 2023 — Present
  * Working on building tools that assist software developers write cleaner code, by combining capabilities of AI models with static analysis.
* **Data Engineer**, Rupeek Fintech Pvt Ltd, Dec 2020 — May 2022
  * Built data-pipelines using pyspark, and helped maintain the data-warehouse on AWS Redshift with multiple terabytes of data.
  * Built a self-serve tool to upload data into the data-warehouse, removing dependencies on the data engineering team for ad-hoc analysis.
  * Saved up to 50% of Data Engg's bandwidth and improved analyst productivity by multiple hours.
* **Software Engineering Intern**, Ola Cabs (ANI Technologies), June 2019 — July 2019
  * Analysed cab-ride data as part of the fraud detection team.
  * Experimented with machine learning techniques (neural networks, auto-encoders, SVMs) to identify fraudulent activity.

Skills
======
* **Languages**: Python, Kotlin, Java, C/C++, JavaScript/TypeScript, HTML/CSS, SQL
* **Tools and Frameworks**: Git/GitHub, Docker, AWS, Node.js, React, TensorFlow, PyTorch, Keras, Scikit-Learn
* **Relevant Coursework**: Machine Learning, Compiler Construction, Advanced Operating Systems, Data Mining

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  


