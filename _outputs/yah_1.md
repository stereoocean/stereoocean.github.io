---
title: Shallow Water Equation (SWE) modelling
lead: Andrea Bucchi, Ya Huang
image: /assets/img/outputs/swe1.png
order: 1
description: In the Shallow Water Equation (SWE), the primitive (non-conservative) form expresses the system in terms of the physical variables of water height and fluid velocity, emphasising local acceleration through advective (material derivative) terms, and is therefore intuitive for analysing fluid parcel dynamics and for methods such as semi-Lagrangian schemes.
---

### SWE beach slope water cone drop
<video controls width="100%">
  <source src="/assets/img/outputs/muller7_swe_beach_v1.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
In the Shallow Water Equation (SWE), the primitive (non-conservative) form expresses the system in terms of the physical variables of water height and fluid velocity, emphasising local acceleration through advective (material
derivative) terms, and is therefore intuitive for analysing fluid parcel dynamics and for methods such as
semi-Lagrangian schemes. However, because it is not written explicitly as a conservation law, it only
holds rigorously for smooth solutions and may produce non-physical results when strong gradients or
discontinuities (e.g. shocks, hydraulic jumps, breaking waves or bores) develop. In contrast, the conservative form rewrites the same equations in terms of conserved quantities (e.g. water height and
fluid momentum) in a flux-divergence form, ensuring exact conservation of mass and momentum at the integral level and yielding physically correct solutions even in the presence of discontinuities.
The conservative form is less directly tied to velocity evolution and less natural for characteristic or
trajectory-based discretisations, whereas the primitive form—while more suitable for semi-Lagrangian
approaches—sacrifices strict conservation and can fail to capture correct jump conditions unless special
treatments are introduced.

### SWE beach obstruction water cone drop
The test

