---
permalink: /
title: "Patrick Harrison, PhD"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Current work
============

I am a postdoctoral researcher at [SIMaP laboratory](https://simap.grenoble-inp.fr/en/about-simap), Grenoble INP, working on algorithm development for 3D reconstructions of multi-phase nanoscale materials from 4D Electron Diffraction data, and more specifically Scanning Precession Electron Diffraction (SPED) data. Diffraction contrast allows indvidual grains to be distinguished within a polycrystalline sample, which is not possible using common imaging signals in the electron microscope (BF/ADF). Tilted projections of individual grains are calculated for tomographic reconstruction by combining SPED with tilt-series tomography, enabling 3D reconstrion of the sample volume and analysis of the material microstructure.

This work involves the development of grain reconstruction algorithms from the diffraction data using Python-based machine learning and image processing. The backbone of the processing workflow is based around grain orientations, which can be calculated using the [Automated Crystal Orientation Mapping](https://nanomegas.com/tem-orientation-imaging/) (ACOM) technique. The dimensionality of the individual crystal orientations maps is reduced through orientation-based clustering into grain components, which are tracked throughout the different tilt-series reference frames, allowing for both grain coupling and orientation refinement. Development of Virtual Reconstruction (VR) algorithms enable orientation-specific contrast and unambiguous determination of the same grain throughout the tilt-series.

This work is explained further in the following publications:

- [Reconstructing Dual-Phase Nanometer Scale Grains within a Pearlitic Steel Tip in 3D through 4D-Scanning Precession Electron Diffraction Tomography and Automated Crystal Orientation Mapping]({% link _publications/007-3DSPED-ultramicroscopy.md %})
- [New Features in Crystal Orientation and Phase Mapping for Transmission Electron Microscopy]({% link _publications/005-symmetry.md %})
- [Reconstructing grains in 3D through 4D Scanning Precession Electron Diffraction]({% link _publications/004-MM.md %})

For those interested in undertaking a similar analysis, a GUI is expected to be released in the future- more to follow! In the mean time check out [`orix`](https://orix.readthedocs.io/en/stable/) for crystallographic analysis using Python.
