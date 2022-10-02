---
hide:
  - navigation
  - toc
---

<img align="right" src="images/8BIT_small.jpg" width="200" height="180">
# GitHub Pages

## Author: Jordy Coolen

#
#
# Projects

## [EasySeq RC-PCR SARS-CoV-2](https://github.com/JordyCoolen/easyseq_covid19)
This github repository contains an automated pipeline dedicated to properly analyse the EasySeq SARS-CoV-2 (COVID-19) sequence sequencing data. Validated with 150/151 bp paired-end reads.

Coolen, J. P., Wolters, F., Tostmann, A., van Groningen, L. F., Bleeker-Rovers, C. P., Tan, E. C., ... & Melchers, W. J. (2021). SARS-CoV-2 whole-genome sequencing using reverse complement PCR: For easy, fast and accurate outbreak and variant analysis. Journal of Clinical Virology, 144, 104993. https://doi.org/10.1016/j.jcv.2021.104993

#
## [MyCodentifier](https://jordycoolen.github.io/MyCodentifier/)
# [![Alt text](images/mycodentifier.png?raw=true "8BIT")](https://jordycoolen.github.io/MyCodentifier/)
The pipeline is constructed using nextflow as workflow manager running in a docker container. It is able to identify species of TB/nTM from positive MGIT cultures. To do so it uses a hsp65 database for fast identification coupled with a Metagenomic method using centrifuge to identify on genome level. For TB it also is able to identify subspecies. Results are presented in automated pdf and html reports.

#
#
## [RC-PCR Classifier](https://jordycoolen.github.io/RC-PCR_CLASSIFIER/)

[![Alt text](images/shankeyplot_mock.png?raw=true "shankeyplot")](https://jordycoolen.github.io/RC-PCR_CLASSIFIER/)