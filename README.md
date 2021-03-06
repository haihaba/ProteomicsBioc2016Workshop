R/Bioconductor tools for mass spectrometry-based proteomics
===========================================================

[![Build Status](https://travis-ci.org/lgatto/ProteomicsBioc2016Workshop.svg?branch=master)](https://travis-ci.org/lgatto/ProteomicsBioc2016Workshop)

*[Bioconductor conference](http://bioconductor.org/help/course-materials/2016/BioC2016/),
Stanford University, 26 July 2016*

In this workshop, we will use R/Bioconductor packages to explore,
process, visualise and understand mass spectrometry-based proteomics
data, starting with raw data, and proceeding with identification and
quantitation data, discussing some of their peculiarities compared to
sequencing data along the way. The participants will gain a general
overview of Bioconductor packages for mass spectrometry and
proteomics, and learn how to navigate raw data and reconstruct
quantitative data. The workshop is aimed at a beginner to intermediate
level, such as, for example, seasoned R users who want to get started
with mass spectrometry and proteomics, or proteomics practitioners who
want to familiarise themselves with R and Bioconductor infrastructure.

Read the vignette online [here](http://lgatto.github.io/ProteomicsBioc2016Workshop).

To open the vignette

```r
library("ProteomicsBioc2016Workshop")
bioc2016()
```

To run/experiment with the code in the vignette

```r
file.edit(system.file("doc", "Bioc2016.R", package = "ProteomicsBioc2016Workshop"))
```
