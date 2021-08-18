<!-- markdownlint-disable no-inline-html -->

<div align="center" class="alert alert-info">
See the <strong><a href="https://www.synapse.org/#!Synapse:syn25829070/discussion/" target="_blank">discussion forum</a></strong> for updates!
</div>


<div align="center" class="alert alert-warning">
Note that Synapse goes down for maintenance on <strong>Sunday evenings (8pm - 12am Pacific Time; Mondays, 5-9am Central European Time)</strong>. Please check <a href="http://status.synapse.org/" target="_blank">status.synapse.org</a> for platform status, in case you encounter any issues accessing the site outside this window.
</div>

### BraTS 2021 Update - August 17, 2021

**Validation Phase Updates**

First, we are going to be giving you a few more days to get your segmentation files scored and your short papers submitted. The short paper is now due on August 23rd at 10:00 AM Eastern Time (please note, this time is earlier than the standard 11:59pm Eastern Time deadline). This short paper submission is **required** in order for participants to continue to the final submission round. If we do not have your short paper in the system by August 23rd at 10AM EST, you will not be able to submit your final docker container.

You can find all the [instructions here](https://www.synapse.org/#!Synapse:syn25829067/wiki/611501) for submitting your short papers, but key takeaways are:
Your paper should be 8-10 pages (excluding references), describing your segmentation method and results. 
Use the [Springer LNCS format](http://bit.ly/2TEcZNF). ([Latex](https://resource-cms.springernature.com/springer-cms/rest/v1/content/19238648/data/v1) and [Microsoft Word](https://resource-cms.springernature.com/springer-cms/rest/v1/content/19238706/data/v1) Templates)
Submit to the Brain Lesion 2021 MICCAI Workshop on the [CMT Submission System](https://cmt3.research.microsoft.com/).
Make sure you choose BRATS as the “Track”

We will be closing the evaluation queue for scoring your segmentation files on Aug 22nd at 23:59 EST. Just to be clear, we cannot guarantee that your segmentation files will be scored and the results returned to you in time for your paper submission. Please submit your segmentation files by August 21 at 23:59 to ensure that you can get your results back and integrated into your short papers.

**Final Submission Updates**

We have updated the [tutorial and instructions](https://www.synapse.org/#!Synapse:syn25829067/wiki/611500) for creating and submitting your Docker containers for the final submission phase. The new language should clarify the expectations for your docker containers. If you have any questions, please post them in the [discussion forum](https://www.synapse.org/#!Synapse:syn25829067/discussion/default). 

We will be opening up the evaluation queue for final docker submissions on Sept 1st at 23:59 EST and will give you two weeks to get your docker image submitted and validated. When you submit your docker image, we will run them against 3-5 cases from the validation data to make sure your containers run, then we will run them against the unseen test set. Your submissions will have a time limit of 4 minutes per case (About 26 hours total).  At the moment, the deadline for your final docker submissions will be Sept 15th, but we will work with you to get your containers validated.

Thank you all for your participation and patience,

The BraTS 2021 Challenge Organizers


### BraTS 2021 Update - July 30, 2021

We are launching the Validation Phase this next Monday, August 2. The [Validation Data](https://www.synapse.org/#!Synapse:syn26017015) is now available for download and we will be accepting segmentation file submissions starting Monday. To clarify, the Validation Phase and the Docker submission phase are two separate phases. During the Validation Phase, we will only be accepting segmentation files as submissions. See [this page](https://www.synapse.org/#!Synapse:syn25829067/wiki/612109) for instructions. We will begin accepting and validating your docker submissions on August 20. 

On August 13 (at 23:59 Eastern Time), the short papers are due for submission to the BrainLes CMT Submission System ([see the short paper submission instructions](https://www.synapse.org/#!Synapse:syn25829067/wiki/611501)). There is an additional required step from previous years. You will need to report your Synapse Team ID when you submit your short papers through the submission site. We have included instructions on how to find that ID on the short paper submission instructions page.

On August 20 (at 23:59 Eastern Time), we will begin accepting final docker container submissions. We will first be running your containers against a small set of images from the validation dataset to make sure they pass technical validation, after which we will be running them against the full Test Dataset. Your containers will have 26 hours to complete all the predictions (average 4 minutes per inference case) in the Test Set and will have access to 1 GPU with 12 GiB GPU memory, 4 vCPU, and 61 GB Memory.

Finally, Sage Bionetworks will be shut down for the first week of August (Aug 2 - 6) and will not be available to answer questions or help with debugging submissions. We are extending the deadline for the Validation Phase by 1 week to August 20, to accommodate this closure. You can still leave questions in the [discussion forum](https://www.synapse.org/#!Synapse:syn25829067/discussion/default), and Sage staff will answer them when they return from vacation. In the meantime, you can direct urgent requests to [brats@cbica.upenn.edu](mailto:brats@cbica.upenn.edu).
