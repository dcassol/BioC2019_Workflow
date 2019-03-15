# *systemPipeR*'s New CWL Command-line Interface

# Instructor name and contact information
* Daniela Cassol (danielac@ucr.edu) - Main Presenter 
* Thomas Girke (thomas.girke@ucr.edu) - PI of Project

Institute for Integrative Genome Biology, University of California, Riverside, California, USA.

# Workshop Description

This workshop introduces how to use *systemPipeR's* new CWL (Common Workflow Language) interface to run data analysis workflows composed of both R and command-line analysis routines. CWL is a widely used community standard for describing analysis workflows in a generic and reproducible manner. This way *systemPipeR* workflows can be run from a single specification instance either entirely from within R, from various command-line wrappers (e.g. *cwl-runner*) or from other languages (*e.g.* Bash or Python). This includes support for both command-line and R/Bioconductor software as well as resources for parallel evaluations on computer clusters along with automated generation of interactive analysis reports. The introduction of the workshop will provide an overview of the design of the new CWL S4 class, while the hand-on components will cover the basic usage of CWL from both within R and the command-line, as well as the construction of custom workflows. A short use-case demonstration will guide users through a basic small-RNA-Seq profiling workflow that will include read mappings with variable parameter settings of two popular short-read aligners (HISAT2 and STAR), read quantification and statistical analyses steps as well as automation routines for running NGS workflows from start to finish with a single command. The last part will demonstrate how to parallelize the analysis of a relatively large NGS data sets on multiple CPU cores of single machines as well as computer clusters with a scheduler (*e.g.* Slurm). 


## Pre-requisites

- Basic knowledge of R and usage of Bioconductor packages for NGS analysis
- Basic knowledge of running command-line software
- Basic knowledge of parallelization concepts 

Non-essential background reading:

* [systemPipeR vignette](https://bioconductor.org/packages/devel/bioc/html/systemPipeR.html)
* [BiocParallel vignette](https://bioconductor.org/packages/release/bioc/html/BiocParallel.html)
* [R Markdown tutorial](https://rmarkdown.rstudio.com/lesson-2.html)

## Workshop Participation

Participants will be able to perform all analysis components of this workshop hands-on. Active user participation in all forms throughout the event is highly encouraged including but not limited to lecture material, hands-on sections and final discussion about package improvements. Most likely, the final computer cluster example will be demonstrated by the presenter rather than performed by all participants, because the AMI instances provided during the conference are unlikely to provide cluster/scheduler support.  

## _R_ / _Bioconductor_ packages used

* [`systemPipeR`](http://www.bioconductor.org/packages/release/bioc/html/systemPipeR.html)
* [`systemPipeRdata`](http://www.bioconductor.org/packages/release/data/experiment/html/systemPipeRdata.html)

## Time outline

1h 45m total

| Activity                                        | Time |
|-------------------------------------------------|------|
| Introduction                                    |  5m  |
| Overview of *systemPipeR* package               | 20m  |
| Introduction to CWL and its new S4 class        | 20m  |
| Building a custom workflow with CWL             | 20m  |
| Showcase small RNA-Seq workflow                 | 30m  |
| Parallelization on single machines and clusters | 10m  |

# Workshop goals and objectives

## Learning goals

* Usage of a generic R-based workflow construction environment that is both scalable and reproducible 
* Integration of command-line tools via the CWL community standard
* Design of CWL workflows
* Rendering of R markdown reports and critical assessment of scientific analysis reports
* Parallelization of big data analysis tasks

## Learning objectives

* How to make analysis workflows more robust, reproducible and portable across heterogeneous computing systems
* Usage of new CWL S4 class
* Optimize and debug workflows 
* Inspection of technical reports and log files 
* Design of new and fully customized workflows 

