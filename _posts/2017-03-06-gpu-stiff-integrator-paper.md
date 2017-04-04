---
layout: post
title: GPU stiff integrator paper published
---

Our paper describing a study of GPU-based integration algorithms for chemical
kinetics, and the associated [accelerInt software package](https://github.com/SLACKHA/accelerInt)
has been published in *Combustion and Flame*:
 * Journal version: <https://doi.org/10.1016/j.combustflame.2017.02.005>
 * arXiv eprint: [`arXiv:1607.03884 [physics.comp-ph]`](https://arxiv.org/abs/1607.03884)

The differential equations governing the time change of chemical kinetics are
typically stiff, meaning they present challenges to solve that require
specialized algorithms.
accelerInt is an open-source library ODE (ordinary differential equation)
solvers tested and verified for these applications. This paper focuses
on three particular algorithms, comparing and contrasting them both with each
other and a representative algorithm used commonly in computer simulations of
combustion. We showed that, under some conditions, one method (implicit,
fifth-order Runge–Kutta) can perform 12–38 times faster on a graphics processing
unit compared with a standard method on a central processing unit.
