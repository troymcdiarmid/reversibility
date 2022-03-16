# Kepler-McDiarmid-Rankin-2022-AID-Reversibility-Analysis

Analysis code for "Rapid Assessment of the Temporal Function and Phenotypic Reversibility of Neurodevelopmental Disorder Risk Genes in C. elegans" (DOI: https://doi.org/10.1101/2021.10.21.465355)

<!-- TABLE OF CONTENTS -->
## Table of Contents
* [About the Project](#about-the-project)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
  * [Data](#data)
* [Contact](#contact)
* [Project authors](#project-authors)
* [Acknowledgements](#acknowledgements)



<!-- ABOUT THE PROJECT -->
## About The Project

* Preprint (BioRxiv): [https://doi.org/10.1101/2021.10.21.465355](https://doi.org/10.1101/2021.10.21.465355)
* Data repository (Dataverse): https://doi.org/10.5683/SP3/NOZWXZ
* Analysis source code repository (Github): [https://github.com/troymcdiarmid/reversibility/](https://github.com/troymcdiarmid/reversibility/)

>SUMMARY:  
>Hundreds of genes have been implicated in neurodevelopmental disorders. Previous studies have indicated that some phenotypes caused by decreased developmental function of select risk genes can be reversed by restoring gene function in adulthood. However, very few risk genes have been assessed for adult reversibility. We developed a strategy to rapidly assess the temporal requirements and phenotypic reversibility of neurodevelopmental disorder risk gene orthologs using a conditional protein degradation system and machine vision phenotypic profiling in Caenorhabditis elegans. Using this approach, we measured the effects of degrading and re- expressing orthologs of 3 neurodevelopmental risk genes EBF3, BRN3A, and DYNC1H1 across 30 morphological, locomotor, sensory, and learning phenotypes at multiple timepoints throughout development. We found some degree of phenotypic reversibility was possible for each gene studied. However, the temporal requirements of gene function and degree of phenotypic reversibility varied by gene and phenotype. The data reflects the dynamic nature of gene function and the importance of using multiple time windows of degradation and re-expression to understand the many roles a gene can play over developmental time. This work also demonstrates a strategy of using a high-throughput model system to investigate temporal requirements of gene function across a large number of phenotypes to rapidly prioritize neurodevelopmental disorder genes for re-expression studies in other organisms.

Please see the pre-print for more information about the project.


<!-- GETTING STARTED -->
## Getting Started

Make sure that you have R installed with the requirements listed below. Raw and processed data can be obtained from the Dataverse link mentioned above or from the authors upon request.

### Prerequisites
The code was executed using the following R version and platform:
```
R version 4.0.0 (2020-04-24) -- "Arbor Day"
Copyright (C) 2020 The R Foundation for Statistical Computing
Platform: x86_64-apple-darwin17.0 (64-bit)
```

### Installation
The R packages required for this project are listed at the beginning of each markdown. The code in each markdown is used to analyze the data from one gene (several experiments per gene). See the bioRxiv for further details about the project. There may be additional system packages that need to be installed outside of the R environment.

Please report any missing dependencies/requirements by [opening an issue](https://github.com/troymcdiarmid/peel-1/issues) on this repository.

### Data
Raw or preprocessed data can be obtained from our lab dataverse or from the authors upon request.


<!-- LICENSE -->
<!--
## License

Distributed under the *** License. See `LICENSE` for more information.
-->


<!-- CONTACT -->
## Contact
For questions or comments specific to the implementation provided in this repository, please contact:

Troy A. McDiarmid - [GitHub](https://github.com/troymcdiarmid) - [@Troy_McD_UBC](https://twitter.com/Troy_McD_UBC)

Additional questions about the project, such as further information and requests for resources and reagents should be directed to and will be fulfilled by the Lead Contact, Catharine H. Rankin (crankin@psych.ubc.ca).

<!-- PROJECT AUTHORS -->
## Project authors
* Lexis D. Kelper  
* Troy A. McDiarmid
* Catharine H. Rankin

<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
The authors thank Dr. Kota Mizumoto for the rab-3p::TIR1 strain that was used for neuron specific degradation and the CGC (funded by National Institute of Health Office of Research Infrastructure Programs, P40 OD010440) for other strains used within this research. This project was supported by a Canadian Institutes of Health Research (CIHR) Doctoral Research Award to L.D.K; a Canadian Institutes of Health Research (CIHR) Doctoral Research Award to T.A.M.; and a CIHR project grant (CIHR MOP PJT-165947) to C.H.R.
