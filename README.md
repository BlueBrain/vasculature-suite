# Vasculature Suite

Vasculature Suite is a set of tools created by the Blue Brain Project to process and visualize large-scale morphological reconstructions of the brain vasculature.

- [vascpy](#vascpy) — A toolbox for reading, writing, and manipulating large-scale vasculature graphs.
- [VessMorphoVis](#VessMorphoVis) — A lightweight, interactive, extensible and cross-platform framework for building, visualizing and analyzing vasculature (or blood vessels) morphologies.
- [Vasculature File Format](https://morphology-documentation.readthedocs.io/en/latest/h5-vasc-graph.html) - A file format to describe vasculature datasets.
- [BioExplorer](#bioexplorer) - Extract and analyze scientific data for visualization and interactive exploration.

## vascpy
<img alt="vascpy Banner" src="https://github.com/BlueBrain/vascpy/raw/main/doc/source/logo/BBP-vascpy.jpg" width="600"/>

Useful links:
[GitHub repo](https://github.com/BlueBrain/vascpy),
[Documentation](https://github.com/BlueBrain/vascpy#readme).

**A toolbox for reading, writing, and manipulating large-scale vasculature graphs.**

Digital morphology reconstructions of the brain vasculature are cyclic graph-like structures embedded in the 3D space. Depending on the use-case, they can be either represented as points linked together with edges or as graphs of connected sections (sequences of non-branching consecutive points). Conversion between representations requires a bi-directional mapping, often challenging to obtain. vascpy is a python library for reading, writing, and manipulating large-scale vasculature graphs. It allows for converting between segment and section-centered representations and reading and writing from and to multiple file formats.

## VessMorphoVis
<img alt="VessMorphoVis Banner" src="https://raw.githubusercontent.com/wiki/BlueBrain/VessMorphoVis/images/logos/vmv-logo.jpeg" width="600"/>

Useful links:
[GitHub repo](https://github.com/BlueBrain/VessMorphoVis),
[Documentation](https://github.com/BlueBrain/VessMorphoVis#readme).

**A lightweight, interactive, extensible and cross-platform framework for building, visualizing and analyzing vasculature (or blood vessels) morphologies.**

VessMorphoVis is an integrated suite of toolboxes for interactive visualization and analysis of vast brain vascular networks represented by 
morphological graphs segmented originally from imaging or microscopy stacks. Our workflow leverages the outstanding potentials of Blender, 
aiming to establish an integrated, extensible and domain-specific framework capable of interactive visualization, analysis, repair, 
high-fidelity meshing and high-quality rendering of vascular morphologies. VessMorphoVis is developed as an extension to its sister NeuroMorphoVis.


## BioExplorer
<img alt="BioExplorer Banner" src="https://github.com/BlueBrain/BioExplorer/raw/master/bioexplorer/pythonsdk/notebooks/bioexplorer_banner.png" width="600"/>

**The Blue Brain BioExplorer is a tool for scientists to extract and analyze scientific data for visualization and interactive exploration**

Exploration relies on building software that combines data integration, analysis and interactive visualization to build, modify and navigate through large scientific datasets. For this, Blue Brain built and open-sourced the Blue Brain BioExplorer. It was originally developed to answer key scientific questions related to the Coronavirus as a use case and to deliver a visualization tool. Today, the BioExplorer allows to reconstruct, visualize, explore and describe in detail the structure and function of highly-detailed biological structures such as molecular systems, neurons, astrocytes, blood vessels, and more. You can see the first application of the BioExplorer in [A Machine-Generated View of the Role of Blood Glucose Levels in the Severity of COVID-19](https://www.frontiersin.org/articles/10.3389/fpubh.2021.695139/full?utm_source=F-NTF&utm_medium=EMLX&utm_campaign=PRD_FEOPS_20170000_ARTICLE) study.

Useful links:
[GitHub repo](https://github.com/BlueBrain/BioExplorer),
[Documentation](https://bluebrain.github.io/BioExplorer/).
