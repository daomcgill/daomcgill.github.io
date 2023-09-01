---
layout: project
type: project
image: img/hist.png
title: "Interpreting Surface Curvature Data on 3D Bone Meshes"
date: 2023-08-31
published: true
labels:
  - Meshlab
  - Python
summary: "Python code for interpreting raw surface curvature data on 3D bone meshes."
---

<div align="center">
  <img src="../img/hist.png" alt="Histogram" width="300px" style="margin-right: 10px">
  <img src="../img/selection.png" alt="Selection" width="300px" style="margin-right: 10px">
  <img src="../img/robusticity_ss.jpg" alt="Robusticity" width="300px">
</div>

## Project Overview

The goal of this project was to accurately measure surface curvature values of 3D meshes, specifically scanned human bones. Previously, the measurement of "robusticity" relied on subjective visual assessment, leading to imprecise values with limited analytical value.

To address this, I developed a system using open-source software for analyzing 3D triangular meshes. By combining the software's output with custom Python code, I was able to provide a comprehensive statistical analysis of the curvature data.

## Project Repository

Find the code and detailed information in the [GitHub repository](https://github.com/daomcgill/meshlab-bone-robusticity).
