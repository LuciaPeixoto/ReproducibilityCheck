# Reproducibility Check

Data-intensive analyses represent a growing part of the scientific literature.
With this document we aim to provide a checklist to help scientifically-inclined readers assess the reproducibility of computational analyses.
We expect that this may be useful to journalists, certain program officers, and members of the public who wish to assess work to the extent possible without directly attempting to replicate findings.

This document is structured as a checklist.
Our aim is to design a checklist that can be completed using only the materials and methods section of a published paper.
Our checklist focuses on a number of components key to reproducibility, which currently includes data, source code, computing environment.
We expect more checked boxes to indicate work that is more reproducible.

## Data

- [ ] URLs or supplementary files are provided for all datasets described in the project.
- [ ] All raw data described in the project have either a database-assigned identifier or DOI to indicate the version of record.
- [ ] If preprocessing or quality control has been performed, the version of the data after preprocessing is provided and clearly noted.
  - [ ] The preprocessed data have a database-assigned identifier or a DOI to indicate the version used in the paper in question.
- [ ] Datasets, databases, or other resources have a clearly specified license that permits reuse.

## Source Code

- [ ] The location where all source code can be found is clearly specified.
- [ ] The source code is made available via a version control service.
- [ ] The authors clearly specify a single script or workflow that will automatically regenerate the results of their analyses.
- [ ] The specific version of the source code associated with the paper has been assigned a DOI by an archiving service (e.g. Figshare, Zenodo).
- [ ] The source code has an [open license](http://opendefinition.org/guide/). Common open licenses for academic software include "BSD" and "MIT" licenses.

## Computing Environment

- [ ] All software specifically used by the authors has a version number listed in the manuscript.
- [ ] The authors provide a computing environment capable of reproducing the results (keywords: virtual machine image, docker container, singularity container).
- [ ] The computing environment has been assigned a DOI by an archiving service (e.g. Figshare, Zenodo)
- [ ] The authors have used software to demonstrate that their results can be automatically replicated in an independent computing environment (e.g. "Continuous Analysis", "Continuous Integration").
