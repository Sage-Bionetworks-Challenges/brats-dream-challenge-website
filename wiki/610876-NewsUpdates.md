<!-- markdownlint-disable no-inline-html -->

<div align="center" class="alert alert-info">
See the <strong><a href="https://www.synapse.org/#!Synapse:syn25829070/discussion/" target="_blank">discussion forum</a></strong> for updates!
</div>


<div align="center" class="alert alert-warning">
Note that Synapse goes down for maintenance on <strong>Sunday evenings (8pm - 12am Pacific Time; Mondays, 5-9am Central European Time)</strong>. Please check <a href="http://status.synapse.org/" target="_blank">status.synapse.org</a> for platform status, in case you encounter any issues accessing the site outside this window.
</div>

### BraTS 2021 Update - July 30, 2021

We are launching the Validation Phase this next Monday, August 2. The [Validation Data](https://www.synapse.org/#!Synapse:syn26017015) is now available for download and we will be accepting segmentation file submissions starting Monday. To clarify, the Validation Phase and the Docker submission phase are two separate phases. During the Validation Phase, we will only be accepting segmentation files as submissions. See [this page](https://www.synapse.org/#!Synapse:syn25829067/wiki/612109) for instructions. We will begin accepting and validating your docker submissions on August 20. 

On August 13 (at 23:59 Eastern Time), the short papers are due for submission to the BrainLes CMT Submission System ([see the short paper submission instructions](https://www.synapse.org/#!Synapse:syn25829067/wiki/611501)). There is an additional required step from previous years. You will need to report your Synapse Team ID when you submit your short papers through the submission site. We have included instructions on how to find that ID on the short paper submission instructions page.

On August 20 (at 23:59 Eastern Time), we will begin accepting final docker container submissions. We will first be running your containers against a small set of images from the validation dataset to make sure they pass technical validation, after which we will be running them against the full Test Dataset. Your containers will have 26 hours to complete all the predictions (average 4 minutes per inference case) in the Test Set and will have access to 1 GPU with 12 GiB GPU memory, 4 vCPU, and 61 GB Memory.

Finally, Sage Bionetworks will be shut down for the first week of August (Aug 2 - 6) and will not be available to answer questions or help with debugging submissions. We are extending the deadline for the Validation Phase by 1 week to August 20, to accommodate this closure. You can still leave questions in the [discussion forum](https://www.synapse.org/#!Synapse:syn25829067/discussion/default), and Sage staff will answer them when they return from vacation. In the meantime, you can direct urgent requests to [brats@cbica.upenn.edu](mailto:brats@cbica.upenn.edu).
