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
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/image_workflow.jpg" title="ImAge Workflow" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/image_results.jpg" title="ImAge Results" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/image_application.jpg" title="ImAge Application" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: ImAge workflow overview. Middle: Example of ImAge results showing age prediction. Right: Application of ImAge in a research setting.
</div>

The ImAge project introduces a novel approach to quantifying aging and rejuvenation through advanced image analysis techniques. Our method leverages state-of-the-art machine learning algorithms to extract meaningful features from cellular images, providing a robust measure of biological age.

The workflow consists of four main steps:

1. Illumination correction
2. Nuclei segmentation
3. Image feature extraction
4. ImAge axis construction

This comprehensive approach allows for accurate assessment of chromatin and epigenetic age, offering new insights into the aging process and potential rejuvenation strategies.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/image_comparison.jpg" title="ImAge vs Traditional Methods" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/image_future.jpg" title="Future Applications" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: Comparison of ImAge results with traditional aging assessment methods. Right: Potential future applications of ImAge in personalized medicine and anti-aging research.
</div>

Our research has demonstrated the power and versatility of ImAge in various contexts, from basic research to potential clinical applications. The tool's ability to provide single-cell resolution of biological age opens up new avenues for studying aging heterogeneity within tissues and organisms.

The ImAge project is open-source and available on GitHub, encouraging collaboration and further development within the scientific community. We believe that this tool will contribute significantly to our understanding of aging processes and aid in the development of interventions to promote healthy aging.

For more details on the methodology and applications of ImAge, please refer to our publication:

Alvarez-Kuglen, M., Ninomiya, K., Qin, H. et al. ImAge quantitates aging and rejuvenation. Nat Aging 4, 1308–1327 (2024). [https://doi.org/10.1038/s43587-024-00685-1](https://doi.org/10.1038/s43587-024-00685-1)

We invite researchers and developers to explore, use, and contribute to the ImAge project, furthering our collective understanding of aging and rejuvenation.
