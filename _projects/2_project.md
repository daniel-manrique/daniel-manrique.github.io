---
layout: page
title: Topological data analysis for neuroscience
description: Implementation of Topological Data Analysis (TDA) to examine the spatial arrangement/distribution of cells. 
img: assets/img/TDAimg.jpg
importance: 2
category: image analysis
---

Topological data analysis (TDA) is an approach that uses algebraic topology to analyze complex data sets, including point clouds. With TDA, the user can evaluate the degree of noise, variability, and complexity, as well as identifying topological features such as holes, loops, and voids in the point clouds at different scales. This approach is based on tools like vietoris-rips complexes and persistent homology that allow to visualize complex topological structures.
 
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/TDAimg.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Example of Vietoris-Rips complexes.
</div>

A first approach is available in this [prepint](https://www.biorxiv.org/content/10.1101/2023.10.04.560910v1) and its corresponding [repository](https://github.com/daniel-manrique/Stroke_GlialScar_PPA-TDA). If you have any ideas or want to implement this approach to your research, please feel free to contact me. I also recommend to get in touch with my colleague [Dhananjay Bhaskar](http://www.dhananjaybhaskar.com/) for this matter. 
