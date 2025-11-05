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
I am currently interested in 3D reconstruction problems in computer vision, primarily on large-scale structure-from-motion and SLAM pipelines. My recent work has been on developing methods for efficient and reliable estimation of camera motions in structure-from-motion. Previously, I was involved in the development of impulse noise removal techniques from colour images.

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
I am working on 3D reconstruction problems in computer vision, i.e. to build a 3D representation of a scene from images. Depending on the application, it can be broadly classified as follows:
- Structure-from-Motion (SfM)<br>
  Build a 3D model of a scene from a collection of images.
  
  ![SfM Model](\images\Vitthala1.jpg){:height="40%" width="40%"}
  
- Simultaneous Localization and Mapping (SLAM)<br>
  Incrementally build a map of the environment from an image sequence, while simultaneously determining the camera position and orientation.
  
  ![SLAM Map](\images\Map.png){:height="50%" width="50%"}<br>

Depth cannot be recovered with a single image. Multiple images of the same scene are required to capture its 3D structure. The geometry of both problems is the same, as both applications utilize cameras. Building a 3D representation requires estimating the orientation/viewing direction as well as the position of the cameras. My current work focuses on estimating orientations (also called rotation averaging) and positions of the cameras (called translation averaging). 

Applications of SfM and SLAM algorithms also include 3D exploration of photo collections and phone-based augmented reality.

<!--
Publications
------

- **L. Manam**, V.M. Govindu, “Fusing directions and displacements in translation averaging,'' International Conference on 3D Vision (3DV), 2024
- **L. Manam**, V.M. Govindu, “Sensitivity in translation averaging,'' Neural Information Processing Systems (NeurIPS), 2023 [[project page](https://ee.iisc.ac.in/cvlab/research/tasensitivity/){:target="_blank"}]
- C. Sidhartha, **L. Manam**, V.M. Govindu, “Adaptive annealing for robust geometric estimation,'' IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), pp. 21929-21939, 2023 [[project page](https://ee.iisc.ac.in/cvlab/research/adanroge/){:target="_blank"}]
- **L. Manam**, V.M. Govindu, “Correspondence reweighted translation averaging," European Conference on Computer Vision (ECCV), pp. 56-72, 2022 [[project page](https://ee.iisc.ac.in/cvlab/research/creta/){:target="_blank"}]
- A. Roy, **L. Manam**, R.H. Laskar, “Removal of `Salt & Pepper' noise from color images using adaptive fuzzy technique based on histogram estimation," Multimedia Tools and Applications, vol. 79, no. 47, pp. 34851-34873, Dec. 2020
- A. Roy, **L. Manam** and R.H. Laskar, “Region adaptive fuzzy filter: an approach for removal of random valued impulse noise,” IEEE Transactions on Industrial Electronics, vol. 65, no. 9, pp. 7268-7278, Sept. 2018
- **L. Manam**, A. Roy, R. H. Laskar and F. A. Talukdar, “Removal of fixed valued impulse noise using global noise statistics based adaptive histogram fuzzy filter,” TENCON 2017 - IEEE Region 10 Conference, pp. 2231-2235, 2017
- A. Roy, J. Singha, **L. Manam**, R.H. Laskar, “Combination of adaptive vector median filter and weighted mean filter for removal of high density impulse noise from color images,” IET Image Processing, vol. 11, no. 6, pp. 352-361, Jan. 2017
--->

Experience
------
* Postdoctoral Researcher, Oct 2025 - Present<br>
[Mitsubishi Electric Research Labs](https://merl.com/){:target="_blank"}<br>
Cambridge, MA, USA<br>

Education
------
* Ph.D. & M.Tech.(Res), Aug 2018 - Mar 2025<br>
[Electrical Engineering](https://ee.iisc.ac.in/){:target="_blank"},<br>
[Indian Institute of Science](https://iisc.ac.in/){:target="_blank"}, Bengaluru, India<br>
Advisor: [Prof. Venu Madhav Govindu](https://ee.iisc.ac.in/venu-madhav-govindu/){:target="_blank"}

* B.Tech., Aug 2013 - Jun 2017<br>
Electronics and Communication Engineering,<br>
National Institute of Technology, Silchar, India

<!--
Work experience
------

* September 2017 - July 2018: Project Assistant
  * [Department of Electrical Engineering](http://www.ee.iisc.ac.in){:target="_blank"}
  * Mentors: [Dr. Prasanta Kumar Ghosh](http://www.ee.iisc.ac.in/faculty/prasantg/index.php){:target="_blank"}
  * Project Details:
--->

Talks/Tutorials/Lectures
------
* 04/2024 - Presented my recent works at [IISc EECS Symposium 2024](https://eecs.iisc.ac.in/EECS2024/)
* 04/2024 - Took a lecture on ‘3D Volumetric Rendering' in Computer Vision Course (E1-216), IISc
* 07/2023 - Presented a talk on ‘Solving Translation Averaging - Lessons for Engineers’ at [IISc EE Summer School 2023](https://ee.iisc.ac.in/summerschool2023/)
* 07/2023 - Took a tutorial on ‘3D Volumetric Rendering - Neural Radiance Fields’ at [IISc EE Summer School 2023](https://ee.iisc.ac.in/summerschool2023/)
* 04/2022 - Presented my work on Translation Averaging at [IISc EECS Symposium 2022](https://eecs.iisc.ac.in/EECS2022/student_abstracts.html#lalit_ee)

Teaching Assistantships
------

* Indian Institute of Science - Spring 2021-24
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

<!--
Relevant Courses
------
* Computer Vision
* Stochastic Models and Applications
* Linear and Non-linear Optimization
* Convex Optimization
* Machine Learning
-->

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
