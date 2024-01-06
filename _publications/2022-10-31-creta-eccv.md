---
title: "Correspondence reweighted translation averaging"
collection: publications
permalink: /publications/2022-10-31-creta-eccv
excerpt: 'Accepted as poster.'
date: 2022-10-31
venue: 'European Conference on Computer Vision (ECCV)'
year: '2022'
authors: 'Lalit Manam, Venu Madhav Govindu'
projectpage: 'https://ee.iisc.ac.in/cvlab/research/creta/'
paperurl: 'https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136930053.pdf'
bib: 'https://scholar.googleusercontent.com/scholar.bib?q=info:7LkdqhoMSKEJ:scholar.google.com/&output=citation&scisdr=ClG-4mYUEJvRycA24ZE:AFWwaeYAAAAAZWsw-ZGBiE4X6SuhdlSGN3a9i_0&scisig=AFWwaeYAAAAAZWsw-aJFEFikO8WrUCKAf7tYJp0&scisf=4&ct=citation&cd=-1&hl=en'

---
<!-- poster: 'https://dbp1994.github.io/publications/files/ICASSP_ALS_2018_poster.pdf' -->
<!--  -->
<!-- code: 'https://github.com/RaghavSomani/CMTRF' -->

Translation averaging methods use the consistency of input translation directions to solve for camera translations. However, translation directions obtained using epipolar geometry are error-prone. This paper argues that the improved accuracy of translation averaging should be leveraged to mitigate the errors in the input translation direction estimates. To this end, we introduce weights for individual correspondences which are iteratively refined to yield improved translation directions. In turn, these refined translation directions are averaged to obtain camera translations. This results in an alternating approach to translation averaging. The modularity of our framework allows us to use existing translation averaging methods and improve their results. The efficacy of the scheme is demonstrated by comparing performance with state-of-the-art methods on a number of real-world datasets. We also show that our approach yields reasonably good 3D reconstructions with straightforward triangulation, i.e. without any bundle adjustment iterations.

<!--
The paper has been accepted at [ICASSP 2018](https://ieeexplore.ieee.org/document/8461836){:target="_blank"}.

Abstract:

Relevant links:
1. [Paper](https://ieeexplore.ieee.org/document/8461836){:target="_blank"}
2. [Poster](https://dbp1994.github.io/publications/files/ICASSP_ALS_2018_poster.pdf){:target="_blank"}


<iframe width="560" height="315" src="https://www.youtube.com/embed/KyHUan_7YnQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<figcaption>Oral presentation at WSDM'19</figcaption> -->
