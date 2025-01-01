---
title: Scientific software packages & code
slug: packages-and-code
date: 2024-12-25 08:04:00 UTC+02:00
type: text
---

Following the motto of 'build your own tools', a driving philosophy of the lab is to 'build it once, but build it well' when it comes to scientific software tools.

## Packages

### ```beamshapes```
<img src="../beamshapes_logo.webp" width="20%" align="left">
```beamshapes``` is a <a href="https://beamshapes.readthedocs.io/en/latest/" target="_blank"> a Python package </a>  to calculate sound radiation patterns for a few all-round model sound sources. The sound radiation of more detailed sound sources are computationally involved to calculate, and their code isn't available with the published paper. This often means one would use a 'simpler' model that is easier to calculate, rather than implement a more detailed one from scratch. ```beamshapes``` aims to hit the middle ground, implementing a few detailed source models through an open-source package (and hopefully with more sources to come).<br />
<br />
<br />
<br />
<br />

### ```itsfm```
<img src="../itsfm_logo.webp" width="20%" align="left">
<a href="https://itsfm.readthedocs.io/en/latest/" target="_blank"> ```itsfm``` is a Python package</a> to segment sounds by how 'wavy' they are. This package was specifically made to ensure accurate segmentation of the stapler-pin shaped horseshoe bat calls, but is likely to work on other sounds without strong harmonics (see page for examples). For more details on its performance and comparison to commonly used methods see the [see here](https://doi.org/10.1101/2021.01.09.426033). 
<br />
<br />
<br />
<br />
## Other methods & code 
### ```DMCP``` 
<img src="../dmcp_example.png" width="30%" align="left">
A Python implementation of the 'depth-map correspondence' algorithm by Julian Jandeleit. DMCP takes a (thermal/RGB) camera scene and finds the camera location in the LiDAR scene without a calibration object using user annotations. This is a baseline method to align featureless subterranean cave scenes where a range of 'standard' computer-vision methods fail. Link to [the code](https://zenodo.org/records/11242436), and see the paper [here](../Jandeleit_et_al_2024_CV4Animals_CVPR-workshop.pdf).
<br />
<br />
<br />

