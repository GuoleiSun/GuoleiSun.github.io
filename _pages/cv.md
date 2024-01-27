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
* Ph.D in computer vision & AI, ETH Zurich
* M.S. in computer science, KAUST
* B.S. in Science, Huazhong University of Science & Technology

Work experience
======
* Fall 2023: Research Scientist Intern
  * [Meta AI](https://ai.meta.com/)
  * Projects: Multi-modal large language models (MLLMs)

* Summer 2023: Research Scientist Intern
  * [Adobe Research](https://research.adobe.com)
  * Projects: Video matting & segmentation
<!--   * Supervisor: Professor Git -->

* 2018-2019: Research Engineer
  * Inception Institute of Artificial Intelligence (IIAI)
  * Duties: develop CV/AI algorithms on scene understanding, segmentation, and object counting
  * Supervisor: Prof. Fahad Kan, Prof. Hisham Cholakkal, and Prof. Salman Khan.
  
Skills
======
* Deal with large-scale datasets
* Deep learning frameworks: Pytorch and Tensorflow
* Various computer vision algorithms: object detection, image/video segmentation, object counting, denoising, super resolution.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Patents
======
* US Patent App. 16/278,392, 2019, [Object counting and instance segmentation using neural network architectures with image-level supervision](https://patents.google.com/patent/US10453197B1/en).
