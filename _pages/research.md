---
permalink: /research/
title: "Research"
author_profile: true
---

My main area of research is physics. One project I am currently working on is at the [Rangamani Lab](https://sites.google.com/eng.ucsd.edu/prangamani/home) at UCSD. I am, specifically, studying the cell membrane's shape changes due to external pressures and forces. There are lots of physics-based models that simulate this change in membrane shape but one of them that stands out is [Mem3dg](https://github.com/RangamaniLabUCSD/Mem3DG). This is because this is the only model that uses discrete differential geometry as opposed to other methods like parametrization or the finite element method. This comes with its own benefits like removing the ambiguity in the definition of geometric measurements on the mesh or better integrating with meshes from ultrastructural imaging. However, Mem3dg is far from complete. There are many biological scenarios that it cannot model, so I am working on improving Mem3dg.

<p align="center">
<img src='/images/Mem3dg.png' width="600" height = "450" >
</p>

One way I have done this is by adding multiple proteins to model. Proteins are one of the fundamental reasons for why membranes bend but Mem3dg previously could only support one protein. However, there are many proteins involved in bending the cell membrane in real life, so I added the ability for the user to add any amount of proteins to the model. Next, I was interested in studying different ways the proteins can bend the membrane. Mem3dg is only able to simulate BAR domain proteins where the proteins induce a spontaneous curvature, but I am currently working on adding in other ways for the proteins to bend the membrane like steric pressure. This is where the crowding of proteins results in the membrane bending. Current research speculates that steric pressure is essential for crucial biological processes like endo- and exocytosis, so I am currently working on adding steric pressure to Mem3dg to see if this is really the case.
