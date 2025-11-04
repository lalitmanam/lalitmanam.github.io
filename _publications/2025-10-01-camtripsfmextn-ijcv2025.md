---
title: "Unifying Viewgraph Sparsification and Disambiguation of Repeated Structures in Structure-from-Motion"
collection: publications
permalink: /publications/2025-10-01-camtripsfmextn-ijcv2025
excerpt: 'In Press'
date: 2025-10-01
venue: 'International Journal of Computer Vision'
year: '2025'
authors: 'Lalit Manam, Venu Madhav Govindu'
# projectpage: 'https://ee.iisc.ac.in/cvlab/research/camtripsfm/'
# paperurl: 'https://ee.iisc.ac.in/cvlab/research/camtripsfm/cam_triplets_sfm.pdf'

---
<!-- paperurl: 'https://ee.iisc.ac.in/cvlab/research/tasensitivity/ta_sensitivity.pdf'
bib: 'https://scholar.googleusercontent.com/scholar.bib?q=info:4HgGdDwKem0J:scholar.google.com/&output=citation&scisdr=ClG-4mYUEJvRycAzneA:AFWwaeYAAAAAZWs1heDQSFMpDJAKn8ZGEXcKooc&scisig=AFWwaeYAAAAAZWs1hcfDFdV62hU9kxKFJddsrkY&scisf=4&ct=citation&cd=-1&hl=en'
-->
<!-- poster: 'https://dbp1994.github.io/publications/files/ICASSP_ALS_2018_poster.pdf' -->
<!-- projectpage: 'https://ee.iisc.ac.in/cvlab/research/tasensitivity/' -->
<!-- code: 'https://github.com/RaghavSomani/CMTRF' -->

In Structure-from-Motion (SfM), viewgraphs obtained from pairwise camera relationships generally have a high redundancy of edges that can be sparsified while maintaining reconstruction quality. Due to incorrect image matching and repeated structures in scenes (symmetries), false edges are often present in the viewgraphs, which gives rise to ghosting and superimposed reconstruction artifacts. In this paper, we present a unified method to simultaneously perform the tasks of viewgraph sparsification via redundant edge removal and disambiguation by removing false edges. We design an edge scoring mechanism to determine redundant and false edges based on triples of cameras that have either two or three edges connecting the three cameras. Our edge selection is formulated as an optimization problem whose optimum can be obtained using a simple thresholding scheme. This results in a highly efficient algorithm which can be applied to any viewgraph without any restriction on its topology. Our algorithm can be incorporated into any SfM pipeline as a pre-processing step, making it modular. We demonstrate the efficacy of our method on publicly available datasets, with a significant reduction in reconstruction time while maintaining reconstruction quality and removing ghosting artifacts on generic datasets. Our method also removes false edges from ambiguous datasets, thereby avoiding incorrect superimposed reconstructions.

<!--
The paper has been accepted at [ICASSP 2018](https://ieeexplore.ieee.org/document/8461836){:target="_blank"}.

Abstract:

Relevant links:
1. [Paper](https://ieeexplore.ieee.org/document/8461836){:target="_blank"}
2. [Poster](https://dbp1994.github.io/publications/files/ICASSP_ALS_2018_poster.pdf){:target="_blank"}


<iframe width="560" height="315" src="https://www.youtube.com/embed/KyHUan_7YnQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<figcaption>Oral presentation at WSDM'19</figcaption> -->
