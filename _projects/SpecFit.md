---
layout: project
title: SpecFit
description: Generalized spectrum fitter using the lmfit Python package.
repo: SpecFit
pinned: True
categories: [Python, data science]
tags: [python]
---

## About

`SpecFit` is designed to be a versatile spectrum-fitting tool. Utilizing the
Python package `lmfit`, this tool performs non-linear least-squares
minimization to accurately model astrophysical spectra.

`SpecFit` streamlines the process of deriving physical parameters such as
blackbody temperature by integrating an internal preprocessing pipeline. With
the support of [`pybind11`](https://github.com/pybind/pybind11) and C++,
`SpecFit` allows for the iteration of complex (non-vectorizable) models within
`lmfit`, combining Python's simplicity to perform data analysis with the
computational efficiency of C++.

## Example

Coming soon!
