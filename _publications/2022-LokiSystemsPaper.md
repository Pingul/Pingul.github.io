---
title: 'Loki: A Unified Multiphysics Simulation Framework for Production'
collection: publications
permalink: /publication/2022-Loki
date: 2022-07-01
venue: 'ACM Transactions on Graphics'
paperurl: 'https://joel.wbn.se/files/Publication-Loki/Loki.pdf'
citation: 'Steve Lesser, Alexey Stomakhin, Gilles Daviet, Joel Wretborn, John Edholm, Noh-Hoon Lee, Eston Schweickart, Xiao Zhai, Sean Flynn, and Andrew Moffat. 2022. &quot;Loki: A Unified Multiphysics Simulation Framework for Production.&quot; ACM Transactions on Graphics, 50, 41 (4): 1–20. https://doi.org/10.1145/3528223.3530058.'
---

![Loki](/files/Publication-Loki/image.jpeg)

Abstract 
--------
We introduce Loki, a new framework for robust simulation of fluid, rigid, and deformable objects with non-compromising fidelity on any single element, and capabilities for coupling and representation transitions across multiple elements. Loki adapts multiple best-in-class solvers into a unified framework driven by a declarative state machine where users declare ‘what’ is simulated but not ‘when,’ so an automatic scheduling system takes care of mixing any combination of objects. This leads to intuitive setups for coupled simulations such as hair in the wind or objects transitioning from one representation to another, for example bulk water FLIP particles to SPH spray particles to volumetric mist. We also provide a consistent treatment for components used in several domains, such as unified collision and attachment constraints across 1D, 2D, 3D deforming and rigid objects. Distribution over MPI, custom linear equation solvers, and aggressive application of sparse techniques keep performance within production requirements. We demonstrate a variety of solvers within the framework and their interactions, including FLIP-style liquids, spatially adaptive volumetric fluids, SPH, MPM, and mesh-based solids, including but not limited to discrete elastic rods, elastons, and FEM with state-of-the-art constitutive models. Our framework has proven powerful and intuitive enough for voluntary artist adoption and has delivered creature and FX simulations for multiple major movie productions in the preceding four years.
