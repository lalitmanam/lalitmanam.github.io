---
title: "Leveraging Camera Triplets for Efficient and Accurate Structure-from-Motion"
collection: publications
permalink: /publications/2024-06-08-camtripsfm-cvpr2024
excerpt: 'Accepted as poster.'
date: 2024-06-08
venue: 'IEEE/CVF Conference on Computer Vision and Pattern Recognition'
year: '2024'
authors: 'Lalit Manam, Venu Madhav Govindu'
projectpage: 'https://ee.iisc.ac.in/cvlab/research/camtripsfm/'
paperurl: 'https://ee.iisc.ac.in/cvlab/research/camtripsfm/cam_triplets_sfm.pdf'

---
<!-- paperurl: 'https://ee.iisc.ac.in/cvlab/research/tasensitivity/ta_sensitivity.pdf'
bib: 'https://scholar.googleusercontent.com/scholar.bib?q=info:4HgGdDwKem0J:scholar.google.com/&output=citation&scisdr=ClG-4mYUEJvRycAzneA:AFWwaeYAAAAAZWs1heDQSFMpDJAKn8ZGEXcKooc&scisig=AFWwaeYAAAAAZWs1hcfDFdV62hU9kxKFJddsrkY&scisf=4&ct=citation&cd=-1&hl=en'
-->
<!-- poster: 'https://dbp1994.github.io/publications/files/ICASSP_ALS_2018_poster.pdf' -->
<!-- projectpage: 'https://ee.iisc.ac.in/cvlab/research/tasensitivity/' -->
<!-- code: 'https://github.com/RaghavSomani/CMTRF' -->

In Structure-from-Motion (SfM), the underlying viewgraphs of unordered image collections generally have a highly redundant set of edges that can be sparsified for efficiency without significant loss of reconstruction quality. Often, there are also false edges due to incorrect image retrieval and repeated structures (symmetries) that give rise to ghosting and superimposed reconstruction artifacts. We present a unified method to simultaneously sparsify the viewgraph and remove false edges. We propose a scoring mechanism based on camera triplets that identifies edge redundancy as well as false edges. Our edge selection is formulated as an optimization problem which can be provably solved using a simple thresholding scheme. This results in a highly efficient algorithm which can be incorporated as a pre-processing step into any SfM pipeline, making it practically usable. We demonstrate the utility of our method on generic and ambiguous datasets that cover the range of small, medium and large-scale datasets, all with different statistical properties. Sparsification of generic datasets using our method significantly reduces reconstruction time while maintaining the accuracy of the reconstructions as well as removing ghosting artifacts. For ambiguous datasets, our method removes false edges, thereby avoiding incorrect superimposed reconstructions.

<!--
The paper has been accepted at [ICASSP 2018](https://ieeexplore.ieee.org/document/8461836){:target="_blank"}.

Abstract:

Relevant links:
1. [Paper](https://ieeexplore.ieee.org/document/8461836){:target="_blank"}
2. [Poster](https://dbp1994.github.io/publications/files/ICASSP_ALS_2018_poster.pdf){:target="_blank"}


<iframe width="560" height="315" src="https://www.youtube.com/embed/KyHUan_7YnQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<figcaption>Oral presentation at WSDM'19</figcaption> -->
