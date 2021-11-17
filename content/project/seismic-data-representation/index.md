---
slides: example
url_pdf: ""
title: Seismic data representation
summary: An example of using the in-built project page.
url_video: ""
date: 2016-09-11T02:40:23.615Z
external_link: ""
url_slides: ""
subtitle: University of Bath, Schlumberger
tags:
  - Industry

image:
  caption: ""
  focal_point: Smart
url_code: ""
---
This research project corresponds to my MSc dissertation at the University of Bath in collaboration with the oil services company Schlumberger.

## **Abstract**
Assuming that the seismic data verifies the acoustic wave equation, its Fourier transform resides within a signal cone. Functions whose Fourier transform lives within a signal cone are called C-limited functions. Thus the seismic data can be modeled as a convolution in terms of the kernel for C-limited functions. This kernel, KC, is defined as the inverse Fourier transform of the characteristic function over the signal cone. It decays slowly in space and time which limits its usage. To overcome this we introduce the C-Gaussian function, KG, whose Fourier transform decays exponentially with respect to slowness and frequency.

To model the seismic data we consider a space-time variable signal cone. The variability of the signal cone is obtained through scaling, slanting and translation of the kernel. Due to the hyperbolic nature of the wave equation, a temporal hyperbolic change of variables is implemented and compared with a parabolic change of variables. The discrete number of parameters involved in the change of variables and in the transformations of the kernel previously described are optimally obtained by solving a nonlinear least squares optimisation problem. This minimisation problem is solved using a Greedy algorithm which requires solving several nonlinear least squares problems using steepest descent methods.

Finally, an analysis of the performance for both changes of variables (hyperbolic and parabolic) is undertaken in order to compare their computational speeds, convergence rates and residuals.

**Keywords**: wave equation, signal cone, kernel, seismic data, Fourier transform, nonlinear least squares, steepest descent, Greedy methods.
