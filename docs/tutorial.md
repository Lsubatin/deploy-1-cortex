# Google Cloud Cortex Framework

<walkthrough-tutorial-duration duration="30min"></walkthrough-tutorial-duration>

## Data Foundation for Google Cloud Cortex Framework

The Data Foundation for [Google Cloud Cortex Framework](https://cloud.google.com/solutions/cortex) is a set of analytical artifacts, that can be automatically deployed together with reference architectures.

This tutorial will guide you through Data Foundation configuration and deployment.

Click the **Start** button to move to the next step.

## Please select a project for deployment or create one

This project will be used:

- As the source project for Cortex data
- To execute the deployment steps.

For more information visit [the Data Foundation Documentation](https://github.com/GoogleCloudPlatform/cortex-data-foundation#gather-the-parameters-for-deployment).

<walkthrough-project-setup billing="true"></walkthrough-project-setup>

## Would you like to learn how this works or just deploy in one click?

**Looking to learn how deployment works?**

- Run these commands in Cloud Shell

```bash
cloudshell open config/config.json
cloudshell workspace .
```

- Follow [deployment instructions in README](https://github.com/GoogleCloudPlatform/cortex-data-foundation/blob/main/README.md#deployment)

**For Demo installations only**, we can automatically create test datasets and artifacts for you in a few clicks.

Simply run this command in Cloud Shell

```bash
./1-click.sh --project "<walkthrough-project-id/>"
```

<walkthrough-footnote>The 1-Click deployment would create all datasets and GCS buckets. </walkthrough-footnote>

## Conclusion

Thanks for using Google Cloud Cortex Framework!

<walkthrough-conclusion-trophy></walkthrough-conclusion-trophy>
