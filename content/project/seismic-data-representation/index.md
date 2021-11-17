---
url_pdf: ""
title: Seismic data representation
summary: We model seismic data by assuming that it satisfies the wave equation and solving a non-linear least-squares optimisation problem.
url_video: ""
external_link: ""
url_slides: ""
subtitle: University of Bath, Schlumberger (2016)
tags:
  - Industry

image:
  caption: "Seismic imaging technique."
  focal_point: Smart
url_code: ""
---
This research project corresponds to my MSc dissertation at the [University of Bath](https://www.bath.ac.uk/) in collaboration with the oil services company [Schlumberger](https://www.slb.com/).

Supervisors: [Prof. Chris Budd](https://people.bath.ac.uk/mascjb/) (University of Bath), [Dr Can Evren Yarman](https://www.researchgate.net/profile/Evren-Yarman) (Schlumberger)

## **Abstract**
Assuming that the seismic data verifies the acoustic wave equation, its Fourier transform resides within a signal cone. Functions whose Fourier transform lives within a signal cone are called C-limited functions. Thus the seismic data can be modeled as a convolution in terms of the kernel for C-limited functions. This kernel, K_C, is defined as the inverse Fourier transform of the characteristic function over the signal cone. It decays slowly in space and time which limits its usage. To overcome this we introduce the C-Gaussian function, K_G, whose Fourier transform decays exponentially with respect to slowness and frequency.

To model the seismic data we consider a space-time variable signal cone. The variability of the signal cone is obtained through scaling, slanting and translation of the kernel. Due to the hyperbolic nature of the wave equation, a temporal hyperbolic change of variables is implemented and compared with a parabolic change of variables. The discrete number of parameters involved in the change of variables and in the transformations of the kernel previously described are optimally obtained by solving a nonlinear least squares optimisation problem. This minimisation problem is solved using a Greedy algorithm which requires solving several nonlinear least squares problems using steepest descent methods.

Finally, an analysis of the performance for both changes of variables (hyperbolic and parabolic) is undertaken in order to compare their computational speeds, convergence rates and residuals.

**Keywords**: wave equation, signal cone, kernel, seismic data, Fourier transform, nonlinear least squares, steepest descent, Greedy methods.
