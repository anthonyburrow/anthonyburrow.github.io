---
layout: project
title: SNEx
description: Extrapolation of SNe Ia spectra into the near-infrared using principal component analysis.
repo: SNEx
pinned: True
categories: [Python, data science]
---

## About

`SNEx` (SuperNova Extrapolation) is a tool that makes use of principal component
analysis (PCA) performed on a data set of Carnegie Supernova Project (CSP)
I & II optical and near-infrared (NIR) spectra to extrapolate optical spectra
of Type Ia SNe into the NIR, up to about 2.3 microns.

Essentially, PCA is performed on a set of optical+NIR data to get a set of
eigenvectors that span both wavelength regimes. This software takes an input
optical spectrum, projects it onto the eigenvectors, and the result allows for
a prediction in the NIR. For more detail on how this extrapolation procedure
works, see
[the publication by Burrow et al. (2024)]({% link _tabs/publications.md %}#extrapolation-of-type-ia-supernova-spectra-into-the-near-infrared-using-principal-component-analysis).

## Example

Below is an example of the extrapolation procedure at work for an example
spectrum. Using the information from the original spectrum between the two
dashed lines, an extrapolated spectrum (in the red) is achieved.

![Desktop View](assets/img/projects/SNEx.png)
_Extrapolation of a maximum-light spectrum of SN 2011fe._
