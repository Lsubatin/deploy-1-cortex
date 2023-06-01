# Cortex guided deployment
<walkthrough-tutorial-duration duration="30min"></walkthrough-tutorial-duration>

## Please select a project for deployment or create one.

This project will be used:
-   As the source project for Cortex data 
-   To execute the deployment steps. 

For more information visit [the Data Foundation Documentation](https://github.com/GoogleCloudPlatform/cortex-data-foundation#gather-the-parameters-for-deployment).

<walkthrough-project-setup></walkthrough-project-setup>

## Would you like to learn how this works or just deploy in one click?

**Looking to learn how deployment works?** Choose **Next** and we will walk you through the steps.

**For Demo installations only**, we can automatically create test datasets and artifacts for you in a few clicks. Navigate to the following tutorial. <walkthrough-load-tutorial-url tutorialId="TUTORIAL_ID">**Please use your imagination :)**</walkthrough-load-tutorial-url>

<walkthrough-footnote>The 1-Click deployment would create all datasets and GCS buckets. </walkthrough-footnote>

## Fill in deployment parameters

Your deployment will require some decisions from you. Here we would explain what source and taregt projects are.

### Open the configuration file

The config.json file governs all of the deployment parameters. 

<walkthrough-editor-open-file filePath="./cloudshell_open/deploy-1-cortex/config/config.json"> Open file</walkthrough-editor-open-file>

### Fill in the source project 

In the file, following `projectIdSource` use the this value:

 _<walkthrough-project-name/>_ 

## Conclusion

Thanks for using your imagination! 

<walkthrough-conclusion-trophy></walkthrough-conclusion-trophy>