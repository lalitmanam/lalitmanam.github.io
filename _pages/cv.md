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
I am currently interested in 3D Vision problems primarily on large scale structure-from-motion and SLAM pipelines. My recent work has been on developing methods to estimate camera motions in structure-from-motion. Previously, I was involved in development of impulse noise removal techniques from colour images.

<!--* Research Interests - Machine Learning
* Other Learning Interests - ... -->

<!--
[Publications](https://dbp1994.github.io/publications/){:target="_blank"}
------

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
--->

Publications
------

- C. Sidhartha, **L. Manam**, V.M. Govindu, ``Adaptive annealing for robust geometric estimation,'' accepted at Computer Vision and Pattern Recognition (CVPR), 2023
- **L. Manam**, V.M. Govindu, ``Correspondence reweighted translation averaging," European Conference on Computer Vision (ECCV), pp. 56-72, 2022 [[project page](https://ee.iisc.ac.in/cvlab/research/creta/){:target="_blank"}]
- A. Roy, **L. Manam**, R.H. Laskar, ``Removal of `Salt \& Pepper' noise from color images using adaptive fuzzy technique based on histogram estimation," Multimedia Tools and Applications, vol. 79, no. 47, pp. 34851-34873, Dec. 2020
- A. Roy, **L. Manam** and R.H. Laskar, “Region adaptive fuzzy filter: an approach for removal of random valued impulse noise,” IEEE Transactions on Industrial Electronics, vol. 65, no. 9, pp. 7268-7278, Sept. 2018
- **L. Manam**, A. Roy, R. H. Laskar and F. A. Talukdar, “Removal of fixed valued impulse noise using global noise statistics based adaptive histogram fuzzy filter,” TENCON 2017 - IEEE Region 10 Conference, pp. 2231-2235, 2017
- A. Roy, J. Singha, **L. Manam**, R.H. Laskar, “Combination of adaptive vector median filter and weighted mean filter for removal of high density impulse noise from color images,” IET Image Processing, vol. 11, no. 6, pp. 352-361, Jan. 2017


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
* PhD, Aug 2018 - Present<br>
[Department of Electrical Engineering](http://www.ee.iisc.ac.in){:target="_blank"},
[Indian Institute of Science](https://www.iisc.ac.in/){:target="_blank"}, Bengaluru<br>
Advisor: [Prof. Venu Madhav Govindu](http://www.ee.iisc.ac.in/people/faculty/venu/index.html){:target="_blank"}

* BTech, Aug 2013 - Jun 2017<br>
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

Teaching Assistantships
------

* Indian Institute of Science - Spring 2021, 2022, 2023
  * Course: Computer Vision (E1-216)
  * Instructor: [Prof. Venu Madhav Govindu](https://ee.iisc.ac.in/~venu/){:target="_blank"}

* NPTEL IIT Guwahati - Spring 2023
  * Course: Computer Vision and Image Processing (NOC23-EE39)
  * Instructor: Prof. M K Bhuyan

* NPTEL IIT Kharagpur - Fall 2022
  * Course: Computer Vision (NOC22-CS89)
  * Instructor: Prof. J Mukhopadhyay

* Indian Institute of Science - Fall 2020
  * Course: Stochastic Models & Applications (E1-222)
  * Instructor: [Prof. P S Sastry](https://ee.iisc.ac.in/sastry-p-s/){:target="_blank"}

Relevant Courses
------
* Computer Vision
* Stochastic Models and Applications
* Linear and Non-linear Optimization
* Convex Optimization
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
