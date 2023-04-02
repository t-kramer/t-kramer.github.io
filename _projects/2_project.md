---
layout: page
title: NV & airborne transmission
description: Minimising airborne transmission of micro-particles by indoor air distribution control.
img: assets/img/ecr-a.png
importance: 2
category: research
---

Natural ventilation can be an effective strategy to minimise the airborne transmission of pathogenic mirco-particles in indoor environments. Unfortunately, an accurate assessment of indoor air flow usually requires the use of complex CFD simulation software. This complicates the evaluation of the effectiveness of natural ventilation strategies, in particular for inexperienced CFD users.

In this project under the lead of [Dr Sara Omrani](https://www.qut.edu.au/about/our-people/academic-profiles/s.omrani) we trained a Machine Learning model on indoor air distribution data created by simulating numerous window/room configurations and linking OpenFOAM with parametric design software. Each scenario produced a detailed mesh of CFD results, which was then used to train the ML model and to make design recommendations based on the input geometry within seconds.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/ecr-a.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/ecr-b.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/ecr-c.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/ecr-d.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/ecr-e.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/ecr-f.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This is a selection of posters that I presented at the annual QUT Early Career Researchers Symposium in 2021.
</div>

So far, we've only tested a limited number of parameters and scenarios and are aiming to generate larger CFD-based datasets to enhance the capabilities of the model.