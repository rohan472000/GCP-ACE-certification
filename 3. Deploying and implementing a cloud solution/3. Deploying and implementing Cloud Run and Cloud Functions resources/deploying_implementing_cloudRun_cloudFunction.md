To deploy and implement Cloud Run and Cloud Functions resources, follow these steps:

1. Deploying an application and updating scaling configuration, versions, and traffic splitting:

- Create a container image for your application
- Deploy the application to Cloud Run by running the command `gcloud run deploy [SERVICE_NAME] --image=[IMAGE_URL]`
- Update the scaling configuration for your service by running the command
  `gcloud run services update [SERVICE_NAME] --min-instances=[MIN_INSTANCES] --max-instances=[MAX_INSTANCES]`
- Create a new version of your service by running the command 
  `gcloud run deploy [SERVICE_NAME] --image=[NEW_IMAGE_URL] --tag=[NEW_TAG]`
- Split traffic between versions of your service by running the command 
  `gcloud run services update-traffic [SERVICE_NAME] --to-tags=[NEW_TAG]=[PERCENTAGE],[OLD_TAG]=[OLD_PERCENTAGE]`

2. Deploying an application that receives Google Cloud events:

- Create a Cloud Function or Cloud Run service that will receive the Google Cloud event
- For Pub/Sub events, create a Pub/Sub topic and subscription to receive the event
- For Cloud Storage object change notification events, enable object change notifications on the bucket and create a 
  Cloud Function or Cloud Run service to handle the event
- Configure the Cloud Function or Cloud Run service to handle the event by writing the appropriate code and specifying 
  the event trigger in the configuration

By following these steps, you can deploy and implement Cloud Run and Cloud Functions resources, including scaling 
configuration, versioning, traffic splitting, and receiving Google Cloud events.