---
layout: page
title: Bijou Espresso Machine
description: A portafilter espresso machine designed from the grounds up.
img: assets/img/bijou.png
importance: 3
category: fun
---

Bijou is built from scrap parts and based around an E61 group-head. Other than commonly seen in commercial E61 based machines, 
Bijou does not rely on a boiler but uses two in-line tank-less water heaters. The first is used to bring the water up to 90°C and the second can be put in series to increase the temperature 
to 120°C for the steam-head.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/bijou_pumps.png" title="bijou piping" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The internals of Bijou.
</div>

The electronics are based on an STM32F405 ARM micro-controller. The firmware is written in Rust and uses freeRTOS (C-wrapper).
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/bijou_electronics.png" title="bijou electronics" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The electronics of Bijou.
</div>
