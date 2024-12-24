---
layout: page
title: Electronics Unit
description: The ELU is the main control unit for the COCoNuT experiment.
img: assets/img/elu_render.png
importance: 2
category: work
---
The electronics unit (ELU) of [COCoNuT](https://hacknus.github.io/projects/coconut/) is based on an STM32F405 micro-controller. Motors, pumps and heaters are controlled by the ELU while temperatures and pressures can be logged. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/elu_render.png" title="Close up view of the Electronics Unit (ELU) that controls COCoNuT." class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Close up view of the Electronics Unit (ELU) that controls COCoNuT.
</div>

The different tasks are managed by extension boards that provide the interface to other devices, e.g. pumps. The extension boards can be attached on the back in the various slots.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/elu_complete.png" title="Complete view of the Electronics Unit (ELU) that controls COCoNuT." class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Overview of the Electronics Unit (ELU) with extension cards in the back.
</div>