---
layout: page
title: Research
description: Josh Myers-Deans's research
---



#### <u>Semantic Pixel Distances for Image Editing</u>
Many image editing techniques make processing decisions based on measures of similarity between pairs of pixels. Traditionally, pixel similarity is measured using a simple L2 distance on RGB or luminance values. In this work,we explore a richer notion of similarity based on feature embeddings learned by convolutional neural networks. We propose to measure pixel similarity by combining distance in a semantically-meaningful feature embedding with traditional color difference. Using semantic features from the penultimate layer of an off-the-shelf semantic segmentation model, we evaluate our distance measure in two image editing applications. A user study shows that incorporating semantic distances into content-aware resizing via seam carving produces improved results. Off-the-shelf semantic features are found to have mixed effectiveness in content-based range masking, suggesting that training better general-purpose pixel embeddings presents a promising future direction for creating semantically-meaningful feature spaces that can be used in a variety of applications.

##### Citation  
@inproceedings{Myers-Dean_2020_CVPR_Workshops,
    title = {Semantic Pixel Distances for Image Editing},
    author = {Josh Myers-Dean and Scott Wehrwein},
    booktitle = {The IEEE Conference on Computer Vision and Pattern Recognition (CVPR) Workshops},
    month = {June},
    year = {2020}
}

click here for the most recent version of the paper]({{ BASE_PATH}}/pages/working_papers/semdist.pdf)


<!-- Note: this is how to write a comment in HTML. Everything in here won't show up on your webpage.-->

<!--
To increase the size of the title, use fewer # in front of the paper title.
To decrease the size of the title, use more #. 
To remove the italics, remove the * before and after the description
To remove the underline from the title, remove the <u> tags (<u> and </u>)
-->
