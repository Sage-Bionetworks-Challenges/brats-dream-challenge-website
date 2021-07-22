<!-- markdownlint-disable no-missing-space-atx -->
<!-- markdownlint-disable-next-line first-line-h1 -->
${toc}

## **Challenge Task: Tumor Sub-region Segmentation**

The participants are called to address this task by using the provided clinically-acquired training data to develop their method and produce segmentation labels of the different glioma sub-regions. **The sub-regions considered for evaluation are the "enhancing tumor" (ET), the "tumor core" (TC), and the "whole tumor" (WT)** [see figure below]. The ET is described by areas that show hyper-intensity in T1Gd when compared to T1, but also when compared to “healthy” white matter in T1Gd. The TC describes the bulk of the tumor, which is what is typically resected. The TC entails the ET, as well as the necrotic (NCR) parts of the tumor. The appearance of NCR is typically hypo-intense in T1-Gd when compared to T1. The WT describes the complete extent of the disease, as it entails the TC and the peritumoral edematous/invaded tissue (ED), which is typically depicted by hyper-intense signal in FLAIR.

The provided segmentation labels have values of 1 for NCR, 2 for ED, 4 for ET, and 0 for everything else.
The participants are called to upload their method in a containerized way for evaluation (Submission Tutorial).

> **Note**: Task 2 is being hosted on [Kaggle](https://www.kaggle.com/c/rsna-miccai-brain-tumor-radiogenomic-classification/overview). See the [Kaggle](https://www.kaggle.com/c/rsna-miccai-brain-tumor-radiogenomic-classification/overview) page or the [RSNA/ASNR/MICCAI BraTS homepage](https://www.med.upenn.edu/cbica/brats2021/) for details about task 2.

### Challenge Data

> Gain access to the [Training Data](#!Synapse:syn25829070/wiki/610873)

### Submission Format

> See [Submission Tutorial (Docker)](#!Synapse:syn25829070/wiki/611103)

---

## **Assessment**

Consistent with the configuration of previous BraTS challenges, we intend to use the "Dice SImilarity Coefficient", and the "Hausdorff distance (95%)". Expanding upon this evaluation scheme, we will also provide the metrics of "Sensitivity" and "Specificity", allowing to determine potential over- or under-segmentations of the tumor sub-regions by participating methods.

---


## **References**

[1] U.Baid, et al., The RSNA-ASNR-MICCAI BraTS 2021 Benchmark on Brain Tumor Segmentation and Radiogenomic Classification, arXiv:2107.02314, 2021.

[2] B. H. Menze, A. Jakab, S. Bauer, J. Kalpathy-Cramer, K. Farahani, J. Kirby, et al. "The Multimodal Brain Tumor Image Segmentation Benchmark (BRATS)", IEEE Transactions on Medical Imaging 34(10), 1993-2024 (2015) DOI: 10.1109/TMI.2014.2377694 

[3] S. Bakas, H. Akbari, A. Sotiras, M. Bilello, M. Rozycki, J.S. Kirby, et al., "Advancing The Cancer Genome Atlas glioma MRI collections with expert segmentation labels and radiomic features", Nature Scientific Data, 4:170117 (2017) DOI: 10.1038/sdata.2017.117 

[4] S. Bakas, H. Akbari, A. Sotiras, M. Bilello, M. Rozycki, J. Kirby, et al., "Segmentation Labels and Radiomic Features for the Pre-operative Scans of the TCGA-GBM collection", The Cancer Imaging Archive, 2017. DOI: 10.7937/K9/TCIA.2017.KLXWJJ1Q

[5] S. Bakas, H. Akbari, A. Sotiras, M. Bilello, M. Rozycki, J. Kirby, et al., "Segmentation Labels and Radiomic Features for the Pre-operative Scans of the TCGA-LGG collection", The Cancer Imaging Archive, 2017. DOI: 10.7937/K9/TCIA.2017.GJQ7R0EF

For more information on the data, see [**here**](#!Synapse:syn25829070/wiki/611091).
