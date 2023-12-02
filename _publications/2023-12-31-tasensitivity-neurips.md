---
title: "Sensitivity in translation averaging"
collection: publications
permalink: /publications/2023-12-31-tasensitivity-neurips
excerpt: 'Accepted as poster.'
date: 2023-09-31
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

In 3D computer vision, translation averaging solves for absolute translations given a set of pairwise relative translation directions. While there has been much work on robustness to outliers and studies on the uniqueness of the solution, this paper deals with a distinctly different problem of sensitivity in translation averaging under uncertainty. We first analyze sensitivity in estimating scales corresponding to relative directions under small perturbations of the relative directions. Then, we formally define the conditioning of the translation averaging problem, which assesses the reliability of estimated translations based solely on the input directions. We give a sufficient criterion to ensure that the problem is well-conditioned. Subsequently, we provide an efficient algorithm to identify and remove combinations of directions which make the problem ill-conditioned while ensuring uniqueness of the solution. We demonstrate the utility of such analysis in global structure-from-motion pipelines for obtaining 3D reconstructions, which reveals the benefits of filtering the ill-conditioned set of directions in translation averaging in terms of reduced translation errors, a higher number of 3D points triangulated and faster convergence of bundle adjustment.

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
