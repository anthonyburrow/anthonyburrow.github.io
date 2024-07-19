---
layout: project
title: Spextractor
description: Uses Gaussian process regression and other techniques to quickly smooth spectra and calculate spectroscopic properties of Type Ia supernovae.
repo: spextractor
pinned: True
categories: [code, python]
tags: [python]
---

## About

This code is a fork of the
[original `spextractor`](https://github.com/astrobarn/spextractor)
by Seméli Papadogiannakis.

`spextractor` uses Gaussian process regression (GPR) to quickly smooth spectra
and extract line-velocities, pseudo-equivalent widths, and other properties of
a given spectrum. It is designed specifically for use with Type Ia supernova
spectra, although the spectrum-smoothing capabilities of this software can be
extended for use on any spectrum.

## Example

Here is a basic use-case of `spextractor` for Type Ia SNe. The red line is the
mean function of the GPR, and it passes through the original spectrum closely
with minimal overfitting.

![Desktop View](assets/img/projects/Spextractor.png)
_An example of line-identification and smoothing with `spextractor`._
