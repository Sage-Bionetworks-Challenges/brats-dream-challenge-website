<!-- markdownlint-disable no-missing-space-atx -->

<!-- markdownlint-disable-next-line first-line-h1 -->
${toc}

## **Overview**

The participants are called to address this task by using the provided clinically-acquired training data to develop their method and produce segmentation labels of the different glioma sub-regions. The sub-regions considered for evaluation are the "enhancing tumor" (ET), the "tumor core" (TC), and the "whole tumor" (WT) [see figure below]. The ET is described by areas that show hyper-intensity in T1Gd when compared to T1, but also when compared to “healthy” white matter in T1Gd. The TC describes the bulk of the tumor, which is what is typically resected. The TC entails the ET, as well as the necrotic (NCR) parts of the tumor. The appearance of NCR is typically hypo-intense in T1-Gd when compared to T1. The WT describes the complete extent of the disease, as it entails the TC and the peritumoral edematous/invaded tissue (ED), which is typically depicted by hyper-intense signal in FLAIR.

The provided segmentation labels have values of 1 for NCR, 2 for ED, 4 for ET, and 0 for everything else.

The participants are called to upload their method in a containerized way for evaluation (See [Submission Tutorial (Docker)](#!Synapse:syn25829070/wiki/611103)).

---

## **Subchallenges**

### **Subchallenge 1**

The participants are called to address this task by using the provided clinically-acquired training data to develop their method and produce segmentation labels of the different glioma sub-regions. **The sub-regions considered for evaluation are the "enhancing tumor" (ET), the "tumor core" (TC), and the "whole tumor" (WT)** [see figure below]. The ET is described by areas that show hyper-intensity in T1Gd when compared to T1, but also when compared to “healthy” white matter in T1Gd. The TC describes the bulk of the tumor, which is what is typically resected. The TC entails the ET, as well as the necrotic (NCR) parts of the tumor. The appearance of NCR is typically hypo-intense in T1-Gd when compared to T1. The WT describes the complete extent of the disease, as it entails the TC and the peritumoral edematous/invaded tissue (ED), which is typically depicted by hyper-intense signal in FLAIR.

The provided segmentation labels have values of 1 for NCR, 2 for ED, 4 for ET, and 0 for everything else.
The participants are called to upload their method in a containerized way for evaluation (more details will follow soon).

### Submission Format

> TODO

---

## **Assessment**

Consistent with the configuration of previous BraTS challenges, we intend to use the "Dice score", and the "Hausdorff distance (95%)". Expanding upon this evaluation scheme, we will also provide the metrics of "Sensitivity" and "Specificity", allowing to determine potential over- or under-segmentations of the tumor sub-regions by participating methods.

---


## **References**

Information of challenge

For more information on the data, see [**here**](#!Synapse:syn25829070/wiki/611091).
