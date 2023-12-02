---
title: "Adaptive annealing for robust geometric estimation"
collection: publications
permalink: /publications/2023-06-31-adanroge-cvpr
excerpt: 'Accepted as poster.'
date: 2023-06-31
venue: 'IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)'
year: '2023'
authors: 'Chitturi Sidhartha, Lalit Manam, Venu Madhav Govindu'
projectpage: 'https://ee.iisc.ac.in/cvlab/research/adanroge/'
paperurl: 'https://openaccess.thecvf.com/content/CVPR2023/papers/Sidhartha_Adaptive_Annealing_for_Robust_Geometric_Estimation_CVPR_2023_paper.pdf'
bib: 'https://scholar.googleusercontent.com/scholar.bib?q=info:E-NVbTwnNl4J:scholar.google.com/&output=citation&scisdr=ClG-4mYUEJvRycAy3i8:AFWwaeYAAAAAZWs0xi8jRJUzji63qfPqc4AdcBU&scisig=AFWwaeYAAAAAZWs0xi-qOPSEokC6D7P5GQNT0LA&scisf=4&ct=citation&cd=-1&hl=en'

---
<!-- poster: 'https://dbp1994.github.io/publications/files/ICASSP_ALS_2018_poster.pdf' -->
<!--  -->
<!-- code: 'https://github.com/RaghavSomani/CMTRF' -->

Geometric estimation problems in vision are often solved via minimization of statistical loss functions which account for the presence of outliers in the observations. The corresponding energy landscape often has many local minima. Many approaches attempt to avoid local minima by annealing the scale parameter of loss functions using methods such as graduated non-convexity (GNC). However, little attention has been paid to the annealing schedule, which is often carried out in a fixed manner, resulting in a poor speed-accuracy trade-off and unreliable convergence to the global minimum. In this paper, we propose a principled approach for adaptively annealing the scale for GNC by tracking the positive-definiteness (i.e. local convexity) of the Hessian of the cost function. We illustrate our approach using the classic problem of registering 3D correspondences in the presence of noise and outliers. We also develop approximations to the Hessian that significantly speeds up our method. The effectiveness of our approach is validated by comparing its performance with state-of-the-art 3D registration approaches on a number of synthetic and real datasets. Our approach is accurate and efficient and converges to the global solution more reliably than the state-of-the-art methods.

<!--
The paper has been accepted at [ICASSP 2018](https://ieeexplore.ieee.org/document/8461836){:target="_blank"}.

Abstract:

Relevant links:
1. [Paper](https://ieeexplore.ieee.org/document/8461836){:target="_blank"}
2. [Poster](https://dbp1994.github.io/publications/files/ICASSP_ALS_2018_poster.pdf){:target="_blank"}


<iframe width="560" height="315" src="https://www.youtube.com/embed/KyHUan_7YnQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<figcaption>Oral presentation at WSDM'19</figcaption> -->
