---
layout: archive
title: "My Research"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

My research lies at the intriguing confluence of applied and pure mathematics, with a strong emphasis on the mathematical underpinnings and computational modeling of turbulence. The central focus of my work is the **Navier–Stokes equations**—a cornerstone of fluid dynamics and a fundamental system of partial differential equations (PDEs) that describe the motion of viscous fluid substances. While these equations appear deceptively simple, they encapsulate rich and complex behaviors that become especially prominent in turbulent regimes.

## Turbulence and Direct Numerical Simulation (DNS)

Turbulence itself is a multiscale phenomenon, characterized by chaotic, non-linear interactions across a wide range of spatial and temporal scales. To investigate this, I employ **Direct Numerical Simulation (DNS)** techniques, which resolve all the dynamically significant scales of motion without resorting to turbulence modeling. Unlike Reynolds-Averaged Navier–Stokes (RANS) or Large Eddy Simulations (LES), DNS directly solves the full set of time-dependent Navier–Stokes equations using high-fidelity numerical schemes, typically on a discretized spatial grid. While DNS is computationally expensive—especially at high Reynolds numbers \(\text{Re}\)—it remains the gold standard for investigating fundamental turbulence physics. A significant part of my DNS work involves analyzing the evolution of turbulent flows in various geometries, including periodic domains and channel flows. These simulations are designed to explore the onset of turbulence, the role of instabilities, and the energy cascade from large to small scales as described in Kolmogorov's theory of turbulence. In line with this, my simulations often aim to replicate classic benchmark problems such as **decaying homogeneous isotropic turbulence**, **Taylor–Green vortex breakdown**, and **Rayleigh–Bénard convection** under various boundary conditions.

<figure>
  <img src="https://github.com/user-attachments/assets/4d62cbfd-b331-42fc-a326-da57c41259c8" alt="image" width="600"/>
  <figcaption style="text-align: center;">This an example for different initial conditions inspired from different fractal structures and their numerical simulation using 2D Navier–Stokes equation.</figcaption>
</figure>

What makes this research particularly fascinating is the blend of physics, numerical analysis, and high-performance computing. The nonlinear term in the Navier–Stokes equations,

\[
(\mathbf{u} \cdot \nabla)\mathbf{u},
\]

is responsible for energy transfer across scales and is also the source of mathematical complexity and chaos. I use spectral and finite-difference methods to discretize these terms and apply time integration schemes such as Runge–Kutta methods to evolve the velocity and pressure fields in time. Special care is taken in ensuring numerical stability through CFL conditions and in satisfying the incompressibility constraint

\[
\nabla \cdot \mathbf{u} = 0.
\]

An exciting avenue in my work has been the visualization of **energy spectra** and **intermittency**. The energy spectrum \( E(k) \), where \( k \) denotes the wavenumber, provides insights into how kinetic energy is distributed across scales. For instance, in fully developed turbulence, the inertial subrange is expected to follow the

\[
E(k) \sim k^{-5/3}
\]

power law. Deviations from this, particularly in high-resolution simulations, point to anisotropy or the effects of coherent structures.

In addition to DNS, my studies have touched on **chaotic attractors and sensitivity to initial conditions**, key features of turbulent systems. Inspired by the deterministic yet unpredictable nature of systems governed by PDEs, I explored how small perturbations in the initial velocity fields can cause drastically different long-term flow behaviors—akin to the butterfly effect. Here, tools from **dynamical systems theory** are instrumental in understanding the underlying structure of these trajectories in infinite-dimensional phase spaces.

## Pure Mathematics: Analysis, Measure Theory, and Functional Analysis

My applied research is complemented by a deep interest in **pure mathematics**, particularly in areas that form the theoretical backbone of analysis. **Real analysis** has been fundamental in formalizing concepts such as convergence, continuity, and integrability—each crucial when proving the well-posedness of the Navier–Stokes system. I am especially drawn to **measure theory** and **functional analysis** for their rigorous frameworks that allow one to interpret PDEs in the context of Sobolev spaces and Hilbert/Banach space theory.

For example, studying weak solutions of the Navier–Stokes equations necessarily involves tools from Lebesgue integration and \( L^p \) spaces. Understanding the compactness arguments and the role of distribution theory has enabled me to appreciate the existence and partial regularity results such as those by Leray and Caffarelli–Kohn–Nirenberg. A fascinating open problem that motivates much of my mathematical curiosity is the **Millennium Prize Problem** on the global regularity of the Navier–Stokes equations in three dimensions. This blends PDE theory with functional analysis in a profound way—requiring insight into whether solutions that start smooth can develop singularities in finite time.

Measure theory plays a particularly central role in understanding statistical properties of turbulent flows. The idea of ergodicity—where time averages converge to ensemble averages—is deeply rooted in measure-theoretic probability. I find the use of **invariant measures** and **ergodic theorems** in the analysis of long-time behavior of turbulent systems both beautiful and practically useful, especially in the development of reduced-order models. My mathematical explorations also include the study of **operator theory** and **semigroup theory**, which appear in the analysis of linearized Navier–Stokes operators and the study of their spectrum. These tools become essential when considering the stability of steady-state solutions and for deriving estimates that are critical in proving the boundedness or blow-up of solutions.

<div style="padding-top:59.951%;position:relative;"><iframe src="https://gifer.com/embed/EUjI" width="100%" height="100%" style='position:absolute;top:0;left:0;' frameBorder="0" allowFullScreen></iframe></div><p><a href="https://gifer.com">via GIFER</a></p>

## Future Directions

Ultimately, my research is a quest to understand complexity through both the lens of rigorous mathematics and the computational power of modern simulations. The Navier–Stokes equations, while physically grounded, sit atop a mountain of analytical depth. Through DNS, I can visualize the fine-grained features of turbulence, while through functional and real analysis, I can comprehend the abstract structures that make such modeling possible. The synergy between these domains not only makes the research intellectually rewarding but also essential for pushing the boundaries of both mathematical theory and applied science. Looking ahead, I am keen on exploring how **machine learning and reduced-order models** can complement traditional DNS approaches, as well as how **nonlinear PDE theory** can provide new regularity criteria or insights into turbulence modeling. Simultaneously, my commitment to pure mathematics ensures that I continue building a rigorous foundation, one that deepens my understanding of the problems I simulate—and perhaps, someday, helps solve one of the most famous mathematical challenges of our time.

# Places who gave me opportunity

<img src="https://github.com/user-attachments/assets/e6c497d8-d8ea-4d32-a2d2-9f51e7483bf1" alt="image" width="450"/>
