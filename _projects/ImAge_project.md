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

<div class="row">
    <div class="col-12 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/image_workflow.png" title="ImAge Workflow" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-12 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/image_results.png" title="ImAge Results" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: ImAge workflow overview. right: Example of ImAge results showing age prediction.
</div>

The ImAge project introduces a novel approach to quantifying aging and rejuvenation through advanced image analysis techniques. Our method leverages state-of-the-art machine learning algorithms to extract meaningful features from cellular images, providing a robust measure of biological age.

The workflow consists of four main steps:

1. Illumination correction
2. Nuclei segmentation
3. Image feature extraction
4. ImAge axis construction

The ImAge project is available on GitHub. We believe that this tool will contribute significantly to our understanding of aging processes and aid in the development of interventions to promote healthy aging.

For more details on the methodology and applications of ImAge, please refer to our publication:

Alvarez-Kuglen, M., Ninomiya, K., Qin, H. et al. ImAge quantitates aging and rejuvenation. Nat Aging 4, 1308–1327 (2024). [https://doi.org/10.1038/s43587-024-00685-1](https://doi.org/10.1038/s43587-024-00685-1)

We invite researchers and developers to explore, use, and contribute to the ImAge project, furthering our collective understanding of aging and rejuvenation.
