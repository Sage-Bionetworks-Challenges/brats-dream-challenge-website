<!-- markdownlint-disable-next-line first-line-h1 -->
${toc}

## **Description**

Ample multi-institutional routine clinically-acquired multi-parametric MRI (mpMRI) scans of glioma, with pathologically confirmed diagnosis and available MGMT promoter methylation status, are used as the training, validation, and testing data for this year’s BraTS challenge.

Specifically, for Task 1 the datasets used in this year's challenge have been updated, since BraTS'20, with many more routine clinically-acquired mpMRI scans. Ground truth annotations of the tumor sub-regions are created and approved by expert neuroradiologists for every subject included in the training, validation, and testing datasets to quantitatively evaluate the predicted tumor segmentations.

### Imaging Data Description

All BraTS mpMRI scans are available as NIfTI files (.nii.gz) and describe a) native (T1) and b) post-contrast T1-weighted (T1Gd), c) T2-weighted (T2), and d) T2 Fluid Attenuated Inversion Recovery (T2-FLAIR) volumes, and were acquired with different clinical protocols and various scanners from multiple data contributing institutions. We intend to release the associated de-identifed DICOM (.dcm) files after the conclusion of the challenge.

All the imaging datasets have been annotated manually, by one to four raters, following the same annotation protocol, and their annotations were approved by experienced neuro-radiologists. Annotations comprise the GD-enhancing tumor (ET — label 4), the peritumoral edematous/invaded tissue (ED — label 2), and the necrotic tumor core (NCR — label 1), as described both in the BraTS 2012-2013 TMI paper and in the latest BraTS summarizing paper. The ground truth data were created after their pre-processing, i.e., co-registered to the same anatomical template, interpolated to the same resolution (1 mm<sup>3</sup>) and skull-stripped.

<!--Needs to confirm software version before adding links and making this part live
### Code Availability

In favor of transparency and reproducibility, we make available the implementations we used for generating the pre-processed data, as well as for evaluating the performance of the participants through the following packages:

The Cancer Imaging Phenomics Toolkit (CaPTk)
The Federated Tumor Segmentation (FeTS) platform
-->
### Comparison with Previous BraTS datasets

This year we provide the naming convention and name mapping between the data of BraTS'21-'17, and the subjects used from the data collections of TCGA-GBM, TCGA-LGG, IvyGAP, and CPTAC-GBM, available through The Cancer Imaging Archive (TCIA) to further facilitate research beyond the directly BraTS related tasks.

---

## **Conditions for Use**

> THESE ARE JUST DRAFT CONDITIONS AND ARE NOT FINAL

- Challenge participants must abide by the guiding principles for responsible research use and data handling within the Synapse Commons Platform as described in the Synapse Governance documents and by the Challenges Official Rules. 

- **Publication embargo**
- Use of Challenge results in a publication by Challenge participants is permitted if it is restricted to the results of your Challenge method and your Team ranking. Participants agree to share the manuscript with the Challenge organizers who will review it within 2 weeks and verify that it does not report overall challenge results or any analysis of the overall results as these are parts of the main Challenge Publication. Additionally, you agree not to report overall Challenge results or any analysis of the overall results. These conditions apply until the organizers publish an overview manuscript on the results from the RSNA-ASNR-MICCAI Brain Tumor Segmentation (BraTS) Challenge and the best performing strategies used in the Challenge. The Challenge participants will be co-authoring this overview manuscript. You will be contacted through your Synapse-affiliated email address when this condition has been met. This information will also be posted within this Synapse project. 
- Acknowledgement: Challenge participants are permitted to use, publish, and present the Challenge results, after the embargo period, provided they adhere to the "Data usage Agreement and add the following acknowledgement: "Data used in this publication were obtained as part of the RSNA-ASNR-MICCAI Brain Tumor Segmentation (BraTS) Challenge project through Synapse ID (syn25829067)."

- **Use of Data Beyond BraTS**
Participants are NOT allowed to use additional public and/or private data (from their own institutions) for extending the provided BraTS data, for the training of the algorithm chosen to be ranked. Similarly, using models that were pretrained on such datasets is NOT allowed. This is due to our intentions to provide a fair comparison among the participating methods.
However, participants are allowed to use additional public and/or private data (from their own institutions), only if for scientific publication purposes and they explicitly mention this in their submitted manuscripts and also report results using only the BraTS'21 data to discuss potential result differences.


- **Data Usage Agreement / Citations**

    You are free to use and/or refer to the BraTS datasets in your own research, provided that you always cite the following three manuscripts: 

    [1] "The RSNA-ASNR-MICCAI Brain Tumor Segmentation (BraTS) challenge", arXiv preprint, 2021 <!--to be updated-->
    
    [2] B. H. Menze, A. Jakab, S. Bauer, J. Kalpathy-Cramer, K. Farahani, J. Kirby, et al. "The Multimodal Brain Tumor Image Segmentation Benchmark (BRATS)", IEEE Transactions on Medical Imaging 34(10), 1993-2024 (2015) DOI: 10.1109/TMI.2014.2377694
    
    [3] S. Bakas, H. Akbari, A. Sotiras, M. Bilello, M. Rozycki, J.S. Kirby, et al., "Advancing The Cancer Genome Atlas glioma MRI collections with expert segmentation labels and radiomic features", Nature Scientific Data, 4:170117 (2017) DOI: 10.1038/sdata.2017.117 

    In addition, if there are no restrictions imposed from the journal/conference you submit your paper about citing "Data Citations", please be specific and also cite the following:

    [4] S. Bakas, H. Akbari, A. Sotiras, M. Bilello, M. Rozycki, J. Kirby, et al., "Segmentation Labels and Radiomic Features for the Pre-operative Scans of the TCGA-GBM collection", The Cancer Imaging Archive, 2017. DOI: 10.7937/K9/TCIA.2017.KLXWJJ1Q 

    [5] S. Bakas, H. Akbari, A. Sotiras, M. Bilello, M. Rozycki, J. Kirby, et al., "Segmentation Labels and Radiomic Features for the Pre-operative Scans of the TCGA-LGG collection", The Cancer Imaging Archive, 2017. DOI: 10.7937/K9/TCIA.2017.GJQ7R0EF 

- Note: Use of the BraTS datasets for creating and submitting benchmark results for publication on MLPerf.org is considered non-commercial use. It is further acceptable to republish results published on MLPerf.org, as well as to create unverified benchmark results consistent with the MLPerf.org rules in other locations. Please note that you should always adhere to the BraTS data usage guidelines and cite appropriately the aforementioned publications, as well as to the terms of use required by MLPerf.org. 

---

## **Access**

You must be registered to the challenge to access the data. Learn [**How to Participate**](#!Synapse:syn25829070/wiki/610874)
