<!-- markdownlint-disable-next-line first-line-h1 -->
${toc}

## **Access the Training Data**

Complete the follow steps to gain access to the training data.
You can find the description and conditions for use for the training data below.

1. **Register for the challenge.** You must be registered before completing the next steps.
    ${jointeam?teamId=3427584&isChallenge=true&isMemberMessage=You have successfully registered for the Challenge%2E&text=Click Here to Register&isSimpleRequestButton=true&requestOpenText=Your registration is in progress%2E&successMessage=Your registration is in progress%2E}
2. **Complete the data access request form.** You will receive a confirmation email when you are given access to the training data.
    <!-- markdownlint-disable-next-line no-bare-urls -->
    ${buttonlink?text=Request Data Access&url=https://forms.gle/RuNkiqKDCKbvUmR37}
3. **Download the Training Data.**
    ${buttonlink?text=Access the Data&url=#!Synapse:syn25953134}

## **Download the Validation Data**

If you have completed the steps above, you should have access to the Validation Data.
${buttonlink?text=Download Validation Data&url=#!Synapse:syn26017015}

---

## **Description**

Ample multi-institutional routine clinically-acquired multi-parametric MRI (mpMRI) scans of glioma, with pathologically confirmed diagnosis and available MGMT promoter methylation status, are used as the training, validation, and testing data for this year’s BraTS challenge.

Specifically, for Task 1 the datasets used in this year's challenge have been updated, since BraTS'20, with many more routine clinically-acquired mpMRI scans. Ground truth annotations of the tumor sub-regions are created and approved by expert neuroradiologists for every subject included in the training, validation, and testing datasets to quantitatively evaluate the predicted tumor segmentations.

### Imaging Data Description

All BraTS mpMRI scans are available as NIfTI files (.nii.gz) and describe a) native (T1) and b) post-contrast T1-weighted (T1Gd), c) T2-weighted (T2), and d) T2 Fluid Attenuated Inversion Recovery (T2-FLAIR) volumes, and were acquired with different clinical protocols and various scanners from multiple data contributing institutions. We intend to release the associated de-identifed DICOM (.dcm) files after the conclusion of the challenge.

All the imaging datasets have been annotated manually, by one to four raters, following the same annotation protocol, and their annotations were approved by experienced neuro-radiologists. Annotations comprise the GD-enhancing tumor (ET — label 4), the peritumoral edematous/invaded tissue (ED — label 2), and the necrotic tumor core (NCR — label 1), as described both in the BraTS 2012-2013 TMI paper and in the latest BraTS summarizing paper. The ground truth data were created after their pre-processing, i.e., co-registered to the same anatomical template, interpolated to the same resolution (1 mm<sup>3</sup>) and skull-stripped.


### Comparison with Previous BraTS datasets

This year we provide the naming convention and name mapping between the data of BraTS'21-'17, and the subjects used from the data collections of TCGA-GBM, TCGA-LGG, IvyGAP, and CPTAC-GBM, available through The Cancer Imaging Archive (TCIA) to further facilitate research beyond the directly BraTS related tasks.

---

## Conditions for Use

- Challenge participants must abide by the guiding principles for responsible research use and data handling within the Synapse Commons Platform as described in the [Synapse Governance documents](https://help.synapse.org/docs/Governance-Overview.2009597114.html#GovernanceOverview-SynapseTermsandConditionsofUse) and by the [Challenges Official Rules](#!Synapse:syn25829067/wiki/610867).

- **Publication embargo**: Use of Challenge results in a publication by Challenge participants is permitted if it is restricted to the results of your Challenge method and your Team ranking. Additionally, you agree not to report overall Challenge results or any analysis of the overall results until the organizers and Challenge participants have jointly published (or pre-published) an overview paper on the results from the RSNA-ASNR-MICCAI Brain Tumor Segmentation (BraTS) Challenge and the best performing strategies used in the Challenge. You will be contacted through your Synapse-affiliated email address when this condition has been met. This information will also be posted within this Synapse project.

- **Acknowledgement**: Challenge participants are permitted to use, publish and present the Challenge results, after the embargo period, provided they acknowledge the BraTS challenge organizing members as follows: "Data used in this publication were obtained as part of the RSNA-ASNR-MICCAI Brain Tumor Segmentation (BraTS) Challenge project through Synapse ID (syn25829067)." 

- **Use of Data Beyond BraTS**: Participants are NOT allowed to use additional public and/or private data (from their own institutions) for extending the provided BraTS data, for the training of the algorithm chosen to be ranked. Similarly, using models that were pretrained on such datasets is NOT allowed. This is due to our intentions to provide a fair comparison among the participating methods. However, participants are allowed to use additional public and/or private data (from their own institutions), only if for scientific publication purposes and they explicitly mention this in their submitted manuscripts and also report results using only the BraTS'21 data to discuss potential result differences.

- **Data Usage Agreement / Citations**

    You are free to use and/or refer to the BraTS datasets in your own research, provided that you always cite the flagship manuscript (published or pre-published) resulting from the challenge as well as the following three manuscripts:

    [1] U.Baid, et al., The RSNA-ASNR-MICCAI BraTS 2021 Benchmark on Brain Tumor Segmentation and Radiogenomic Classification, arXiv:2107.02314, 2021.

    [2] B. H. Menze, A. Jakab, S. Bauer, J. Kalpathy-Cramer, K. Farahani, J. Kirby, et al. "The Multimodal Brain Tumor Image Segmentation Benchmark (BRATS)", IEEE Transactions on Medical Imaging 34(10), 1993-2024 (2015) DOI: 10.1109/TMI.2014.2377694 
    
    [3] S. Bakas, H. Akbari, A. Sotiras, M. Bilello, M. Rozycki, J.S. Kirby, et al., "Advancing The Cancer Genome Atlas glioma MRI collections with expert segmentation labels and radiomic features", Nature Scientific Data, 4:170117 (2017) DOI: 10.1038/sdata.2017.117 

    In addition, if there are no restrictions imposed from the journal/conference you submit your paper about citing "Data Citations", please be specific and also cite the following:

    [4] S. Bakas, H. Akbari, A. Sotiras, M. Bilello, M. Rozycki, J. Kirby, et al., "Segmentation Labels and Radiomic Features for the Pre-operative Scans of the TCGA-GBM collection", The Cancer Imaging Archive, 2017. DOI: 10.7937/K9/TCIA.2017.KLXWJJ1Q

    [5] S. Bakas, H. Akbari, A. Sotiras, M. Bilello, M. Rozycki, J. Kirby, et al., "Segmentation Labels and Radiomic Features for the Pre-operative Scans of the TCGA-LGG collection", The Cancer Imaging Archive, 2017. DOI: 10.7937/K9/TCIA.2017.GJQ7R0EF

- **Note**: Challenge participants agree to cite the initial challenge pre publication manuscript (or the final publication manuscript). You will be contacted through your Synapse affiliated email when the manuscript has been released for citation.

- **Note**: Use of the BraTS datasets for creating and submitting benchmark results for publication on MLPerf.org is considered non-commercial use. It is further acceptable to republish results published on MLPerf.org, as well as to create unverified benchmark results consistent with the MLPerf.org rules in other locations. Please note that you should always adhere to the BraTS data usage guidelines and cite appropriately the aforementioned publications, as well as to the terms of use required by MLPerf.org.
