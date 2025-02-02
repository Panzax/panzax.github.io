---
layout: page
title: ImAge - Quantifying Aging and Rejuvenation
description: Python-based tool for imaging-based chromatin and epigenetic age analysis
img: assets/img/ImAge_workflow.png
importance: 1
category: work
related_publications: true
---

ImAge is a computational tool designed to quantitate aging and rejuvenation through imaging-based chromatin and epigenetic age analysis. This project represents a significant advancement in the field of aging research, providing researchers with a powerful method to assess biological age at the single-cell level.

{% include figure.liquid loading="eager" path="assets/img/image_fig1.png" title="ImAge Workflow" class="img-fluid rounded z-depth-1" zoomable=true %}

<div class="caption">
    Figure 1 (taken from [ImAge paper](https://doi.org/10.1038/s43587-024-00685-1)): a, Graphical representation of the microscopic imaging of epigenetic landscapes workflow: nuclear isolation, immunofluorescence imaging, image preprocessing, nuclear segmentation, texture feature extraction and downstream analysis. b,c, Multidimensional scaling plots of CD3+ and CD3− subsets of PBMCs from C57BL/6NJ males aged from 1.7 to 32 months (1.7, 2.2, 5.3, 8.7, 15.1, 21, 22.3 and 32.2) (n = 2 per age group) based on 2D EMDS (b) and 3D HMDS (c) of 504 texture features. Each axis represents the score obtained from EMDS or HMDS indicated as EMDS1 and EMDS2 and HMDS1–HMDS3. Each data point was colored with its chronological age based on the color scale on the right side of the plot. d,e, Top, graphical representation of the method of ImAge axis construction; bottom, scatter-plots of ImAge versus chronological age for CD3+ subset (top), the CD3− subset (middle) and the whole population (PBMC) (bottom). d, ImAge axis constructed using the geodesic connecting the centroids of the youngest and oldest groups in Euclidean or hyperbolic space. e, ImAge axis constructed using linear SVM fit to the youngest and oldest groups. Pearson’s correlation (r) between ImAge and chronological age and P values.
</div>

The ImAge project introduces a novel approach to quantifying aging and rejuvenation through advanced image analysis techniques. Our method leverages state-of-the-art machine learning algorithms to extract meaningful features from cellular images, providing a robust measure of biological age.

The workflow consists of four main steps:

1. Illumination correction
2. Nuclei segmentation
3. Image feature extraction
4. ImAge axis construction

The ImAge project is available on GitHub. We believe that this tool will contribute significantly to our understanding of aging processes and aid in the development of interventions to promote healthy aging.

For more details on the methodology and applications of ImAge, please refer to our publication{% cite alvarez-kuglenImAgeQuantitatesAging2024 %}.

We invite researchers and developers to explore, use, and contribute to the ImAge project, furthering our collective understanding of aging and rejuvenation.
