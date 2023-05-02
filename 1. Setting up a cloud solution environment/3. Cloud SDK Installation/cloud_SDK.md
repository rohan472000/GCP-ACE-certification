1. Installing the Cloud SDK CLI:

To install the Cloud SDK CLI, follow the instructions in the documentation for your operating system. 
Here are the links to the documentation for the most popular operating systems:

- [Installing on Windows](https://cloud.google.com/sdk/docs/install#windows)
- [Installing on macOS](https://cloud.google.com/sdk/docs/install#mac)
- [Installing on Linux](https://cloud.google.com/sdk/docs/install#linux)


2. Initializing the Cloud SDK:

After installing the Cloud SDK, you need to initialize it by running the following command:

```
gcloud init
```

This command will guide you through the process of configuring the Cloud SDK. 
It will prompt you to log in to your Google account, select a project, and set a default compute zone and region.


3. Setting the default project:

To set the default project for the Cloud SDK, run the following command:

```
gcloud config set project [PROJECT_ID]
```

Replace [PROJECT_ID] with the ID of the project you want to set as the default.


4. Verifying the default project:

To verify that the default project has been set correctly, run the following command:

```
gcloud config list
```

This command will display the current configuration settings for the Cloud SDK, including the default project.