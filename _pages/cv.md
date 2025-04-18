---
layout: archive
title: "My Research"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}


  <h1>My Research Focus</h1>

  <p>My research lies at the intriguing confluence of applied and pure mathematics, with a strong emphasis on the mathematical underpinnings and computational modeling of turbulence. The central focus of my work is the <strong>Navier–Stokes equations</strong>—a cornerstone of fluid dynamics and a fundamental system of partial differential equations (PDEs) that describe the motion of viscous fluid substances. While these equations appear deceptively simple, they encapsulate rich and complex behaviors that become especially prominent in turbulent regimes.</p>

  <h2>Turbulence and Direct Numerical Simulation (DNS)</h2>

  <p>Turbulence itself is a multiscale phenomenon, characterized by chaotic, non-linear interactions across a wide range of spatial and temporal scales. To investigate this, I employ <strong>Direct Numerical Simulation (DNS)</strong> techniques, which resolve all the dynamically significant scales of motion without resorting to turbulence modeling. Unlike Reynolds-Averaged Navier–Stokes (RANS) or Large Eddy Simulations (LES), DNS directly solves the full set of time-dependent Navier–Stokes equations using high-fidelity numerical schemes, typically on a discretized spatial grid. While DNS is computationally expensive—especially at high Reynolds numbers <em>Re</em>—it remains the gold standard for investigating fundamental turbulence physics. A significant part of my DNS work involves analyzing the evolution of turbulent flows in various geometries, including periodic domains and channel flows. These simulations are designed to explore the onset of turbulence, the role of instabilities, and the energy cascade from large to small scales as described in Kolmogorov's theory of turbulence. In line with this, my simulations often aim to replicate classic benchmark problems such as <strong>decaying homogeneous isotropic turbulence</strong>, <strong>Taylor–Green vortex breakdown</strong>, and <strong>Rayleigh–Bénard convection</strong> under various boundary conditions.</p>

  <figure>
    <img src="https://github.com/user-attachments/assets/4d62cbfd-b331-42fc-a326-da57c41259c8" alt="Fractal Initial Conditions Simulation" width="600">
    <figcaption>This is an example for different initial conditions inspired from different fractal structures and their numerical simulation using 2D Navier–Stokes equation.</figcaption>
  </figure>

  <p>What makes this research particularly fascinating is the blend of physics, numerical analysis, and high-performance computing. The nonlinear term in the Navier–Stokes equations, <em>(u · ∇)u</em>, is responsible for energy transfer across scales and is also the source of mathematical complexity and chaos. I use spectral and finite-difference methods to discretize these terms and apply time integration schemes such as Runge–Kutta methods to evolve the velocity and pressure fields in time. Special care is taken in ensuring numerical stability through CFL conditions and in satisfying the incompressibility constraint <em>∇ · u = 0</em>. An exciting avenue in my work has been the visualization of <strong>energy spectra</strong> and <strong>intermittency</strong>. The energy spectrum <em>E(k)</em>, where <em>k</em> denotes the wavenumber, provides insights into how kinetic energy is distributed across scales. For instance, in fully developed turbulence, the inertial subrange is expected to follow the <em>E(k) ∼ k<sup>−5/3</sup></em> power law. Deviations from this, particularly in high-resolution simulations, point to anisotropy or the effects of coherent structures.</p>

  <p>In addition to DNS, my studies have touched on <strong>chaotic attractors and sensitivity to initial conditions</strong>, key features of turbulent systems. Inspired by the deterministic yet unpredictable nature of systems governed by PDEs, I explored how small perturbations in the initial velocity fields can cause drastically different long-term flow behaviors—akin to the butterfly effect. Here, tools from <strong>dynamical systems theory</strong> are instrumental in understanding the underlying structure of these trajectories in infinite-dimensional phase spaces.</p>

  <h2>Pure Mathematics: Analysis, Measure Theory, and Functional Analysis</h2>

  <p>My applied research is complemented by a deep interest in <strong>pure mathematics</strong>, particularly in areas that form the theoretical backbone of analysis. <strong>Real analysis</strong> has been fundamental in formalizing concepts such as convergence, continuity, and integrability—each crucial when proving the well-posedness of the Navier–Stokes system. I am especially drawn to <strong>measure theory</strong> and <strong>functional analysis</strong> for their rigorous frameworks that allow one to interpret PDEs in the context of Sobolev spaces and Hilbert/Banach space theory. For example, studying weak solutions of the Navier–Stokes equations necessarily involves tools from Lebesgue integration and <em>L<sup>p</sup></em> spaces. Understanding the compactness arguments and the role of distribution theory has enabled me to appreciate the existence and partial regularity results such as those by Leray and Caffarelli–Kohn–Nirenberg. A fascinating open problem that motivates much of my mathematical curiosity is the <strong>Millennium Prize Problem</strong> on the global regularity of the Navier–Stokes equations in three dimensions. This blends PDE theory with functional analysis in a profound way—requiring insight into whether solutions that start smooth can develop singularities in finite time.</p>

  <p>Measure theory plays a particularly central role in understanding statistical properties of turbulent flows. The idea of ergodicity—where time averages converge to ensemble averages—is deeply rooted in measure-theoretic probability. I find the use of <strong>invariant measures</strong> and <strong>ergodic theorems</strong> in the analysis of long-time behavior of turbulent systems both beautiful and practically useful, especially in the development of reduced-order models. My mathematical explorations also include the study of <strong>operator theory</strong> and <strong>semigroup theory</strong>, which appear in the analysis of linearized Navier–Stokes operators and the study of their spectrum. These tools become essential when considering the stability of steady-state solutions and for deriving estimates that are critical in proving the boundedness or blow-up of solutions.</p>

  <h2>Future Directions</h2>

  <p>Ultimately, my research is a quest to understand complexity through both the lens of rigorous mathematics and the computational power of modern simulations. The Navier–Stokes equations, while physically grounded, sit atop a mountain of analytical depth. Through DNS, I can visualize the fine-grained features of turbulence, while through functional and real analysis, I can comprehend the abstract structures that make such modeling possible. The synergy between these domains not only makes the research intellectually rewarding but also essential for pushing the boundaries of both mathematical theory and applied science. Looking ahead, I am keen on exploring how <strong>machine learning and reduced-order models</strong> can complement traditional DNS approaches, as well as how <strong>nonlinear PDE theory</strong> can provide new regularity criteria or insights into turbulence modeling. Simultaneously, my commitment to pure mathematics ensures that I continue building a rigorous foundation, one that deepens my understanding of the problems I simulate—and perhaps, someday, helps solve one of the most famous mathematical challenges of our time.</p>
 
# Places who gave me opportunity

<img src="https://github.com/user-attachments/assets/e6c497d8-d8ea-4d32-a2d2-9f51e7483bf1" alt="image" width="550"/>
