---
layout: project
title: Rad1D
description: A simple 1-D radiative transfer code that describes light passing through a medium.
repo: Rad1D
categories: [code, C++]
tags: [C++]
math: true
---

## About

A simple 1D, plane-parallel radiative transfer code that implements accelerated
lambda iterations (ALI). ALI is a method of solving the complex radiative
transfer equation for the mean intensity of radiation at a specific wavelength
as a function of wavelength. By doing so, a resulting observed flux can be
modeled for light passing through a medium, such as a star's atmosphere.

## Examples

The solution of the source function $S$ can be found through many lambda
iterations. Below, this is illustrated where every line is a different
iteration, until $S$ (in terms of the blackbody function $B$) can finally
converge with the initial condition $S = B$.

![Desktop View](assets/img/projects/Rad1D.png)
_The convergence of the source function for the gray-wavelength case._
