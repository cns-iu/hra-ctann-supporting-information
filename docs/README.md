# Constructing, Validating, and Using Human Reference Atlas Cell Type Annotation Crosswalks

Nicole Vasilevsky<sup>1,2*</sup>, Aleix Puig-Barbe<sup>3*</sup>, Andreas Bueckle<sup>1</sup>, Ellen M. Quardokus<sup>1</sup>, Yongxin Kong<sup>1</sup>, Divya Prasanth  Paraman<sup>1</sup>, Jie Zheng<sup>4</sup>, Yongqun He<sup>4</sup>, Yashvardhan Jain<sup>1</sup>, Bruce W. Herr II<sup>1</sup>, Katy Börner<sup>1*</sup>

<sup>1</sup> Department of Intelligent Systems Engineering, Luddy School of Informatics, Computing, and Engineering, Indiana University, Bloomington, IN, USA  
<sup>2</sup> Rose City Data Science, Portland, OR, USA  
<sup>3</sup> European Bioinformatics Institute (EMBL-EBI), Wellcome Genome Campus, Hinxton, Cambridge CB10 1SD, UK  
<sup>4</sup> University of Michigan Medical School, Ann Arbor, MI, USA  

## Abstract

The Human Reference Atlas (HRA) v2.5 includes 4,807 anatomical structures, 1,347 cell types, and 2,215 biomarkers (genes, proteins, lipids); 81 organs with 1,392 anatomical structures modeled in three dimensions (3D). Mapping new data into the HRA requires 3D spatial registration and/or cell type annotation (CTann). Many CTann tools exist but few use cell type names linked to Cell Ontology (CL)—making comparisons across tools, tissues, and organs difficult. The HRA supports five transcriptomics CTann tools (Azimuth, CellTypist, popV, FR-Match, Pan-Human Azimuth), four sc-proteomics CTann tools (DeepCell Types, DeepCell Types-HuBMAP, Robust Image-Based Cell Annotator [RIBCA], and SpaTial cELl LeARning [STELLAR]), plus a Cell Distance Explorer (CDE) Spatial Omics collection covering previously published annotations across 12 tissue types with 47,349,496 cells. Assigned cell types differ in number, resolution, and coverage. This paper details how 10 crosswalks were constructed, validated, and used to compile a ‘Supertree’ that can be used to compare CTann across organs and technologies in support of reference atlas constitution and usage.

## GitHub Repository

The repo is structured in the following way:
```
├── data
├── docs
├── figures
├── notebooks
├── supertree
```

The **data** folder contains the color codes for the anatomical structures and supertree, as well as the raw table for Table 1 and Table 2.

The **docs** folder contains the supertree files and ReadMe to generate this website.

The **figures** contains the figure files for Figures 1 and 2 (png and svg formats).

The **notebooks** contains the underlying code for Figures 1 and 2 and Tables 1 and 2.

The **supertree** contains the code for the interactive Supertree visualization tool.

## Data Availability

The following Digital Objects are described in this paper and are available at the link below:  
Azimuth: https://purl.humanatlas.io/ctann/azimuth/v1.4  
CellTypist: https://purl.humanatlas.io/ctann/celltypist/v1.3  
DeepCell Types: https://purl.humanatlas.io/ctann/deepcelltypes/v1.2  
DeepCell Types-HuBMAP: https://purl.humanatlas.io/ctann/deepcelltypes-hubmap/v1.2  
FR-Match: https://purl.humanatlas.io/ctann/frmatch/v1.0  
Pan-Human Azimuth: https://purl.humanatlas.io/ctann/pan-human-azimuth/v1.2  
popV: https://purl.humanatlas.io/ctann/popv/v1.4  
RIBCA: https://purl.humanatlas.io/ctann/ribca/v1.0  
STELLAR: https://purl.humanatlas.io/ctann/stellar/v1.0  
CDE Spatial Omics: https://purl.humanatlas.io/ctann/vccf/v1.2  

Supertree [to be added]

## Link to Interactive Supertree Visualization
The interactive Supertree can be found [here](https://cns-iu.github.io/hra-ctann-supporting-information/supertree/).
The Supertree source code and usage instructions are in the [/supertree directory](https://github.com/cns-iu/hra-ctann-supporting-information/tree/main/supertree). 
