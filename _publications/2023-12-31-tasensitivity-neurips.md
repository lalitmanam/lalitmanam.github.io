---
title: "Adaptive annealing for robust geometric estimation"
collection: publications
permalink: /publications/2023-12-31-tasensitivity-neurips
excerpt: 'Poster'
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


<!--
---
title: "Sensitivity in translation averaging"
collection: publications
permalink: /publications/2023-12-31-tasensitivity-neurips
excerpt: 'Poster'
date: 2023-12-31
venue: 'Neural Information Processing Systems (NeurIPS)'
year: '2023'
authors: 'Lalit Manam, Venu Madhav Govindu'
projectpage: 'https://ee.iisc.ac.in/cvlab/research/tasensitivity/'
paperurl: 'https://ee.iisc.ac.in/cvlab/research/tasensitivity/ta_sensitivity.pdf'
bib: 'https://scholar.googleusercontent.com/scholar.bib?q=info:4HgGdDwKem0J:scholar.google.com/&output=citation&scisdr=ClG-4mYUEJvRycAzneA:AFWwaeYAAAAAZWs1heDQSFMpDJAKn8ZGEXcKooc&scisig=AFWwaeYAAAAAZWs1hcfDFdV62hU9kxKFJddsrkY&scisf=4&ct=citation&cd=-1&hl=en'

---
<!-- poster: 'https://dbp1994.github.io/publications/files/ICASSP_ALS_2018_poster.pdf' -->
<!--  -->
<!-- code: 'https://github.com/RaghavSomani/CMTRF' -->

<!--
In 3D computer vision, translation averaging solves for absolute translations given a set of pairwise relative translation directions. While there has been much work on robustness to outliers and studies on the uniqueness of the solution, this paper deals with a distinctly different problem of sensitivity in translation averaging under uncertainty. We first analyze sensitivity in estimating scales corresponding to relative directions under small perturbations of the relative directions. Then, we formally define the conditioning of the translation averaging problem, which assesses the reliability of estimated translations based solely on the input directions. We give a sufficient criterion to ensure that the problem is well-conditioned. Subsequently, we provide an efficient algorithm to identify and remove combinations of directions which make the problem ill-conditioned while ensuring uniqueness of the solution. We demonstrate the utility of such analysis in global structure-from-motion pipelines for obtaining 3D reconstructions, which reveals the benefits of filtering the ill-conditioned set of directions in translation averaging in terms of reduced translation errors, a higher number of 3D points triangulated and faster convergence of bundle adjustment.
-->
<!--
The paper has been accepted at [ICASSP 2018](https://ieeexplore.ieee.org/document/8461836){:target="_blank"}.

Abstract:

Relevant links:
1. [Paper](https://ieeexplore.ieee.org/document/8461836){:target="_blank"}
2. [Poster](https://dbp1994.github.io/publications/files/ICASSP_ALS_2018_poster.pdf){:target="_blank"}


<iframe width="560" height="315" src="https://www.youtube.com/embed/KyHUan_7YnQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<figcaption>Oral presentation at WSDM'19</figcaption> -->
