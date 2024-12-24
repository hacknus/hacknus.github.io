---
layout: page
title: Open-Source UPS
description: A 12V uninterruptible power supply designed to be used for usage in home applications with NAS devices.
img: assets/img/ups_render.png
importance: 3
category: fun
---

UPS are commonly used in server applications to protect against power outages. For home applications, for example to protect a NAS, small Uninterruptible Power Supplies (UPS) do exist, but they all lack the USB HID communication to shut down the NAS/Server/Host when the battery gets low.
For small scale applications like Synology NAS products that operate at 12V, there currently exists no UPS product that is able to buffer the power and communicate over USB when the battery level gets critically low.
Only high voltage solutions (110V or 230V) exist, which also include an inverter and are thus much less efficient and overpowered for a simple 12V Synology NAS.
This is a simple, open source UPS, based around an STM32F405 and written in Rust.
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/ups_electronics_2.png" title="UPS electronics close up" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Electronics close up of the UPS.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/ups_render.png" title="UPS inside view" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Inside view of the UPS.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/ups_back_view.png" title="UPS back view" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Back view of the UPS.
</div>
The hardware is essentially just a charging circuit where the remaining capacity is monitored by the MCU.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/ups_electronics.png" title="UPS electronics close up" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Electronics close up of the UPS.
</div>
All files are documented in [this repository](https://github.com/hacknus/open-source-ups).