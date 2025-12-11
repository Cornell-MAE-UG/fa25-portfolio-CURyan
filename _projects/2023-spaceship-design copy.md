---
layout: project
title: MAE 3270 Design Project
description: Final HW - Fall 2025 | Cornell University
technologies: [ANSYS, Python]
image: /assets/images/wrench.png
---

Results

**1.Image(s) of CAD model. Must show all key dimensions.**

![Profile Picture]({{ "assets/images/1.png" | relative_url }}){: class="profile-image"}





**2.Describe material used and its relevant mechanical properties.**

The material used was structural steel (E=30e6 psi)



**3.Diagram communicating how loads and boundary conditions were applied to your FEM model.**

![Profile Picture]({{ "assets/images/3.1.png" | relative_url }}){: class="profile-image"}

Boundary conditions were applied to the blue-highlighted faces of our FEM model. By setting displacement to zero in each direction, we were able to fix those faces of the drive.

![Profile Picture]({{ "assets/images/3.2.png" | relative_url }}){: class="profile-image"}

A 30 lb load (600/L) was applied in the +x direction on the highlighted blue face. 





**4.Normal strain contours (in the strain gauge direction) from FEM.**

![Profile Picture]({{ "assets/images/4.1.png" | relative_url }}){: class="profile-image"}

![Profile Picture]({{ "assets/images/4.2.png" | relative_url }}){: class="profile-image"}





**5.Contour plot of maximum principal stress from FEM.**

![Profile Picture]({{ "assets/images/5.1.png" | relative_url }}){: class="profile-image"}

![Profile Picture]({{ "assets/images/5.2.png" | relative_url }}){: class="profile-image"}





**6.Summarize results from FEM calculation showing maximum normal stress (anywhere), load point deflection, strains at the strain gauge locations.**

Max normal stress: 29359 psi

Load point deflection: 0.169 in

Strain at gauge 1: 178.6 microstrains

Strain at gauge 2: -178.9 microstrains




**7.Torque wrench sensitivity in mV/V using strains from the FEM analysis.**

Using the FEM strains at the gauge location and assuming a full-bridge with 
GF=2, the torque wrench sensitivity at the rated torque of 600 in-lbf is approximately 0.36 mV/V.





**8.Strain gauge selected (give type and dimensions). Note that design must physically have enough space to bond the gauges.**

Type: linear, single-axis foil strain gauge for bending

Resistance: 350 Ω, gauge factor GF ≈ 2.0

Active grid length: ~3 mm ≈ 0.12 in

Active grid width: ~2 mm ≈ 0.08 in

Overall backing size: ~5 mm × 3 mm ≈ 0.20 in × 0.12 in
