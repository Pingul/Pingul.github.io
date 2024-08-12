---
title: 'Underwater bubbles and coupling'
collection: publications
permalink: /publication/2020-UnderwaterBubbles
date: 2020-08-17
venue: 'ACM SIGGRAPH Talks'
paperurl: 'https://joel.wbn.se/files/Publication-Underwater_Bubbles_And_Coupling/Publication-Underwater_Bubbles_and_Coupling.pdf'
citation: 'Alexey Stomakhin, Joel Wretborn, Kevin Blom, and Gilles Daviet. 2020. &quot;Underwater Bubbles and Coupling.&quot; Special Interest Group on Computer Graphics and Interactive Techniques Conference Talks. https://doi.org/10.1145/3388767.3407390.'
---

![Underwater bubbles and coupling](/files/Publication-Underwater_Bubbles_And_Coupling/bubbles.jpg)

Abstract 
--------
We present an approach to simulating underwater bubbles. Our method is sparse in that it only simulates a thin band of water around the region of interest allowing us to achieve high resolu- tions in turbulent scenarios. We use a hybrid bubble representation consisting of two parts. The hero counterpart utilizes an incompressible two-phase Navier-Stokes solve on an Eulerian grid with air phase also represented via FLIP/APIC particles to facilitate volume conservation and accurate interface tracking. The diffuse counter-part captures sub-grid bubble motion not “seen” by the Eulerian grid. We represent those as particles and develop a novel scheme for coupling them with the bulk fluid. The coupling scheme is not limited to sub-grid bubbles and may be applied to other thin/porous objects such as sand, hair, and cloth.

