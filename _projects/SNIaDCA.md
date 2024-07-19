---
layout: project
title: SNIaDCA
description: A Python wrapper for the cluster analysis by Burrow, et al. (2020) using Gaussian mixture models.
repo: SNIaDCA
pinned: True
categories: [code, python]
tags: [python]
---

## About

`SNIaDCA` is a Python wrapper containing the various Gaussian mixture model
(GMM) objects used to produce the results of a cluster analysis performed by
[Burrow et al. (2020)]({% link _tabs/publications.md %}#carnegie-supernova-project-classification-of-type-ia-supernovae).
In this paper we define a robust classification system for Type Ia SNe based on
both spectroscopic and photometric properties.

This wrapper allows one to easily provide the relevant spectroscopic and/or
photometric quantities and receive the probabilities of cluster membership
according to the corresponding GMMs.

## Example

Below is a figure taken from Burrow, et al. (2020), which is a visualization
of one of the GMMs. The probabilities that are output by `SNIaDCA` can be used
to recreate this figure with any given sample of Type Ia SNe.

![Desktop View](assets/img/projects/SNIaDCA.png)
_2-D Gaussian mixture model from Burrow, et al. (2020)._
