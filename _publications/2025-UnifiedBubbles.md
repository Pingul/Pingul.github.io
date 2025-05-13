---
title: 'A unified multi-scale method for simulating immersed bubbles'
collection: publications
permalink: /publication/2025-UnifiedBubbles
date: 2025-05-13
venue: 'Eurographics'
paperurl: 'https://joel.wbn.se/files/Publication-Unified_Bubbles/Unified-bubbles.pdf'
citation: 'Wretborn, Joel, Alexey Stomakhin, and Christopher Batty. 2025. “A Unified Multi‐scale Method for Simulating Immersed Bubbles.” Computer Graphics Forum: Journal of the European Association for Computer Graphics, April. https://doi.org/10.1111/cgf.70033.'
---

![Unified bubbles](/files/Publication-Unified_Bubbles/bubble-barrel-closeup-combined.png)

Abstract 
--------
We introduce a novel unified mixture-based method for simulating underwater bubbles across a range of bubble scales. Our approach represents bubbles as a set of Lagrangian particles that are coupled with the surrounding Eulerian water volume. When bubble particles are sparsely distributed, each particle, typically smaller than the liquid grid voxel size, corresponds to an individual spherical bubble. As the sub-grid particles increase in local density our model smoothly aggregates them, ultimately forming connected, fully aerated volumetric regions that are properly resolved by the Eulerian grid. We complement our scheme with a continuous surface tension model, defined via the gradient of the bubbles’ local volume fractions, which works seamlessly across this scale transition. Our unified representation allows us to capture a wide range of effects across different scales—from tiny dispersed sub-grid air pockets to fully Eulerian two-phase interfacial flows.

