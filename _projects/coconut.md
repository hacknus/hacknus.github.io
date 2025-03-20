---
layout: page
title: COCoNuT
description: COCoNuT (Characteristic Observation of Cometary Nuclei using THz-spectroscopy) is a vacuum chamber designed to simulate the conditions found on comets. It is used to investivate the application of THz time domain spectroscopy on cometary analogues/samples.
img: assets/img/coconut.png
importance: 1
category: work
related_publications: true
---

COCoNuT (Characteristic Observation of Cometary Nuclei using THz-spectroscopy) is an experimental setup consisting of a THz spectro-goniometer in a vacuum chamber along with a cryo-cooler intended for cooling down samples rich in ices expected in cometary environments. This setup allows use of THz time domain spectroscopy on analogues including refractory materials in the spectral range from 0.1 THz to 5.5 THz with a spectral resolution of up to 0.005 THz. Since the optical setup is mounted on a precision controlled $x$/$y$-stage, imaging or spatial averaging can be performed.
In this work, we present the design decisions and selection of components. Furthermore, the commissioning of the setup is described and the capabilities are shown.
The system can reach pressures of $10^{-7}$ mbar and temperatures of 50 K. For 2D scanning a spatial resolution of $0.3$ line-pair per mm is obtained.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/coconut.png" title="Overview COCoNuT." class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Overview of COCoNuT.
</div>

The design and commissioning of this setup is documented in this publication {% cite stoeckli_coconut_2025 %}.

The setup is controlled by the [Electronics Unit (ELU)](https://hacknus.github.io/projects/elu/).
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/elu_render.png" title="Electronics Unit (ELU) that controls COCoNuT." class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Electronics Unit (ELU) that controls COCoNuT.
</div>

The antennas of the THz spectrometer are placed on a goniometer and $x$/$y$ stage.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/coconut_optics.png" title="Optics of COCoNuT." class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Optics of COCoNuT.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/coconut_beam.png" title="Beam of COCoNuT." class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The optical setup of COCoNuT. The goniometer is shown in transmission mode and the 2D stage is centered. The beam is indicated in red, going through the center of the sample holder, which is connected to the cryo-cooler.
</div>


