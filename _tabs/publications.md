---
layout: page
icon: fas fa-book
order: 3
math: True
---

# Dissertation
---

My PhD dissertation is currently in preparation, but will eventually be available here.

# First-Author Papers
---

#### <ins>*Extrapolation of Type Ia Supernova Spectra into the Near-infrared Using Principal Component Analysis*</ins>
Burrow et al. (2024), [DOI: 10.3847/1538-4357/ad3c45](https://doi.org/10.3847/1538-4357/ad3c45){:target="_blank"}

We present a method of extrapolating near-infrared (NIR) spectra of Type Ia supernovae up to $\sim2.3\ \mu m$ using an optical spectrum. This is done by performing a principal component analysis (PCA) on a set of observed optical and NIR spectra. Further analysis on the output PCs is also provided.

This method led to [`SNEx`]({% link _projects/SNEx.md %}), which uses Python to extrapolate an input spectrum accordingly with this work.

#### <ins>*Carnegie Supernova Project: Classification of Type Ia Supernovae*</ins>
Burrow et al. (2020), [DOI: 10.3847/1538-4357/abafa2](https://doi.org/10.3847/1538-4357/abafa2){:target="_blank"}

We first establish changes to [`Spextractor`]({% link _projects/Spextractor.md %}), and we use these changes to measure the blueshifts and pseudo-equivalent widths of two Si II features of Type Ia supernovae. We then model the distribution of these quantities, along with $B$-band maximum, using multi-dimensional Gaussian mixture models. This cluster analysis has led to a statistically robust classification system based on that from Branch et al. (2006).

A Python wrapper called [`SNIaDCA`]({% link _projects/SNIaDCA.md %}) has been created to handle the a Gaussian mixture model object such that a user can easily obtain group membership probabilities from the trained model by just giving relevant spectroscopic properties.

# Co-Authored Papers
---

A list of publications I've contributed to can be found using [this NASA/ADS query](https://ui.adsabs.harvard.edu/search/fq=%7B!type%3Daqp%20v%3D%24fq_database%7D&fq_database=(database%3Aastronomy%20OR%20database%3Aphysics)&q=%20author%3A%22burrow%2C%20anthony%22&sort=date%20desc%2C%20bibcode%20desc&p_=0){:target="_blank"}.
