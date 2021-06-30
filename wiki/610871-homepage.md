<!-- markdownlint-disable no-inline-html -->
<!-- markdownlint-disable header-start-left -->

<!-- markdownlint-disable-next-line first-line-h1 -->
${image?fileName=BRATS%5Fbanner%5FnoCaption%2Epng&align=Center&scale=100&responsive=true&altText=BraTS Challenge banner}

---

{row}
 {column width=2}
 {column}
 {column width=4}

#### ${jointeam?teamId=3427584&isChallenge=true&isMemberMessage=You have successfully registered for the Challenge%2E&text=Click Here to Register&isSimpleRequestButton=true&requestOpenText=Your registration is in progress%2E&successMessage=Your registration is in progress%2E}
#### There are ${teammembercount?teamId=3427584} [registered participants](https://www.synapse.org/#!Team:3427584). <br>**Join them now!**
{column}
 {column width=4}
${buttonlink?text=Access the Training Data&url=https://forms%2Egle/j7KLDKfA6qTup4mg8&align=Center}

{column}
 {column width=2}
 {column}
{row}

---

# Overview

Glioblastoma, and diffuse astrocytic glioma with molecular features of glioblastoma (WHO Grade 4 astrocytoma), are the most common and aggressive malignant primary tumor of the central nervous system in adults, with extreme intrinsic heterogeneity in appearance, shape, and histology. Glioblastoma patients have very poor prognosis, and the current standard of care comprises surgical resection followed by radiotherapy and chemotherapy. MGMT (O[6]-methylguanine-DNA methyltransferase) is a DNA repair enzyme that the methylation of its promoter in newly diagnosed glioblastoma has been identified as a favorable prognostic factor and a predictor of chemotherapy response. Thus determination of MGMT promoter methylation status in newly diagnosed glioblastoma can influence treatment decision making. The International Brain Tumor Segmentation (BraTS) Challenges—which have been run since 2012—assess state-of-the-art machine learning (ML) methods used for brain tumor image analysis in mpMRI scans. 

## BraTS DREAM Challenge

{row}
 {column width=8}

The **Brain Tumor Segmentation (BraTS) Challenge** celebrates its 10th anniversary, and this year is jointly organized by the [**Radiological Society of North America (RSNA)**](https://www.rsna.org/), the [**American Society of Neuroradiology (ASNR)**](https://www.asnr.org/), and the [**Medical Image Computing and Computer Assisted Interventions (MICCAI) society**](http://www.miccai.org/).

The RSNA/ASNR/MICCAI BraTS 2021 challenge utilizes multi-institutional multi-parametric magnetic resonance imaging (mpMRI) scans, and focuses on (**Task 1**) the evaluation of state-of-the-art methods for the segmentation of intrinsically heterogeneous brain glioblastoma sub-regions in mpMRI scans. Furthermore, to pinpoint the clinical relevance of this segmentation task, BraTS’21 also focuses on (**Task 2**) the evaluation of methods to predict the MGMT promoter methylation status at the pre-operative baseline scans, via integrative analyses of quantitative imaging phenomic features and machine learning algorithms.

> **NOTE:** **Task 2** of the BraTS Challenge will be hosted by Kaggle. Participants interested in submitting to this task should visit **this page**(add link here).

{column}
 {column width=4} 
<font size = 3> **Getting started** </font>

- Learn more about the [**Question**](#!Synapse:syn25829070/wiki/610872)
- Learn more about the [**Data**](#!Synapse:syn25829070/wiki/610873)

{row}

---

### Challenge Question

{row}
 {column width=8}

**Task 1** of the BraTS Challenge is as follows:

>  ### Brain Tumor Segmentation in mpMRI Scans
> 
> The participants are called to address this task by using the provided clinically-acquired training data to develop their method and produce segmentation labels of the different glioma sub-regions.

{column}
 {column width=4}
Learn more about the [**Question**](#!Synapse:syn25829070/wiki/610872)
{row}

---

### Challenge Data

{row}
 {column width=8}

Ample multi-institutional routine clinically-acquired multi-parametric MRI (mpMRI) scans of glioblastoma (GBM), with pathologically confirmed diagnosis and available MGMT promoter methylation status, are used as the training, validation, and testing data for this year’s BraTS challenge.

Specifically, the datasets used in this year's challenge have been updated, since BraTS'20, with many more routine clinically-acquired mpMRI scans. Ground truth annotations of the tumor sub-regions are created and approved by expert neuroradiologists for every subject included in the training, validation, and testing datasets to quantitatively evaluate the predicted tumor segmentations of Task 1, whereas the quantitative evaluation of Task 2 is performed according to clinical data.

{column}
 {column width=4} 
Learn more about the [**Data**](#!Synapse:syn25829070/wiki/610873)
{row}

---

## Timeline

| | **(All deadlines are for 23:59 Eastern Time)** |
| --- | --- |
| 15 Jun | Training phase (Release of training data + associated ground truth). |
| 15 Jul | Validation phase (Release of validation data. Hidden ground truth). |
| 13 Aug | Submission of short papers, reporting method & preliminary results. |
| 27 Aug | Contacting methods top-ranked in validation phase, to prepare slides for oral presentation at MICCAI. |
| 20-30 Oct | Final ranking phase on unseen testing data (Evaluation only for methods with submitted papers). |
| 4 Oct | Challenge at MICCAI. |
| 29 Nov | Announcement of top 3 ranked teams at RSNA 2021. |
| 12 Dec | Extended Camera-Ready LNCS paper submission deadline. |

---

## How to Participate

Learn more about [**How to Participate**](#!Synapse:syn25829070/wiki/610874) to start competing.

---

## Data Contributors

- John B. Freymann & Justin S. Kirby - on behalf of The Cancer Imaging Archive (TCIA),    Cancer Imaging Program, NCI, National Institutes of Health (NIH), USA
- John Mongan, M.D., Ph.D. & Evan Calabrese, M.D., Ph.D. & Jeff Rudie, M.D., Ph.D.,    University of California San Francisco, CA, USA
- Christos Davatzikos, Ph.D.,    CBICA, UPenn, Philadelphia, PA, USA
- Rivka R. Colen, M.D., & Aikaterini Kotrotsou, Ph.D.,    MD Anderson Cancer Center, TX, USA
- Daniel Marcus, Ph.D., & Mikhail Milchenko, Ph.D., & Arash Nazeri, M.D.,    Washington University School of Medicine in St. Louis, MO, USA
- Hassan Fathallah-Shaykh, M.D., Ph.D.,    University of Alabama at Birmingham, AL, USA
- Roland Wiest, M.D.,    University of Bern, Switzerland
- Andras Jakab, M.D., Ph.D.,    University of Debrecen, Hungary
- Marc-Andre Weber, M.D.,    Heidelberg University, Germany
- Abhishek Mahajan, M.D., & Ujjwal Baid, Ph.D.,    Tata Memorial Centre, Mumbai, India, & SGGS Institute of Engineering and Technology, Nanded, India

---

## Challenge Organizers

| Name |  Institution | Role |
| --- | --- |--- |
| Spyros Bakos | University of Pennsylvania | Challenge Lead & Co-Director |
| Tim Bergquist | Sage Bionetworks | Challenge Lead |
| Thomas Schaffter | Sage Bionetworks | Challenge Lead |
| Thomas Yu | Sage Bionetworks | Challenge Infrastructure |
| James Eddy | Sage Bionetworks | Co-Director |
| Keyvan Farahani | NIH/NCI | Co-Director |
---
