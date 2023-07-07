# Google Cloud Cortex Framework

<walkthrough-tutorial-duration duration="30min"></walkthrough-tutorial-duration>

## Data Foundation for Google Cloud Cortex Framework

The Data Foundation for [Google Cloud Cortex Framework](https://cloud.google.com/solutions/cortex) is a set of analytical artifacts, that can be automatically deployed together with reference architectures.

This tutorial will guide you through Data Foundation configuration and deployment **for a demo environment**.

Click the **Start** button to move to the next step.

## Please select a project for deployment or create one

This project will be used:

- As the source project for Cortex data
- To execute the deployment steps.

For more information visit [the Data Foundation Documentation](https://github.com/GoogleCloudPlatform/cortex-data-foundation#gather-the-parameters-for-deployment).

<walkthrough-project-setup billing="true"></walkthrough-project-setup>

## Deploy a demo of Cortex Data Foundation

### **For Demo installations only**

Deployment will automatically create test datasets and artifacts for you in a few clicks. 

Simply run this command in Cloud Shell and follow instructions:

```bash
./get_copy.sh --project "<walkthrough-project-id/>"
```

<walkthrough-footnote>The 1-Click deployment will create all datasets and GCS buckets. If you want to learn how to prepare for a productive deployment, check [the Data Foundation Documentation](https://github.com/GoogleCloudPlatform/cortex-data-foundation) </walkthrough-footnote>

## Conclusion

Follow the 

Thanks for trying Google Cloud Cortex Framework!

<walkthrough-conclusion-trophy></walkthrough-conclusion-trophy>
