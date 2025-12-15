---
layout: project
title: Blade Design
description: Design project for a wind turbine blade
technologies: [MATLAB, Autodesk Inventor]
image: /assets/images/Blade-Testing.png
---


**Project Overview**

This project focused on the design and experimental validation of a small-scale wind turbine blade optimized to maximize power output using a NACA 4412 airfoil. The blade was designed to operate efficiently in wind speeds of 3–6 m/s while remaining within limits on torque (0.035 Nm), rotational speed (3000 RPM), material stress (55 MPa), and physical dimensions (2" chord, 6" span). The NACA 4412 airfoil was selected for its high lift-to-drag ratio, and blade geometry (pitch, taper, and span) was optimized for the most probable wind speed derived from a Weibull distribution.

**Design Process**

The blade design was based on our hypothesis that maximizing the lift-to-drag ratio (CL/CD) would maximize power output, which drove the decision to use the NACA 4412 airfoil. Using a simplified Blade Element Momentum (BEM) model, the blade was divided into sections to calculate lift, drag, torque, and bending loads. Assumptions for this analysis included a constant axial induction factor of 1/3, bending-dominated failure, and a taper ratio of 0.3. We targetted an 8° angle of attack for the NACA 4412 airfoil and created a CAD model which d the optimized pitch, chord, and taper. 

**Testing Summary**

Wind tunnel experiments were conducted to measure turbine performance and validate theoretical predictions. Power and torque curves were generated for multiple wind speeds between 3-6 m/s, successfully capturing the right-hand side of the power curve while maintaining safe operation through monitoring the torque and RPM limits. Testing at higher wind speeds was limited by the torque brake capacity, which prevented measurement of the left-hand side of the power curve and reducing data density at the upper end of the operating range. 

![More power curves]({{ "/assets/images/Torque-Power-Curves.png" | relative_url }}) 
At the most probable wind speed, the experimental power output was approximately half of the theoretical prediction, and the model slightly underestimated the operating angular velocity at maximum power for each wind speed.

**My Contributions**

For this group project, while all of us contributed to all parts of the project, my main focus was in creating the CAD model of the blade. This was done through importing the airfoil shape into Inventor and changing the chord length and pitch for multiple sections of the span and then creating a loft through them. I also ensured that the part would be within 3D printing tolerances and that the hub connection point would fit into the testing setup. 

![CAD Image]({{ "/assets/images/Blade-Cad.png" | relative_url }}) 