---
layout: page
title: Point pattern analysis (PPA) for neuroscience
description: Implementation of Point pattern analysis (PPA) to examine the spatial arrangement/distribution of cells. 
img: assets/img/Pointanalysis.png
importance: 1
category: image analysis
---

I am exploring ways to incorporate Point patterns analysis (PPA) for the analysis of microscopy images in neuroscience. PPA allows the investigation of the spatial arrangement/distribution of cells, like neurons and neuroglia, in the healthy and disease central nervous system. Indeed, it has application in multiple biomedical fields. I perform point pattern analysis using the [spatstat](https://spatstat.org/download.html) package in R-programming language. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Pointanalysis.png" title="PPA" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Density kernel generated from point patterns.
</div>


A first approach is available in this [prepint](https://www.biorxiv.org/content/10.1101/2023.10.04.560910v1) and its corresponding [repository](https://github.com/daniel-manrique/Stroke_GlialScar_PPA-TDA). I also developed a protocol for Star Protocols (Cell Press) and its corresponding [repository](https://github.com/daniel-manrique/StarProtocol_PPA). If you have any ideas or want to implement this approach to your research, please feel free to contact me.

