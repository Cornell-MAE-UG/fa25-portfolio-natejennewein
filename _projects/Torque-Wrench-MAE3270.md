---
layout: project
title: Torque Wrench Design
description: Class Project with Finite Element Analysis
technologies: [python, Ansys]
image: /assets/images/stresscontour.png
---

## Description
For our final project in Mechancics of Engineering Materials, 
my partner and I designed a torque wrench designed to meet certain
requirements when a 600 lb-in moment is applied to its drive. First,
we hand calculated our expected delfection and stresses, then we 
created a CAD model and ran it through Ansys to obtain the following 
results.

---

#### CAD Files

![CAD Photo 1 ](/assets/images/cad1.png)
![CAD Photo 2 ](/assets/images/cad2.png)

These show the dimensions of our design and a rough layout of the geometry used. 

#### Loads and Boundary Conditions

![Loading Schematic](/assets/images/loads.jpeg)

This shows how the pieces of the model were constrained and loaded in Ansys

#### Normal Strain Contours

![strain contour](/assets/images/straincontour.png)

#### Contour Plot of Maximum Principal Stress

![strain contour](/assets/images/straincontour.png)

#### Results of FEM

Our FEM analysis yielded a 1.64 mv/v output at the gauge (seen in photo as Normal Strain Z-Axis in bottom left), a maximum normal stress of 77323, and a maximum deflection of 

![Strain Gauge](/assets/images/probestrain.png)
![Max Normal](/assets/images/maxnormal.png)

#### Torque Wrench Sensitivity

Our sensitivity converts each thousand units of microstrain into 1 mv/V on our strain gauge. This can also be stated as 1 mv/V = 1000 microstrain

#### Strain Gauge Selection

We chose a half bridge strain gauge for out analysis. 





