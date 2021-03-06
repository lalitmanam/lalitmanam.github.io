---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Download my CV - [__Curriculum Vitae__](\files\LM_Resume.pdf){: .btn .btn--info}

Research Interests
------
I am currently interested in 3D Vision problems primarily on large scale structure-from-motion and SLAM pipelines. Previously, I was involved in development of impulse noise removal techniques from colour images.

<!--* Research Interests - Machine Learning
* Other Learning Interests - ... -->

<!--
[Publications](https://dbp1994.github.io/publications/){:target="_blank"}
------

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
--->

Current Research
------
I am working on 3D reconstruction problems in computer vision i.e. to build a 3D representation of a scene from images. Depending on the application, it can be broadly classified as following
- Structure-from-Motion (SfM)<br>
  Build a 3D model of a scene from a collection of images.
  
  ![SfM Model](\images\Vitthala1.jpg){:height="40%" width="40%"}
  
- Simultaneous Localization and Mapping (SLAM)<br>
  Incrementally build a map of the environment from an image sequence along with determining the camera location simultaneously.
  
  ![SLAM Map](\images\Map.png){:height="50%" width="50%"}<br>

Depth cannot be recovered with a single image. Multiple images of the same scene is required to capture the 3D structure. Geometry of both the problems is same since both the applications use cameras. So building 3D representation requires estimating the orientation/viewing direction as well as the position of the cameras. My current work focuses on estimating orientations (also called rotation averaging) and positions of the cameras (called translation averaging). 

Applications of SfM and SLAM algorithms also include 3D exploration of photo collections and phone-based augmented reality.

Education
------
* PhD, August 2018 - Present<br>
[Department of Electrical Engineering](http://www.ee.iisc.ac.in){:target="_blank"},
[Indian Institute of Science](https://www.iisc.ac.in/){:target="_blank"}, Bangalore<br>
Advisor: [Dr Venu Madhav Govindu](http://www.ee.iisc.ac.in/people/faculty/venu/index.html){:target="_blank"}

* BTech, August 2013 - June 2017<br>
Electronics and Communication Engineering,<br>
National Institute of Technology Silchar

<!--
Work experience
------

* September 2017 - July 2018: Project Assistant
  * [Department of Electrical Engineering](http://www.ee.iisc.ac.in){:target="_blank"}
  * Mentors: [Dr. Prasanta Kumar Ghosh](http://www.ee.iisc.ac.in/faculty/prasantg/index.php){:target="_blank"}
  * Project Details:
--->

Teaching experience
------

* October 2020 - February 2021: Teaching Assistant
  * Course: Stochastic Models & Applications
  * Instructor: [Prof. PS Sastry](http://www.ee.iisc.ac.in/faculty/sastry/index.php){:target="_blank"}

Relevant courses
------
* Computer Vision
* Stochastic models and applications
* Linear and non-linear optimization
* Convex optimization
* Machine Learning

<!--
[Projects](https://dbp1994.github.io/projects/){:target="_blank"}
------

  <ul>{% for post in site.projects reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
-->
<!-- Professional services
------
* Reviewer for [NeurIPS '20](https://neurips.cc/Conferences/2020)
-- >

<!-- Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
 -->
