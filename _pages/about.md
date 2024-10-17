---
permalink: /
title: "Anish K. Simhal, PhD."
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Anish is a postdoctoral researcher at Memorial Sloan Kettering Cancer Center's Department of Medical Physics, focusing on innovative network science-based approaches to cancer research, particularly in the field of multiple myeloma (MM). 

Advised by [Dr. Joseph Deasy]( https://www.mskcc.org/research-areas/labs/joseph-deasy), Anish’s work primarily revolves around applying advanced computational and network analysis techniques to better understand cancer biology and improve patient prognosis. Anish received his PhD in computer vision/electrical engineering from Duke University, advised by [Dr. Guillermo Sapiro](https://ece.princeton.edu/people/gsapiro). Anish did his undergraduate degree in electrical engineering from The University of Virginia, where he worked with [Dr. Scott Acton](https://engineering.virginia.edu/faculty/scott-t-acton) and [Dr. John Lach](https://engineering.gwu.edu/john-lach). 

He has conducted novel research on gene interaction networks in multiple myeloma. His work involves integrating complex gene-product interactions to characterize global patterns of MM biological behavior. This approach has led to the identification of novel genomic subtypes and potential new therapeutic targets. 

Anish's research demonstrates a multidisciplinary approach, combining advanced computational methods with biological insights to push the boundaries of cancer research and potentially improve patient outcomes.

The full list of publications can be found on [Google Scholar](https://scholar.google.com/citations?user=NefDuV0AAAAJ&hl=en). Curriculum vitae is [here](https://aksimhal.github.io/files/simhal_cv.pdf). 


&nbsp;

Genomic Network Analysis in Multiple Myeloma
----------
Here, Anish used a novel measure of network robustness called Ollivier-Ricci curvature (ORC) to characterize cancers. This innovative geometric network analysis integrates complex gene-product interactions to uncover patterns in cancer biology that were previously undetectable.

ORC designed for -omic data was released as a stand-alone Python package, "ORCO," available for download [here](https://pypi.org/project/orcomics). Details about the ORCO implementation can be found on biorxiv ([PDF](https://www.biorxiv.org/content/10.1101/2024.10.06.616915v1.full.pdf)).

> A.K. Simhal, C. Weistuch, K.A. Murgas, D. Grange, J. Zhu, J.H. Oh, R. Elkin, J.O. Deasy. ["ORCO: Ollivier-Ricci Curvature-Omics: an unsupervised method for analyzing robustness in biological systems."](https://www.biorxiv.org/content/10.1101/2024.10.06.616915v1.full.pdf) 2024. bioRxiv. 


Using Ollivier-Ricci curvature (a measure of network robustness), we identified 118 genes previously unassociated with MM that identify a high risk subtype. This paper described a novel eight gene signature associated with high-risk multiple myeloma: *BUB1*, *MCM6*, *NOSTRIN*, *PAM*, *RNF115*, *SNCAIP*, *SPRR2A*, & *WEE1*. 

> A.K. Simhal, K.H. Maclachlan, R. Elkin, J. Zhu, L. Norton, J.O. Deasy, J.H. Oh, S.Z. Usmani, A. Tannenbaum. [Gene interaction network analysis in multiple myeloma detects complex immune dysregulation associated with shorter survival.](https://www.nature.com/articles/s41408-023-00935-2) 2023. Blood Cancer Journal.

### WEE1 is a strong prognostic marker of high-risk MM

Of all 8 genes, *WEE1* was the most prognostic. When researching WEE1 expression further, WEE1 was found to be incredibly prognostic for MM outcomes independent of known MM biomarkers. Additionally, the results show WEE1 expression differentiates outcomes associated with known markers, is upregulated independently of its interacting neighbors, and is associated with dysregulated P53 pathways. This suggests that WEE1 expression levels may have clinical utility in prognosticating outcomes in newly diagnosed MM and may support the application of WEE1 inhibitors to MM preclinical models. 

> A.K. Simhal, R.S. Firestone, J.H. Oh, V. Avutu, L. Norton, M. Hultcrantz, S.Z. Usmani, K.H. Maclachlan, J.O. Deasy. [“High WEE1 expression is independently linked to poor survival in multiple myeloma.”](https://www.biorxiv.org/content/10.1101/2024.09.20.613788v1) 2024. bioRxiv.

&nbsp;


Network-based studies of autism spectrum disorders using MRI 
----------
These papers were the first to use a measure of network robustness, Ollivier-Ricci curvature, to analyze DTI images of children with ASD. The papers showed the differences in brain connectivity before and after a stem cell transfusion. 

> A. K. Simhal, K. L. H. Carpenter, J. Kurtzberg, A. Song, A. Tannenbaum, L. Zhang, G. Sapiro, G. Dawson. [“Changes in the geometry and robustness of diffusion tensor imaging net- works: secondary analysis from a randomized controlled trial of young autistic children receiving an umbilical cord blood infusion.”](https://www.frontiersin.org/articles/10.3389/fpsyt.2022.1026279/full) 2022. Frontiers in Psychiatry.

> A. K. Simhal, K. L. H. Carpenter, S. Nadeem, J. Kurtzberg, A. Song, A. Tannenbaum, G. Sapiro, G. Dawson. [“Measuring robustness of brain networks in autism spectrum disorder with Ricci curvature.”](https://www.nature.com/articles/s41598-020-67474-9) 2020. Scientific Reports.


&nbsp;



Autism Spectrum Disorders & Random Forest Models
----------
The first paper uses random forest (RF) models to figure what helps kids with ASD successfully complete MRI scans. The second uses RF to model survey data to examine what helped kids with ASD through the COVID-19 pandemic. 

> A. K. Simhal, J. O. A. Filho, P. Segura, J. Cloud, E. Petkova, R. Gallagher, F. X. Castellanos, S. Colcombe, M. P. Milham, A. D. Martino. [“Predicting multiscan MRI outcomes in children with neurodevelopmental conditions following MRI simulator training.”](https://www.sciencedirect.com/science/article/pii/S1878929321000992) 2021. Developmental Cognitive Neuroscience.

> B. Vibert, ..., A. K. Simhal, ..., A. D. Martino. [“CRISIS AFAR: An International Collaborative Study of the Impact of the COVID-19 Pandemic on Youth with Autism and Neurodevelopmental Conditions.”](https://link.springer.com/article/10.1186/s13229-022-00536-z) 2023. Molecular Autism.

&nbsp;


Synapse Biology & Image Processing
-----------
This trio of papers presents a novel unsupervised method for synapse detection. The method, designed for array tomography, detects and characterizes synapses and astrocytes in mouse brain tissue. The method was used to examine synaptic differences in mouse models of fragile X syndrome, a type of ASD. I've presented this work at various meetings and multiple labs have adapted the methodology into their pipelines. 

> A. K. Simhal, Y. Zuo, M. M. Perez, D. V. Madison, G. Sapiro, and K. D. Micheva. [“Multifaceted changes in synaptic composition and astrocytic involvement in a mouse model of fragile x syndrome.”](https://www.nature.com/articles/s41598-019-50240-x) 2019. Scientific Reports.

> A. K. Simhal, B. Gong, J. S. Trimmer, R. J. Weinberg, S. J. Smith, G. Sapiro, and K. D. Micheva. [“A computational synaptic antibody characterization tool for array tomography.”](https://www.frontiersin.org/articles/10.3389/fnana.2018.00051/full)  2018. Frontiers in Neuroanatomy.

> A. K. Simhal, C. Aguerrebere, F. Collman, J. T. Vogelstein, K. D. Micheva, R. J. Weinberg, S. J. Smith, and G. Sapiro. [“Probabilistic fluorescence-based synapse detection.”](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005493) 2017. PLoS Computational Biology.

&nbsp;


Cervical Cancer & Machine Learning (SVM models)
--------
We developed an image processing pipeline to automate detections of various cervical lesions taken via a pocket colposcope. 

> M. N. Asiedu, A. K. Simhal, U. Chaudhary, J. L. Mueller, C. T. Lam, J. W. Schmitt, G. Venegas, G. Sapiro, and N. Ramanujam. [“Development of algorithms for automated detection of cervical pre-cancers with a low-cost, point-of-care, pocket colposcope.”](https://ieeexplore.ieee.org/iel7/10/4359967/08580569.pdf) 2018. IEEE Transactions on Biomedical Engineering.

> M. N. Asiedu, A. K. Simhal, C. T. Lam, J. Mueller, U. Chaudhary, J. W. Schmitt, G. Sapiro, and N. Ramanujam. [“Image processing and machine learning techniques to automate diagnosis of lugol’s iodine cervigrams for a low-cost point-of-care digital colposcope.”](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/10485/2282792/Image-processing-and-machine-learning-techniques-to-automate-diagnosis-of/10.1117/12.2282792.short) 2018. Optics and Biophotonics in Low-Resource Settings IV. Volume 10485. International Society for Optics and Photonics.

&nbsp;


Published software tools 
======
- [Ollivier-Ricci curvature genomic analysis toolbox (Python)](https://pypi.org/project/orcomics)
- [Ollivier-Ricci curvature for brain connectivity analysis (MATLAB)](https://github.com/aksimhal/Curvature-ASD-Analysis)
- [Probabilistic synapse detection (MATLAB)](https://github.com/aksimhal/synapse-detection-examples)
- [Probabilistic synapse detection (Python)](https://github.com/aksimhal/synapse-detection-examples)
- [Synaptic antibody characterization tool (Python)](https://aksimhal.github.io/SynapseAnalysis/)

&nbsp;

Posters
======
PDF downloads of posters presented at various conferences including the International Myeloma Society, American Society for Hematology, American Association for Cancer Research, and Society for Neuroscience can be found [here](https://github.com/aksimhal/posters). A full list of conference presentations is listed in the CV. 
