---
title: LIGO
description: LIGO
headingDivider: 2
transition: fade 200ms
theme: gaia
class:
  - invert
---

## LIGO

<!-- _class: lead invert -->

#### Laser Interferometer Gravitational-Wave Observatory

The National Science Foundation
Caltech and MIT



## TOC

<style>
  section { background-color: "#ccaa00"; }
  section.lead h1 { text-align: center; }
</style>

- Theory
    - Gravitational wave
    - Detection
- Setup
- Observation
- Conclusion


## Theory - Gravitational wave

* General Relativity
    - Einstein's equation
    - $R_{\mu\nu} - {1 \over 2} R g_{\mu\nu} = {8 \pi G \over c^4} T_{\mu\nu}$
* Lagrangean formulation
    - Einstein-Hilbert action
    - $S_{EH} = {1 \over 16 \pi G} \int \sqrt{-g} R d^4x$
* Linearlize it
    - $g_{\mu\nu} = \eta_{\mu\nu} + h_{\mu\nu}$

## Theory - Gravitational wave

- Transform
    - $x^\mu \longrightarrow x'^\mu = x^\mu + \xi^\mu(x)$
    - $h_{\mu\nu} \longrightarrow h_{\mu\nu} = h'_{\mu\nu} - \partial_\mu \xi_\nu - \partial_\nu \xi_\nu$
* Convenient gauge transformation
    - $\partial^\mu \bar{h}_{\mu\nu} \longrightarrow (\partial^\nu \bar{h}_{\mu\nu})' = \partial^\nu h_{\mu\nu} - \square\xi_\mu$
* Fix gauge (transverse-traceless gauge)
    - $h^{0 \mu} = 0, h^i_i = 0, \partial^i h_{ij} = 0$

## Theory - Gravitational wave

- Transverse-traceless gauge
    - $\square h_{\mu\nu}^{TT} = 0$
* Solutions
    - $h_{ij}^{TT}(x) = \epsilon_{ij}(\boldsymbol{k})e^{i k_\mu x^\mu}$
* Impose $\partial^i h_{ij} = 0$
    - $k^i h_{ij} = 0$
    - $k^\mu = (\omega, \boldsymbol{k})$

## Theory - Gravitational wave

- ${\boldsymbol{k} \over \left| k \right|} = \hat{\boldsymbol{z}}$
- $h_{ij}^{TT}(t, z) = \left( \matrix{h_+ & h_x & 0 \cr h_x & - h_+ & 0 \cr 0 & 0 & 0} \right) \cos[\omega(t + z)]$


## Ripples in Spacetime Pond

<style scoped>
  img {
      display: block;
      margin: auto;
  }
  p {
      font-size: 0.5rem;
  }
</style>

[![](./assets/Ripples_in_Spacetime_Pond.jpg)](./assets/Ripples_in_Spacetime_Pond.mp4)


LIGO Lab Caltech : MIT
https://www.youtube.com/watch?v=zLAmF0H-FTM

## Difficulty

- $10^{-19}m$
- 10,000 times smaller than a proton

## Basic Michelson Interferometer

![bg right 95%](./assets/Basic_michelson_labeled.jpg)

1) L-shaped
2) Mirrors
3) Photodetector

## Arm length

![bg right 95%](./assets/Basic_michelson_labeled.jpg)

* Longer is better
* Arm length ~ 4km
* <-> 1.3m
    - by Michelson and Morley
    - to study Aether
* But...
* 4km is still too short to detect gravitational wave


## Fabry Parot cavities

![bg right 95%](./assets/Basic_michelson_with_FP_labeled.jpg)

* More mirrors
* 300 times
* 4km x 300 = 1,200km
* But...
* We need more power
    - 40W vs 750kW

## Power Recycling Mirror

![bg right 95%](./assets/Basic_michelson_with_FP_and_PR_labeled.jpg)

* Yet another mirror
* _Nearly all_ of the laser light goes the path to the PR mirror

## Initial LIGO

- Operated for 9 years (2002 - 2010)
- Never detected gravitational waves

## Advanced LIGO

- Built taking 7 years
    -  2008 - 2015
* Better mirrors
* Better suspension
* Better seismic isolation
* 10 times more sensitive than the initial LIGO

## Advanced LIGO

![bg right 95%](./assets/iLIGO_vs_aLIGO_susp_comparison_w_caption.jpg)

- Built taking 7 years
    - 2008 - 2015
- Better mirrors
- Better suspension
- Better seismic isolation
- 10 times more sensitive than the initial LIGO

## First Observation - GW150914

<style scoped>
  img { display: block; margin: auto; }
  p { font-size: 0.5rem; }
</style>

![](./assets/LIGO_measurement_of_gravitational_waves.png)

Made on 14 September 2015
Announced on 11 February 2016

## Another detection - GW170817

<style scoped>
  img { display: block; margin: auto; }
  p { font-size: 0.5rem; }
</style>

[![](./assets/First_LIGO_Virgo_detection.jpg)](./assets/First_LIGO_Virgo_detection_of_a_binary_neutron_star_merger.mp4)


First LIGO/Virgo detection of a binary neutron star merger (GW170817)
https://www.youtube.com/watch?v=_SQbaILipjY
© Alex Nitz/Max Planck Institute for Gravitational Physics/LIGO

Time-frequency representation (spectrogram) of the LIGO-Hanford and LIGO-Livingston data. Your ears are the two LIGO detectors. The observed data is revealed in real time, accompanied by the audio presentation of the plotted data.


## Conclusion

- Laser Interferometer is good to...
* Detect a gravitational wave

## References

- LIGO Caltech
    - https://www.ligo.caltech.edu/page/ligos-ifo
- LIGO (Wikipedia)
    - https://en.wikipedia.org/wiki/LIGO
- First observation of gravitational waves (Wikipedia)
    - https://en.wikipedia.org/wiki/First_observation_of_gravitational_waves
