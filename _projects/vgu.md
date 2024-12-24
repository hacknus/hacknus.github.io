---
layout: page
title: Vacuum Gateway Unit
description: A vacuum-grade gateway (VGU) to read out local sensors inside a vacuum chamber and communicate with devices outisde.
img: assets/img/vgu_render.png
importance: 3
category: work
---
The Vacuum Gateway Unit (VGU) serves as a readout unit inside the vacuum chamber. Sensors and simple actuators or illumination sources can be placed inside the chamber and commands can be sent to the vacuum gateway over RS-232. This way the actuators control lines and I2C/SPI lines do not need to go over long cables through vacuum feedthroughs, which could make communication unreliable.
The main feature is the readout and PID heating of the IR sensor (MLX90614 or Heimann sensor) .

The electronics are based on an STM32F405 ARM micro-controller. The firmware is written in Rust and uses freeRTOS (C-wrapper).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/vgu_render.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Render of the VGU PCB.
</div>
