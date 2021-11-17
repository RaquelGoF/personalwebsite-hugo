---
url_pdf: "https://ora.ox.ac.uk/objects/uuid:df016039-4c40-43ca-91a6-ffe0575aae77"
title: Microsilica particle formation and growth
summary: Modelling the formation and growth of microsilica particles due to the combustion reaction of silicon monoxide with oxygen inside silicon furnaces.
url_video: ""
date: 2020-11-20T02:37:02.245Z
external_link: ""
url_slides: ""
subtitle: University of Oxford, Elkem ASA
tags:
  - Industry

image:
  caption: Sketch of a silicon furnace. Reproduced from The Si Process Drawings by Thorsteinn Hannesson.
  focal_point: Smart
url_code: ""
---

The present work corresponds to my PhD research project at the [University of Oxford](https://www.maths.ox.ac.uk/) in collaboration with the silicon manufacturer company [Elkem](https://www.elkem.com/).

## Background
Microsilica particles are spherical particles smaller than a micrometre which are primarily composed of silicon dioxide. One way in which these particles are formed is as a byproduct of silicon production within furnaces, like the one sketched in the figure above. In particular, microsilica particles are created through the combustion of silicon monoxide with air, as the former escapes the furnace surface, producing silicon dioxide vapours. Growth of microsilica particles is through various mechanisms, including nucleation, condensation, aggregation, and agglomeration, which are highly dependent on temperature, chemical species concentrations, pressure, and fluid flow within the furnace domain. 

Being able to control the size and quality of microsilica particles is vital to Elkem, as the microsilica properties affect the performance of composite materials used in applications involving refractories and ceramics, polymers, and concrete additives. The optimal operation of a furnace can result in the creation of particles with desired properties and yield, and motivated by this, the aim of our research project is to derive a mathematical model that relates the local fluid flow, thermal and chemical conditions of the furnace to the formation and growth of microsilica particles.

## Outcomes
We derived a mathematical model that captures the dynamics of the chemical concentrations, temperature, gas flow, and moments of the particle size distribution within a furnace hood. We couple this model to a population balance equation that predicts the entire particle size distribution, by accounting for silicon dioxide consumption and energy release due to particles nucleating and growing by condensation.

Since the regions where microsilica particles form are local to a very thin reaction zone, we first consider a simplified one-dimensional geometry given by a cross section of the reaction zone or flame front. We study two distinct reductions of this model: the case of initially well-mixed or spatially homogeneous chemical species (modelling the region within the flame front), and the case of initially separated chemical species, in which diffusion plays a dominant role in providing material to a combustion front (modelling a larger cross section, which contains a reaction zone with limiting quantities of fuel).  Our findings show that oxygen availability and a sufficiently high temperature are essential for the combustion reactions to occur, strongly influencing the width of the reaction zone and the particle size distribution.

In order to incorporate fluid flow, we extended the previous work to 2-D by considering a mixing layer approach, that is, by assuming two parallel flows entering the domain with distinct velocities, temperatures, and concentrations (one stream is only composed of fuel and the other of oxygen). We studied how the mixing layer evolves as both streams interact, and how mixing affects the formation and growth of particles.  Specifically, we examined how the ratio of the streams velocities affects the final particle size distribution and we conclude that there are no significant differences in the final number density function of particles. However, our results suggest that when the flow is almost uniform, less particles form and more of the total mass corresponds to large particles, in contrast with the non-uniform case.

You can find the main source of the above description [here](http://www.maths.ox.ac.uk/study-here/postgraduate-study/industrially-focused-mathematical-modelling-epsrc-cdt/infomm-resear-34) and a relevant publication [here](https://epubs.siam.org/doi/abs/10.1137/19M1287080).
