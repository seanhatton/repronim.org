---
title: "HeuDiConv"
date: 2024-11-27T11:03:21-05:00
weight: 20
---

*Flexible DICOM conversion into structured directory layouts.*

HeuDiConv (Heuristic DICOM Converter) is a command line converter from DICOM to BIDS (or other structured layouts).  HeuDiConv's conversion parameters are encoded as configurable Python code ("heuristics"), enabling flexible and efficient use.

### Development status

HeuDiConv is production software and is actively maintained.

### Innovation

Conversion from DICOM to more usable formats is complicated and requires managing a lot of metadata, but some flexibility is needed to prepare the data in a form appropriate for the next steps.  HeuDiConv allows the user to efficiently manage the flexibility while hiding unneeded complexity.

### Citation information

[RRID:SCR_017427](https://scicrunch.org/resolver/RRID:SCR_017427)

### Requisite knowledge to use

- Command line
- Desired project structure (BIDS)
- Python

### Requisite technical requirements

- Collecting DICOMs from MRI (not NIfTI, PAR/REC, etc)
- Python OR Docker OR Singularity OR Debian
- DataLad (optional)

### Links

- Home page: https://heudiconv.readthedocs.io/
- Tutorial: https://heudiconv.readthedocs.io/en/latest/tutorials.html
- Installation: https://heudiconv.readthedocs.io/en/latest/installation.html
- Full documentation: https://heudiconv.readthedocs.io/
- How to get help:
  - https://github.com/nipy/heudiconv/issues
  - https://neurostars.org/tag/heudiconv

### Representative publications
