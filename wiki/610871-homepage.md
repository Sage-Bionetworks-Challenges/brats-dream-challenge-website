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

{column}
 {column width=5}

#### There are ${teammembercount?teamId=3427584} [registered participants](https://www.synapse.org/#!Team:3427584). <br>**Join them now!**

 {column}
 {column width=1}
 {column}
{row}

---

# Overview

Glioblastoma, and diffuse astrocytic glioma with molecular features of glioblastoma (WHO Grade 4 astrocytoma), are the most common and aggressive malignant primary tumor of the central nervous system in adults, with extreme intrinsic heterogeneity in appearance, shape, and histology. Glioblastoma patients have very poor prognosis, and the current standard of care treatment comprises surgery, followed by radiotherapy and chemotherapy. The International Brain Tumor Segmentation (BraTS) Challenges —which have been running since 2012— assess state-of-the-art machine learning (ML) methods used for brain tumor image analysis in mpMRI scans. 

## RSNA-ASNR-MICCAI BraTS Challenge 2021

{row}
 {column width=8}

The **Brain Tumor Segmentation (BraTS) Challenge** celebrates its 10th anniversary, and this year is jointly organized by the [**Radiological Society of North America (RSNA)**](https://www.rsna.org/), the [**American Society of Neuroradiology (ASNR)**](https://www.asnr.org/), and the [**Medical Image Computing and Computer Assisted Interventions (MICCAI) society**](http://www.miccai.org/).

The **RSNA-ASNR-MICCAI BraTS 2021 challenge** utilizes multi-institutional multi-parametric magnetic resonance imaging (mpMRI) scans, and focuses on (**Task 1**) the evaluation of state-of-the-art methods for the segmentation of intrinsically heterogeneous brain glioblastoma sub-regions in mpMRI scans. Furthermore, this year's challenge also focuses on (**Task 2**) the evaluation of classification methods to predict the MGMT promoter methylation status at pre-operative baseline scans. Participants are free to choose whether they want to focus only on one or both tasks.

**NOTE:** **Task 2** is being hosted by Kaggle. Participants interested in submitting to this task should visit [**this page**](https://www.kaggle.com/c/rsna-miccai-brain-tumor-radiogenomic-classification/overview).

{column}
 {column width=4} 
<font size = 3> **Getting started** </font>

- Learn more about the [**Question**](#!Synapse:syn25829070/wiki/610872)
- Learn more about the [**Data**](#!Synapse:syn25829070/wiki/610873)

{row}

---

### Challenge Question (Task 1 - Segmentation)

{row}
 {column width=8}

**Task 1** of the BraTS Challenge is as follows:

>  ### Brain Tumor Segmentation in mpMRI Scans
> 
> The participants are called to address this task by using the provided clinically-acquired training data to develop their method and produce segmentation labels of the different glioma sub-regions.
> 
> The participants are called to upload their method in a containerized way for evaluation (See Submission Tutorial (Docker)).


{column}
 {column width=4}
Learn more about the [**Challenge Question**](#!Synapse:syn25829070/wiki/610872)
{row}

---

### Challenge Data

{row}
 {column width=8}

The RSNA-ASNR-MICCAI BraTS 2021 Challenge makes publicly available the largest and most diverse retrospective cohort of glioma patients. Ample manually-annotated multi-institutional routine clinically-acquired mpMRI scans of glioma are used as the training, validation, and testing data for this year’s BraTS challenge.

Specifically, the datasets used in this year's challenge have been updated, since BraTS'20, with many more routine clinically-acquired mpMRI scans from institutions that have not previously contributed to BraTS, increasing the demographic diversity of the represented patient population. Ground truth annotations of the tumor sub-regions are created and approved by expert neuroradiologists for every subject included in the training, validation, and testing datasets to quantitatively evaluate the predicted tumor segmentations of Task 1.

{column}
 {column width=4} 
Learn more about the [**Challenge Data**](#!Synapse:syn25829070/wiki/610873)
{row}

---

## Timeline

| 1 Jul | (Pre)-Registration opens for Task 1. |
| 7 Jul | Training phase start (Release of training data + associated ground truth). |
| 2 Aug | Validation phase starts (Release of validation data. Hidden ground truth). |
| 22 Aug | Validation phases ends, submission queue closes. |
| 23 Aug at 10am EST | Final submission of short papers, reporting method & preliminary results. Participants must submit short paper to continue in Challenge.|
| 29 Aug | Contacting methods top-ranked in validation phase, to prepare slides for oral presentation at MICCAI. |
| 1 Sept | Final Docker submission phase opens. |
| 15 Sept | Final Docker submission phase closes. |
| 16 Sept - 15 Oct | Final ranking phase on unseen testing data. |
| 4 Oct | Challenge at MICCAI 2021. Presentations on validation phase results. |
| 15 Oct | Final model submission for Task 2 hosted on [**Kaggle**](https://www.kaggle.com/c/rsna-miccai-brain-tumor-radiogenomic-classification/overview). | 
| 29 Nov | Challenge conlusion at RSNA 2021. Announcement of top 3 ranked teams & distribution of awards. |
| 12 Dec | Extended Camera-Ready LNCS paper submission deadline. |
| --- | --- |
| | **(All deadlines are for 23:59 Eastern Time unless otherwise mentioned)** |

---

## How to Participate

Learn more about [**How to Participate**](#!Synapse:syn25829070/wiki/610874) to start competing.

---

## Data Contributors

- Christos Davatzikos, Ph.D. & Spyridon Bakas, Ph.D.,    Center ofr Biomedical Image Computing and Analytics, University of Pennsylvania, Philadelphia, PA, USA
- John Mongan, M.D., Ph.D. & Evan Calabrese, M.D., Ph.D. & Jeffrey D. Rudie, M.D., Ph.D. & Christopher Hess, M.D., Ph.D. & Soonmee Cha, M.D. & Javier Villanueva-Meyer, M.D.,    University of California San Francisco, CA, USA
- John B. Freymann & Justin S. Kirby - on behalf of The Cancer Imaging Archive (TCIA),    Cancer Imaging Program, NCI, National Institutes of Health (NIH), USA
- Benedikt Wiestler, M.D., & Bjoern Menze, Ph.D.,   Technical University of Munich, Germany
- Bjoern Menze, Ph.D.,    University of Zurich, Switzerland 
- Errol Colak, M.D., Priscila Crivellaro,    University of Toronto, Toronto, ON, Canada 
- Rivka R. Colen, M.D., & Aikaterini Kotrotsou, Ph.D.,    MD Anderson Cancer Center, TX, USA
- Daniel Marcus, Ph.D., & Mikhail Milchenko, Ph.D., & Arash Nazeri, M.D.,    Washington University School of Medicine in St. Louis, MO, USA
- Hassan Fathallah-Shaykh, M.D., Ph.D.,    University of Alabama at Birmingham, AL, USA
- Roland Wiest, M.D.,    University of Bern, Switzerland
- Andras Jakab, M.D., Ph.D.,    University of Debrecen, Hungary
- Marc-Andre Weber, M.D.,    Heidelberg University, Germany
- Abhishek Mahajan, M.D., & Ujjwal Baid, Ph.D.,    Tata Memorial Centre, Mumbai, India, & SGGS Institute of Engineering and Technology, Nanded, India

---

## Annotation Volunteers

(in order of decreasing data contributions)

- Evan Calabrese,  MD, PHD, Department of Radiology & Biomedical Imaging, University of California San Francisco, CA, USA
- Ahmed W. Moawad,  MBBS, Mercy Catholic Medical Center, Darby, PA, USA
- Jeffrey Rudie,  MD, PHD, Department of Radiology & Biomedical Imaging, University of California San Francisco, CA, USA
- Luiz Otavio Coelho,  MD, Diagnóstico Avançado por Imagem, Curitiba, Brazil and  Hospital Erasto Gaertner, Curitiba, Brazil
- Olivia McDonnell, Department of Medical Imaging, Gold Coast University Hospital, Southport, Australia
- Elka Miller,  MD, Department of Radiology, University of Ottawa, Ottawa, Canada
- Fanny E. Morón,  MD, Department of Radiology, Baylor College of Medicine, Houston, Tex, USA
- Mark C. Oswood,  MD, PHD, Department of Radiology, Hennepin Healthcare, Minneapolis, MN, USA 
- Robert Y. Shih,  MD, Uniformed Services University, Bethesda, MD, USA
- Loizos Siakallis,  MD, Institute of Neurology, University College London, London, United Kingdom
- Yulia Bronstein,  MD, Virtual Radiologic Professionals, LLC - Branson, Eden Prairie, MN, USA
- James R. Mason,  DO, MPH, University of Pittsburgh Medical Center, Pittsburg, PA, USA
- Anthony F. Miller,  MD, Hahnemann University Hospital Drexel University College of Medicine, PA, USA
- Gagandeep Choudhary,  MD, MBMS, Department of Radiology, Oregon Health & Science University, Portland, OR, USA
- Aanchal Agarwal,  MBBS, Dr Jones and Partners Medical Imaging, South Australia
- Cristina H. Besada ,  MD, PHD, Department of Neuroradiology. Hospital Italiano de Buenos Aires, Buenos Aires, Argentina
- Jamal J. Derakhshan,  MD, PHD, Mallinckrodt Institute of Radiology, Washington University in St. Louis, MO, USA
- Mariana Cardoso Diogo,  MD, Neuroradiology Department, Hospital Garcia de Orta EPE, Almada, Portugal
- Daniel D. Do-Dai,  MD, Department of Radiology, Tufts MedicalCenter, Boston, MA, USA.
- Luciano Farage,  MD, Centro Universitario Euro-Americana (UNIEURO), Brasília, DF, Brazil
- John L. Go,  MD, Department of Radiology, Division of Neuroradiology, University of Southern California, Keck School of Medicine, Los Angeles, CA, USA.
- Mohiuddin Hadi,  MD, Radiology (Neuroradiology Section), University of Louisville, Louisville, KY, USA
- Virginia B. Hill,  MD, Northwestern University Feinberg School of Medicine, Chicago, IL, USA
- Michael Iv,  MD, Stanford Hospital and Clinics, Stanford University, Stanford, CA, USA
- David Joyner,  MD, Department of Radiology and Medical Imaging University of Virginia Health System Charlottesville, VA, USA
- Christie Lincoln,  MD, Department of Radiology, Baylor College of Medicine, Houston, Tex, USA
- Eyal Lotan,  MD, PHD, NYU Langone Medical Center, New York, NY, USA
- Asako Miyakoshi,  MD, Kaiser Permanente, San Diego, CA, USA
- Mariana Sanchez-Montaño,  MD, Instituto Nacional de Ciencias Medicas y Nutricion, Maxico City, Maxico
- Jaya Nath,  MD, Northport VA Medical Center Northport, NY, USA
- Xuan V. Nguyen,  MD, PHD, Ohio State University Wexner Medical Center, Columbus, OH, USA
- Manal Nicolas-Jilwan,  MD, University of Virginia Medical Center, Charlottesville, VA, USA
- Johanna Ortiz Jimenez,  MD, Neuroradiology- Department of Radiology Kingston General Hospital - Queen's University, Kingston, Canada
- Kerem Ozturk,  MD, Department of Radiology, University of Minnesota Health,Minneapolis, MN, USA
- Bojan D. Petrovic,  MD, NorthShore University HealthSystem, Chicago, IL, USA
- Lubdha M. Shah,  MD, University of Utah Health Sciences Center, Salt Lake City, UT, USA
- Chintan Shah,  MD, MS, Neuroradiology and Imaging Informatics Imaging Institute, Cleveland Clinic, Cleveland, OH, USA
- Manas Sharma,  MD, MBMS, London Health Sciences Centre, London, Ontario, Canada
- Onur Simsek,  MD, Dr Abdurrahman Yurtaslan Ankara Oncology Training and Research Hospital, University of Health Sciences, Ankara, Turkey
- Achint K. Singh,  MD, University of Texas Health San Antonio, TX, USA
- Salil Soman,  MD, MS, Department of Radiology, Beth Israel Deaconess Medical Center, Harvard Medical School, Boston, MA, USA
- Volodymyr Statsevych,  MD, Neuroradiology and Imaging Informatics Imaging Institute, Cleveland Clinic, Cleveland, OH, USA
- Brent D. Weinberg,  MD, PHD, Emory University, Atlanta, GA, USA
- Robert J. Young,  MD, Memorial Sloan Kettering Cancer Center, New York, NY, USA
- Ichiro Ikuta,  MD, MMSc, Yale University School of Medicine, Department of Radiology & Biomedical Imaging, New Haven, CT, USA
- Amit K. Agarwal,  MD, MBMS, Mayo Clinic, Jacksonville, FL, USA
- Sword Christian Cambron,  MD, Dartmouth Hitchcock Medical Center, NH, USA
- Richard Silbergleit,  MD, Oakland University William Beaumont School of Medicine, Rochester, MI, USA. 
- Alexandru Dusoi, Radiology Department at Klinikum Hochrhein Waldshut-Tiengen, Germany
- Alida A. Postma,  MD, PHD, Maastricht University Hospital, Maastricht, The Netherlands
- Laurent Letourneau-Guillon ,  MSc, Radiology department, Centre Hospitalier de l'Universite de Montreal (CHUM) and Centre de Recherche du CHUM (CRCHUM) Montreal, Quebec, Canada
- Gloria J. Guzmán Pérez-Carrillo,  MD, MSc, Mallinckrodt Institute of Radiology, School of Medicine, Washington University, St. Louis, MO, USA
- Atin Saha,  MD, Department of Radiology, NewYork-Presbyterian Hospital, Weill Cornell Medical College, New York, NY, USA
- Neetu Soni,  MD, MBMS, University of Iowa Hospitals and Clinics, Iowa City, IA, USA
- Greg Zaharchuk,  MD, PHD, Department of Radiology Stanford University, Stanford, CA, USA
- Vahe M. Zohrabian,  MD, Department of Radiology, Northwell Health, Zucker Hofstra School of Medicine at Northwell, North Shore University Hospital, Hempstead, New York, NY, USA.
- Yingming Chen,  MD, Department of Medical Imaging, University of Toronto, ON, Canada
- Milos M. Cekic,  MD, University of California Los Angeles, CA, USA
- Akm Rahman,  DO, University of Rochester Medical Center,Rochester, NY, USA
- Juan E. Small,  MD, Lahey Clinic, Burlington, MA, USA
- Varun Sethi,  MD, Temple University Hospital, Philadelphia, PA, USA

---

## Challenge Organizing Committee

| Name |  Institution | Role |
| --- | --- |--- |
| Spyridon Bakas | University of Pennsylvania | Lead & Co-Director |
| Keyvan Farahani | National Cancer Institute | Co-Director |
| Ujjwal Baid | University of Pennsylvania | Co-Organizer |
| Evan Calabrese | University of California San Francisco | Co-Organizer |
| Errol Colak | University of Toronto | Co-Organizer |
| Timothy Bergquist | Sage Bionetworks | Evaluation Co-Lead |
| Michel Bilello | University of Pennsylvania | Clinical Evaluator & Annotation Approver |
| Satyam Ghodasara | University of Pennsylvania | Clinical Evaluator & Approver Coordinator |
| Thomas Schaffter | Sage Bionetworks | Challenge Evaluation Co-Lead |
| Thomas Yu | Sage Bionetworks | Challenge Evaluation Infrastructure |
| Verena Chung | Sage Bionetworks | Challenge Evaluation Infrastructure |
| James Eddy | Sage Bionetworks | Challenge Evaluation Co-Director |
| Jiaxin Zheng | Sage Bionetworks | Challenge Evaluation Project Manager | 
| Rong Chai | Sage Bionetworks | Challenge Evaluation Infrastructure | 
| Adam Flanders | Thomas Jefferson University Hospital | Co-Organizer |
| Felipe C. Kitamura |	Diagnósticos da América SA (DASA) | Co-Organizer|
| Bjoern Menze | University of Zurich | Co-Organizer |
| Suyash Mohan | University of Pennsylvania | Clinical Evaluator & Annotation Approver |
| Luciano M. Prevedello |	The Ohio State University Wexner Medical Center | Co-Organizer |
| Jeffrey D. Rudie | University of California San Francisco | Co-Organizer |
| Russell T. Shinohara | University of Pennsylvania | Co-Organizer |
---
