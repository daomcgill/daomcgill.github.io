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

  <img src="../img/hist.png" alt="Histogram" width="800px" style="margin-right: 10px">


## Project Overview

The goal of this project was to accurately measure surface curvature values of 3D meshes, specifically scanned human bones. Previously, the measurement of "robusticity" relied on subjective visual assessment, leading to imprecise values with limited analytical value.

To address this, I developed a system using open-source software for analyzing 3D triangular meshes. The challenge in trying to measure surface curvature of a mesh is that it technically does not have a surface. Meshes are created out of many triangle, joined at the vertices to other triangles. To solve this I ended up measuring the change in slope from each triangle's vertex, as it relates to its neighboring vertex. By combining the software's output with custom Python code, I was able to provide a comprehensive statistical analysis of the curvature data.

This was the first project I worked on as a student intern, and it taught me a lot. I went into this not knowing much about any part of the process that would be involved, and ended up figuring out how to do each step, one at a time. Another part that was interesting was working with non-CS people, and being primarily responsible for the creation of the software aspect of a solution, from start to finish. 


  <img src="../img/selection.png" alt="Selection" width="800px" style="margin-right: 10px">


## Project Repository

Find the code and detailed information in the [GitHub repository](https://github.com/daomcgill/meshlab-bone-robusticity).

  <img src="../img/robusticity_ss.jpg" alt="Robusticity" width="800px">

