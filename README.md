
<!-- README.md is generated from README.Rmd. Please edit that file -->

# microbiomeMarker

<a href='https://github.com/yiluheihei/microbiomeMarker'/><img src='man/figures/microbiomeMarker.png' height="150" align="right" />

<!-- badges: start -->

[![](https://img.shields.io/badge/release%20version-1.0.0-green.svg)](https://www.bioconductor.org/packages/microbiomeMarker)
[![](https://img.shields.io/badge/devel%20version-1.1.1-green.svg)](https://github.com/yiluheihei/microbiomeMarker)
[![platform](http://www.bioconductor.org/shields/availability/devel/microbiomeMarker.svg)](https://www.bioconductor.org/packages/devel/bioc/html/microbiomeMarker.html#archives)
[![BioC
status](http://www.bioconductor.org/shields/build/release/bioc/microbiomeMarker.svg)](https://bioconductor.org/checkResults/release/bioc-LATEST/microbiomeMarker)
[![Bioc
years](http://www.bioconductor.org/shields/years-in-bioc/microbiomeMarker.svg)](https://www.bioconductor.org/packages/devel/bioc/html/microbiomeMarker.html#since)
[![R build
status](https://github.com/yiluheihei/microbiomeMarker/workflows/R-CMD-check-bioc/badge.svg)](https://github.com/yiluheihei/microbiomeMarker/actions)
[![License: GPL
v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://github.com/yiluheihei/microbiomeMarker/blob/master/LICENSE.md)
[![Codecov test
coverage](https://codecov.io/gh/yiluheihei/microbiomeMarker/branch/master/graph/badge.svg)](https://codecov.io/gh/yiluheihei/microbiomeMarker?branch=master)
[![DOI](https://zenodo.org/badge/215731961.svg)](https://zenodo.org/badge/latestdoi/215731961)
[![Lifecycle:
stable](https://img.shields.io/badge/lifecycle-stable-brightgreen.svg)](https://lifecycle.r-lib.org/articles/stages.html#stable)
![GitHub Repo
stars](https://img.shields.io/github/stars/yiluheihei/microbiomeMarker?style=social)
<!-- badges: end -->

***microbiomeMarker*** is still under development, your suggestion and
contribution will be highly appreciated. If you think this project is
helpful to you, you can give this project a :star:.

## Motivation

The aim of this package is to build a unified toolbox in R for
microbiome biomarker discovery by integrating existing widely used
differential analysis methods.

## Installation

Install the package from Bioconductor directly:

``` r
if (!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")

BiocManager::install("microbiomeMarker")
```

Or install the development version of the package from
[Github](https://github.com/yiluheihei/microbiomeMarker).

``` r
if (!requireNamespace("remotes", quietly=TRUE))
  install.packages("remotes")
remotes::install_github("yiluheihei/microbiomeMarker")
```

For more details on how to use ***microbiomeMarker***, please see the
help page or
[website](https://yiluheihei.github.io/microbiomeMarker/index.html) of
our package.

## Citation

Kindly cite as follows: Yang Cao (2020). microbiomeMarker: microbiome
biomarker analysis toolkit. R package version 0.99.0.
<https://github.com/yiluheihei/microbiomeMarker>. doi:
[10.5281/zenodo.3749415](https://doi.org/10.5281/zenodo.3749415).

Please cite the corresponding methods paper too:

-   LEfSe: Segata, Nicola, Jacques Izard, et al. 2011. Metagenomic
    Biomarker Discovery and Explanation. Genome Biology 12 (6): 1–18.
    doi:
    [10.1186/gb-2011-12-6-r60](https://doi.org/10.1186/gb-2011-12-6-r60)
-   metagenomeSeq: Paulson, Joseph N, O Colin Stine, et al. 2013.
    Differential Abundance Analysis for Microbial Marker-Gene Surveys.
    Nature Methods 10 (12): 1200–1202. doi:
    [10.1038/nmeth.2658](https://doi.org/10.1038/nmeth.2658)
-   ANCOM: Mandal, Siddhartha, Will Van Treuren, et al. 2015. Analysis
    of Composition of Microbiomes: A Novel Method for Studying Microbial
    Composition. Microbial Ecology in Health and Disease 26 (1): 27663.
    doi:
    [10.3402/mehd.v26.27663](https://doi.org/10.3402/mehd.v26.27663)
-   ANCOMBC: Lin, Huang, and Shyamal Das Peddada. 2020. Analysis of
    Compositions of Microbiomes with Bias Correction. Nature
    Communications 11 (1): 1–11. doi:
    [10.1038/s41522-020-00160-w](https://doi.org/10.1038/s41522-020-00160-w)
-   ALDEx2: Fernandes, Andrew D, Jennifer Ns Reid, et al. 2014. Unifying
    the Analysis of High-Throughput Sequencing Datasets: Characterizing
    Rna-Seq, 16S rRNA Gene Sequencing and Selective Growth Experiments
    by Compositional Data Analysis. Genome Biology 15(2): 1–17. doi:
    [10.1186/2049-2618-2-15](https://doi.org/10.1186/2049-2618-2-15)
-   edgeR: Robinson, Mark D, Davis J McCarthy, and Gordon K Smyth. 2010.
    EdgeR: A Bioconductor Package for Differential Expression Analysis
    of Digital Gene Expression Data. Bioinformatics 26 (1): 139–40. doi:
    [10.1093/bioinformatics/btp616](https://doi.org/10.1093/bioinformatics/btp616)
-   DESeq2: Love, Michael I, Wolfgang Huber, and Simon Anders. 2014.
    Moderated Estimation of Fold Change and Dispersion for Rna-Seq Data
    with Deseq2. Genome Biology 15 (12): 1–21. doi:
    [10.1186/s13059-014-0550-8](https://doi.org/10.1186/s13059-014-0550-8)
-   limma-voom: Law, Charity W, Yunshun Chen, et al. 2014. Voom:
    Precision Weights Unlock Linear Model Analysis Tools for Rna-Seq
    Read Counts. Genome biology, 15(2), 1-17. doi:
    [10.1186/gb-2014-15-2-r29](https://doi.org/10.1186/gb-2014-15-2-r29)

### Publications citing microbiomeMarker

-   Shanmugam G, Lee SH, Jeon J. EzMAP: Easy Microbiome Analysis
    Platform. BMC bioinformatics. 2021 Dec;22(1):1-0. doi:
    [10.1186/s12859-021-04106-7](https://doi.org/10.1186/s12859-021-04106-7)
-   Altaib H, Nakamura K, Abe M, et al. Differences in the concentration
    of the fecal neurotransmitters GABA and glutamate are associated
    with microbial composition among healthy human subjects.
    Microorganisms. 2021. Feb;9(2):378. doi:
    [10.3390/microorganisms9020378](https://doi.org/10.3390/microorganisms9020378)
-   Ingham AC, Kielsen K, Mordhorst H, et al. Microbiota long-term
    dynamics and prediction of acute graft-versus-host-disease in
    pediatric allogeneic stem cell transplantation. medRxiv. 2021 Jan 1.
    doi:
    [10.1101/2021.02.19.21252040](https://doi.org/10.1101/2021.02.19.21252040)
-   Künstner A, Aherrahrou R, Hirose M, et al. Effect of Differences in
    the Microbiome of Cyp17a1-Deficient Mice on Atherosclerotic
    Background. Cells. 2021 Jun;10(6):1292.  
    doi: [10.3390/cells10061292](https://doi.org/10.3390/cells10061292)
-   Ingham AC, Urth TR, Sieber RN, et al. Dynamics of the human nasal
    microbiota and Staphylococcus aureus CC398 carriage in pig truck
    drivers across one workweek. Applied and Environmental Microbiology.
    2021 Jun 30:AEM-01225. doi:
    [10.1128/AEM.01225-21](https://doi.org/10.1128/AEM.01225-21).
-   Shibata T, Nakagawa M, Coleman HN, et al. Evaluation of DNA
    extraction protocols from liquid-based cytology specimens for
    studying cervical microbiota. Plos one 16, no. 8 (2021). doi:
    [10.1371/journal.pone.0237556](https://doi.org/10.1371/journal.pone.0237556)

## Question

If you have any question, please file an issue on the issue tracker
following the instructions in the issue template:

Please briefly describe your problem, what output actually happened, and
what output you expect.

Please provide a minimal reproducible example. For more details on how
to make a great minimal reproducible example, see
<https://stackoverflow.com/questions/5963269/how-to-make-a-great-r-reproducible-example>
and <https://www.tidyverse.org/help/#reprex>.

    Brief description of the problem

    # insert minimal reprducible example here

## Acknowledgement

We thanks all the developers of the methods integrated into our package.

-   [lefse python
    script](https://bitbucket.org/biobakery/biobakery/wiki/lefse), The
    main lefse code are translated from ***lefse python script***,
-   [microbiomeViz](https://github.com/lch14forever/microbiomeViz),
    cladogram visualization of lefse is modified from
    ***microbiomeViz***.
-   [phyloseq](https://github.com/joey711/phyloseq), the main data
    structures used in ***microbiomeMarker*** are from or inherit from
    `phyloseq-class` in package ***phyloseq***.
-   [MicrobiotaProcess](https://github.com/YuLab-SMU/MicrobiotaProcess),
    function `import_dada2()` and `import_qiime2()` are modified from
    the `MicrobiotaProcess::import_dada2()`.
-   [qiime2R](https://github.com/jbisanz/qiime2R), `import_qiime2()` are
    refer to the functions in ***qiime2R***.
