<!-- markdownlint-disable no-emphasis-as-header -->
<!-- markdownlint-disable no-trailing-punctuation -->

<!-- markdownlint-disable-next-line first-line-h1 -->
This page will assist you in submitting a Docker container to a challenge queue.
${toc}

---

> During the Validation phase (August 2 - August 22), you are only expected to submit your segementation files. Validation submissions are due August 22 at 23:59 Eastern Time. We will **not be accepting** docker containers until September 1 at 23:59 Eastern Time.

> We **cannot** guarantee that your submissions will be scored by the time your short papers are due. Please submit your predictions at least 48 hours before your short papers are due to make sure you can get your scores from your validation phase submissions.

## **1. Create a Synapse Project**

- Name your project `BraTS DREAM Challenge <Your team name>`
- You should use this project for your segmentation files and your source code in the **Files** tab.  
->${video?mp4SynapseId=syn20685869}<-
->_Creating a project on Synapse_<-

---

## **2. Creating your Segmentation Files**

- Zip each of the NIfTI files, such that the file names end in `*.nii.gz`.
- Filenames should be named using the case ID, given by the folder name containing the 4 modalities for each patient. In other words, for subjects that you were given files named ID_t1.nii.gz, ID_t2.nii.gz, etc., the individual segmentations should be named ID.nii.gz
- All of the individual zipped NIfTI files must be contained inside of a single zip or tarball archive. When you make your submission, **you must submit this zipped archive**.

---

## **3. Upload your Submission Tarball**

> In order to upload your tarball, you will need to be a [**Certified User**](https://docs.synapse.org/articles/accounts_certified_users_and_profile_validation.html#certified-users).
>
>${buttonlink?text=Become a Certified User&url=%23%21Quiz%3A&highlight=true}

Go to your `BraTS DREAM Challenge <Your team name>` project and upload your tarball to the `Files` tab.
${image?synapseId=syn26016673&align=Left&scale=50&responsive=true&altText=Uploading your zip files}

---

## **4. Submit your Predictions**

<!-- ${evalsubmit?projectId=syn25829070&unavailableMessage=Please register to make a submission.&buttonText=Submit to the challenge} -->

${image?synapseId=syn26016672&align=Right&scale=50&responsive=true&altText=Submitting a File}
To submit your predictions tarball, navigate to the tarball you uploaded on Synapse and click on the **File Tools** button in the upper-right corner.  Select **Submit File to Challenge** from the options, then follow the prompts. Select the `BraTS Challenge - Task 1` challenge. You can track the status of your submission in the [submission dashboard](#!Synapse:syn25829070/wiki/611102).
