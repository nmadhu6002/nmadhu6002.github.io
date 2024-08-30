---
permalink: /research/
title: "Research"
author_profile: true
---

My main area of research is physics, and I am currently pursuing two projects.

## Membrane Mechanics

This project I'm working on at the [CTLee Lab](https://labs.biology.ucsd.edu/ctlee/) in UCSD. I am studying the cell membrane's shape changes due to external pressures and forces. There are lots of physics-based models that simulate this change in membrane shape but one of them that stands out is [Mem3dg](https://github.com/RangamaniLabUCSD/Mem3DG). This is because this is the only model that uses discrete differential geometry as opposed to other methods like parametrization or the finite element method. This comes with its own benefits like removing the ambiguity in the definition of geometric measurements on the mesh or better integrating with meshes from ultrastructural imaging. However, Mem3dg is far from complete. There are many biological scenarios that it cannot model, so I am working on improving Mem3dg.

<p align="center">
<img src='/images/Mem3dg.png' width="600" height = "450" >
</p>

One way I have done this is by adding multiple proteins to model. Proteins are one of the fundamental reasons for why membranes bend but Mem3dg previously could only support one protein. However, there are many proteins involved in bending the cell membrane in real life, so I added the ability for the user to add any amount of proteins to the model. Next, I was interested in studying different ways the proteins can bend the membrane. Mem3dg is only able to simulate BAR domain proteins where the proteins induce a spontaneous curvature, but I am currently working on adding in other ways for the proteins to bend the membrane like steric pressure. This is where the crowding of proteins results in the membrane bending. Recent research speculates that steric pressure is essential for crucial biological processes like endo- and exocytosis, so I am currently working on adding steric pressure to Mem3dg and investigate if this is really the case.

## Hénon-Heiles System

In this independent project, I study the nonlinear dynamics of a generalized Hénon-Heiles System. The Hénon-Heiles system was a Hamiltonian system Michel Hénon and Carl Heiles came up in 1964 to study the existance of third integrals of motion. Because this system is analytically very simple but produces very interesting and complex trajectories, it has been studied in contexts outside of integrals of motion like general relativity and quantum entanglement. There has also been lots of work generalizing this system by starting off with a axi-symmetric potential and Taylor expanding it. 

So far, I have look at the seventh order expansion that contains two parameters δ and α, for the fifth and seventh order terms, respectively. This allowed me to *separately* study how the higher order terms affect the dynamics of the system, which has not been done before. To study the nonlinear dynamics, I used Poincaré sections for a qualitative approach and Lyapunov Exponents for a quantitative approach. All of this work is in the paper I have published in *Applications and Applied Mathematics: An International Journal*. Currently, I am working on further analyzing these indicators of chaotic dynamics. For example, the Poincaré sections have loops which indicates quasiperiodic motion, so I am looking into seeing if there are any patterns the fundamental frequencies of motion in the generalized Hénon-Heiles system.