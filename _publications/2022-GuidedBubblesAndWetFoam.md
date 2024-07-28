---
title: 'Guided Bubbles and Wet Foam for Realistic Whitewater Simulation'
collection: publications
permalink: /publication/2022-GuidedBubblesAndWetFoam
date: 2022-07-01
venue: 'GraphicsCM Transaction on Graphics'
paperurl: 'http://pingul.github.io/files/Publication-Guided_Bubbles_And_Wet_Foam/Guided_Bubbles_And_Wet_Foam.pdf'
citation: 'Joel Wretborn, Sean Flynn, and Alexey Stomakhin. 2022. &quot;Guided Bubbles and Wet Foam for Realistic Whitewater Simulation.&quot; ACM Transactions on Graphics. https://doi.org/10.1145/3528223.3530059.'
---

![Guided Bubbles and Wet Foam for Realistic Whitewater Simulation](/files/Publication-Guided_Bubbles_And_Wet_Foam/image)

Abstract 
--------
We present a method for enhancing fluid simulations with realistic bubble and foam detail. We treat bubbles as discrete air particles, two-way coupled with a sparse volumetric Euler flow, as first suggested in [Stomakhin et al. 2020]. We elaborate further on their scheme and introduce a bubble inertia correction term for improved convergence. We also show how one can add bubbles to an already existing fluid simulation using our novel guiding technique, which performs local re-simulation of fluid to achieve more interesting bubble dynamics through coupling. As bubbles reach the surface, they are converted into foam and simulated separately. Our foam is discretized with smoothed particle hydrodynamics (SPH), and we replace forces normal to the fluid surface with a fluid surface manifold advection constraint to achieve more robust and stable results. The SPH forces are derived through proper constitutive modeling of an incompressible viscous liquid, and we explain why this choice is appropriate for “wet” types of foam. This allows us to produce believable dynamics from close-up scenarios to large oceans, with just a few parameters that work intuitively across a variety of scales. Additionally, we present relevant research on air entrainment metrics and bubble distributions that have been used in this work.

