---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Mechanical / CAE Engineer with 8+ years of industry experience in automotive and energy systems, specializing in structural analysis, fatigue, thermal modeling, and simulation-driven design.

My work focuses on bridging physics-based engineering with data-driven methods to solve real-world problems. I have hands-on experience with FEA, CFD, heat transfer, durability, and design-by-analysis, and I increasingly use Python and machine-learning techniques (including Physics-Informed Neural Networks) to improve model accuracy, automation, and decision-making.

I enjoy building reproducible engineering tools, validating simulations against test data, and documenting assumptions clearly so results can be trusted by design, test, and verification teams.

What I Work On
======
Finite Element Analysis (linear, nonlinear, contact, plasticity, fatigue)

Thermal modeling & heat transfer (lumped and transient models)

Physics-Informed Neural Networks (PINNs) for thermal & life prediction

Data analysis, optimization, and workflow automation using Python

Engineering validation, correlation with test data, and reporting

Tools & Technologies
------
Simulation: ANSYS, Abaqus, HyperMesh, Fluent

Programming: Python, MATLAB

Methods: ASME design-by-analysis, strain-life fatigue, Weibull & Arrhenius life models

Data & ML: NumPy, SciPy, optimization, PINNs

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.


