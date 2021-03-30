---
layout: page
title: Research
description: Josh Myers-Deans's research
---



#### <u>Semantic Pixel Distances for Image Editing</u>
Many image editing techniques make processing decisions based on measures of similarity between pairs of pixels. Traditionally, pixel similarity is measured using a simple L2 distance on RGB or luminance values. In this work,we explore a richer notion of similarity based on feature embeddings learned by convolutional neural networks. We propose to measure pixel similarity by combining distance in a semantically-meaningful feature embedding with traditional color difference. Using semantic features from the penultimate layer of an off-the-shelf semantic segmentation model, we evaluate our distance measure in two image editing applications. A user study shows that incorporating semantic distances into content-aware resizing via seam carving produces improved results. Off-the-shelf semantic features are found to have mixed effectiveness in content-based range masking, suggesting that training better general-purpose pixel embeddings presents a promising future direction for creating semantically-meaningful feature spaces that can be used in a variety of applications.

##### Citation
<pre>@inproceedings{Myers-Dean_2020_CVPR_Workshops,
    title = {Semantic Pixel Distances for Image Editing},
    author = {Josh Myers-Dean and Scott Wehrwein},
    booktitle = {The IEEE Conference on Computer Vision and Pattern Recognition (CVPR) Workshops},
    month = {June},
    year = {2020}
}</pre>
[Project page](https://facultyweb.cs.wwu.edu/~wehrwes/semantic_pixels/)

[click here for the most recent version of the paper]({{ BASE_PATH}}/pages/working_papers/semdist.pdf)


#### <u>PETRA: Drug Engineering Through Rigidity Analysis</u>
Rational drug design aims to develop pharmaceutical agents that impart maximal therapeutic benefits via their interaction with their intended biological targets. In the past several decades, advances in computational tools that inform wet-lab techniques have aided the development of a wide variety of new medicines with high efficacies. Nonetheless, drug development remains a time and cost intensive process. In this work, we have developed a computational pipeline for assessing how individual atoms contribute to a ligand’s effect on the structural stability of a biological target. Our approach takes as input a protein-ligand resolved PDB structure file and systematically generates all possible ligand variants. We assess how the atomic-level edits to the ligand alter the drug’s effect via a graph theoretic rigidity analysis approach. We demonstrate, via four case studies of common drugs, the utility of our pipeline and corroborate our analyses with known biophysical properties of the medicines, as reported in the literature.

##### Citation  
<pre>
@article{Herr_2020,
title={PETRA: Drug Engineering via Rigidity Analysis},
volume={25},
ISSN={1420-3049},
url={http://dx.doi.org/10.3390/molecules25061304},
DOI={10.3390/molecules25061304},
number={6},
journal={Molecules},
publisher={MDPI AG},
author={Herr, Sam and Myers-Dean, Josh and Read, Hunter and Jagodzinski, Filip},
year={2020},
month={Mar},
pages={1304}}
</pre>
[click here for the most recent version of the paper]({{ BASE_PATH}}/pages/working_papers/petra.pdf)
#### <u>Towards Modeling Student Engagement with Interactive Computing Textbooks: An Empirical Study</u>
##### Citation
<pre>
@inproceedings{10.1145/3408877.3432361,
author = {Smith, David H. and Hao, Qiang and Hundhausen, Christopher D. and Jagodzinski, Filip and Myers-Dean, Josh and Jaeger, Kira},
title = {Towards Modeling Student Engagement with Interactive Computing Textbooks: An Empirical Study},
year = {2021},
isbn = {9781450380621},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3408877.3432361},
doi = {10.1145/3408877.3432361},
abstract = {Interactive textbooks have great potential to increase student engagement with the course content which is critical to effective learning in computing education. Prior research on digital textbooks and interactive visualizations contributes to our understanding of student interactions with visualizations and modeling textbook knowledge concepts. However, research investigating student usage of interactive computing textbooks is still lacking. This study seeks to fill this gap by modeling student engagement with a Jupyter-notebook-based interactive textbook. Our findings suggest that students' active interactions with the presented interactive textbook, including changing, adding, and executing code in addition to manipulating visualizations, are significantly stronger in predicting student performance than conventional reading metrics. Our findings contribute to a deeper understanding of student interactions with interactive textbooks and provide guidance on the effective usage of said textbooks in computing education.},
booktitle = {Proceedings of the 52nd ACM Technical Symposium on Computer Science Education},
pages = {914–920},
numpages = {7},
keywords = {learning analytics, jupyter notebook, interactive textbook, interaction behavior modeling, visualization},
location = {Virtual Event, USA},
series = {SIGCSE '21}
}
</pre>
