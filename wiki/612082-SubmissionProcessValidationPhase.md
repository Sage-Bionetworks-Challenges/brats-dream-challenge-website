<!-- markdownlint-disable no-emphasis-as-header -->

<!-- markdownlint-disable-next-line first-line-h1 -->
This page will assist you in submitting a Docker container to a challenge queue.
${toc}

---

## **1. Create a Synapse Project**

- Name your project `BraTS DREAM Challenge <Your team name>`
- You should use this project for your prediction files and your source code in the **Files** tab.  
->${video?mp4SynapseId=syn20685869}<-
->_Creating a project on Synapse_<-

---

Upload your segmentation labels in .nii.gz format. Note that each file should be named using the patient ID, given by the folder name containing the 4 modalities for each patient. In other words, for subjects that you were given files named ID_t1.nii.gz, ID_t2.nii.gz, etc., the uploaded segmentations should be named ID.nii.gz

## **2. Creating your Submission Files**

During the Validation phase (August 2 - August 13), you can submit the predictions from your trained models on the validation data (To Be Released on August 2).

- Be sure to zip each of the NIfTI files, such that the file names end in `*.nii.gz`.
- Filenames should contain the case number for which they are predictions. For example, `ex_###.nii.gz` where `###` is the appropriate case number.
- All of the individual NIfTI files must be contained inside of a zip or tarball archive. When you make your submission, you must submit this zipped archive.



## **3. Upload your Submission Tarball**

Go to your `BraTS DREAM Challenge <Your team name>` project and upload your tarball to the `Files` tab.
${image?fileName=FileUpload%2Epng&align=Right&scale=50&responsive=true&altText=Submitting a Docker image}


## **4. Submit your Predictions**

<!-- ${evalsubmit?projectId=syn25829070&unavailableMessage=Please register to make a submission.&buttonText=Submit to the challenge} -->

${image?fileName=FileSelection%2Epng&align=Right&scale=50&responsive=true&altText=Submitting a Docker image}
To submit your predictions tarball, navigate to the tarball you uploaded on Synapse and click on the **File Tools** button in the upper-right corner.  Select **Submit File to Challenge** from the options, then follow the prompts. Select the `BraTS Challenge - Task 1` challenge.
