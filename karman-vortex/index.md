---
title: "Karman Vortex"
layout: default
---

# Karman Vortex street simulation
A simple Karman street simulation that uses a D2Q9 LBM CFD solver for real-time web.

### Approach
- A genuine discretized D2Q9 LBM model on a grid measuring `320x180` cells, with boundary interactions handling halfway bounceback logic, which establishes actual no-slip conditions around the cylinder (no shortcuts taken).
- High-efficiency density and velocity clamped before the collision step (`U_max = 0.2`) to make sure there are no particle explosions. The BGK collision relaxes the clamped values back into the physical bounds.
- Adjustable values in accordance to the Strouhal formula (sliders for flow velocity `U`, diameter `D`) make sure the LBM field reacts to the `f = St(U/D)` principle. The Reynolds number `Re` and kinematic viscocity `v` are also provided.
- Optimized for JIT compilers to reduce object allocations on the hot path, uses CDNs/mirrors for global resource coverage

### Trade-offs
- Multi-relaxation time (MRT) is not implemented in favor of the BGK single-relaxation scalar even though it's unconditionally stable, because the transformation matrix requires more flops on a non-accelerated backend
- The Smagorinsky model requires recalculation of the nonequilibrium strain rate tensor `S_ij` for every cell just to add artificial viscocity, which is unideal for real-time contexts
- Zou/He & Boudini interpolated bounceback boundaries are also not implemented because they are better for moving curves while the object in the simulation is strictly a stationary cylinder. Hence a staircasing halfway bounceback model is sufficient.
- Overall, more advanced methods used in industrial solvers like ANSYS Fluent aren't implemented because this one is a good approximation for demo and simulation

### Demo
Looks pretty cool
<img width="1280" height="720" alt="CFD_Frame_2026_04_30T16_20_28_997Z" src="https://github.com/user-attachments/assets/fe528ced-0bf9-47b6-9921-662399619f8f" />

Embedded simulation (view the simulation in full-screen [here](https://willuhd.github.io/karman-vortex/karmanVortex.html)):
<iframe src="karmanVortex.html" class="karman-vortex"></iframe>
