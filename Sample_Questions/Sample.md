9. You are deploying an application to App Engine. You want the number of instances to scale based on request rate. You need at least 3 unoccupied instances at all times. Which scaling type should you use?

- Manual Scaling with 3 instances.

- Basic Scaling with min_instances set to 3.

- Basic Scaling with max_instances set to 3.

- Automatic Scaling with min_idle_instances set to 3. _**Most Voted**_


10. You have a development project with appropriate IAM roles defined. You are creating a production project and want to have the same IAM roles on the new project, using the fewest possible steps. What should you do?

- Use gcloud iam roles copy and specify the production project as the destination project. _**Most Voted**_

- Use gcloud iam roles copy and specify your organization as the destination organization.

- In the Google Cloud Platform Console, use the 'create role from role' functionality.

- In the Google Cloud Platform Console, use the 'create role' functionality and select all applicable permissions.
 

11. You need a dynamic way of provisioning VMs on Compute Engine. The exact specifications will be in a dedicated configuration file. You want to follow Google's recommended practices. Which method should you use?

A. Deployment Manager **Most Voted**
B. Cloud Composer
C. Managed Instance Group
D. Unmanaged Instance Group

12. You have a Dockerfile that you need to deploy on Kubernetes Engine. What should you do?
A. Use kubectl app deploy <dockerfilename>.
B. Use gcloud app deploy <dockerfilename>.
C. Create a docker image from the Dockerfile and upload it to Container Registry. Create a 
   Deployment YAML file to point to that image. Use kubectl to create the deployment with that file. **Most Voted**
D. Create a docker image from the Dockerfile and upload it to Cloud Storage. Create a Deployment YAML 
   file to point to that image. Use kubectl to create the deployment with that file.

13. Your development team needs a new Jenkins server for their project. You need to deploy the server using the fewest steps possible. What should you do?
A. Download and deploy the Jenkins Java WAR to App Engine Standard.
B. Create a new Compute Engine instance and install Jenkins through the command line interface.
C. Create a Kubernetes cluster on Compute Engine and create a deployment with the Jenkins Docker image.
D. Use GCP Marketplace to launch the Jenkins solution. **Most Voted**

14. You need to update a deployment in Deployment Manager without any resource downtime in the deployment. Which command should you use?
A. gcloud deployment-manager deployments create --config <deployment-config-path>
B. gcloud deployment-manager deployments update --config <deployment-config-path> **Most Voted**
C. gcloud deployment-manager resources create --config <deployment-config-path>
D. gcloud deployment-manager resources update --config <deployment-config-path>

15. You need to run an important query in BigQuery but expect it to return a lot of records. You want to find out how 
    much it will cost to run the query. You are using on-demand pricing. What should you do?
A. Arrange to switch to Flat-Rate pricing for this query, then move back to on-demand.
B. Use the command line to run a dry run query to estimate the number of bytes read. Then convert that bytes estimate 
   to dollars using the Pricing Calculator. **Most Voted**
C. Use the command line to run a dry run query to estimate the number of bytes returned. Then convert that bytes 
   estimate to dollars using the Pricing Calculator.
D. Run a select count (*) to get an idea of how many records your query will look through. Then convert that number of 
   rows to dollars using the Pricing Calculator.

16. You have a single binary application that you want to run on Google Cloud Platform. You decided to automatically 
    scale the application based on underlying infrastructure CPU usage. Your organizational policies require you to use virtual machines directly. You need to ensure that the application scaling is operationally efficient and completed as quickly as possible. What should you do?
A. Create a Google Kubernetes Engine cluster, and use horizontal pod autoscaling to scale the application.
B. Create an instance template, and use the template in a managed instance group with autoscaling configured. **Most Voted**
C. Create an instance template, and use the template in a managed instance group that scales up and down based on the 
   time of day.
D. Use a set of third-party tools to build automation around scaling the application up and down, based on Stackdriver
   CPU usage monitoring.

17. You are analyzing Google Cloud Platform service costs from three separate projects. You want to use this 
    information to create service cost estimates by service type, daily and monthly, for the next six months using standard query syntax. What should you do?
A. Export your bill to a Cloud Storage bucket, and then import into Cloud Bigtable for analysis.
B. Export your bill to a Cloud Storage bucket, and then import into Google Sheets for analysis.
C. Export your transactions to a local file, and perform analysis with a desktop tool.
D. Export your bill to a BigQuery dataset, and then write time window-based SQL queries for analysis. **Most Voted**

18. You need to set up a policy so that videos stored in a specific Cloud Storage Regional bucket are moved to 
    Coldline after 90 days, and then deleted after one year from their creation. How should you set up the policy?
A. Use Cloud Storage Object Lifecycle Management using Age conditions with SetStorageClass and Delete actions. Set the 
   SetStorageClass action to 90 days and the Delete action to 275 days (365 ג€" 90)
B. Use Cloud Storage Object Lifecycle Management using Age conditions with SetStorageClass and Delete actions. Set the
   SetStorageClass action to 90 days and the Delete action to 365 days. **Most Voted**
C. Use gsutil rewrite and set the Delete action to 275 days (365-90).
D. Use gsutil rewrite and set the Delete action to 365 days.

19. You have a Linux VM that must connect to Cloud SQL. You created a service account with the appropriate access rights.
    You want to make sure that the VM uses this service account instead of the default Compute Engine service account. What should you do?
A. When creating the VM via the web console, specify the service account under the 'Identity and API Access' section. 
   **Most Voted**
B. Download a JSON Private Key for the service account. On the Project Metadata, add that JSON as the value for the key
   compute-engine-service- account.
C. Download a JSON Private Key for the service account. On the Custom Metadata of the VM, add that JSON as the value 
   for the key compute-engine- service-account. Most Voted
D. Download a JSON Private Key for the service account. After creating the VM, ssh into the VM and save the JSON under
   `~/.gcloud/compute-engine-service- account.json`.

20. You created an instance of SQL Server 2017 on Compute Engine to test features in the new version. You want to 
    connect to this instance using the fewest number of steps. What should you do?
A. Install a RDP client on your desktop. Verify that a firewall rule for port 3389 exists.
B. Install a RDP client in your desktop. Set a Windows username and password in the GCP Console. Use the credentials 
   to log in to the instance. 
C. Set a Windows password in the GCP Console. Verify that a firewall rule for port 22 exists. Click the RDP button in 
   the GCP Console and supply the credentials to log in.
D. Set a Windows username and password in the GCP Console. Verify that a firewall rule for port 3389 exists. Click the
   RDP button in the GCP Console, and supply the credentials to log in. **Most Voted**

21. You have one GCP account running in your default region and zone and another account running in a non-default region 
    and zone. You want to start a new Compute Engine instance in these two Google Cloud Platform accounts using the command
    line interface. What should you do?
A. Create two configurations using gcloud config configurations create [NAME]. Run gcloud config configurations activate
   [NAME] to switch between accounts when running the commands to start the Compute Engine instances. **Most Voted**
B. Create two configurations using gcloud config configurations create [NAME]. Run gcloud configurations list to start 
   the Compute Engine instances.
C. Activate two configurations using gcloud configurations activate [NAME]. Run gcloud config list to start the 
   Compute Engine instances.
D. Activate two configurations using gcloud configurations activate [NAME]. Run gcloud configurations list to start 
   the Compute Engine instances.

22. You significantly changed a complex Deployment Manager template and want to confirm that the dependencies of all 
    defined resources are properly met before committing it to the project. You want the most rapid feedback on your 
    changes. What should you do?
A. Use granular logging statements within a Deployment Manager template authored in Python.
B. Monitor activity of the Deployment Manager execution on the Stackdriver Logging page of the GCP Console.
C. Execute the Deployment Manager template against a separate project with the same configuration, and monitor for 
   failures.
D. Execute the Deployment Manager template using the ג€"-preview option in the same project, and observe the state of 
   interdependent resources. **Most Voted**

23. You are building a pipeline to process time-series data. Which Google Cloud Platform services should you put in 
    boxes 1,2,3(Storage), and 4(Analytics)?
A. Cloud Pub/Sub, Cloud Dataflow, Cloud Datastore, BigQuery
B. Firebase Messages, Cloud Pub/Sub, Cloud Spanner, BigQuery
C. Cloud Pub/Sub, Cloud Storage, BigQuery, Cloud Bigtable
D. Cloud Pub/Sub, Cloud Dataflow, Cloud Bigtable, BigQuery **Most Voted**

24. You have a project for your App Engine application that serves a development environment. The required testing has 
    succeeded and you want to create a new project to serve as your production environment. What should you do?
A. Use gcloud to create the new project, and then deploy your application to the new project. **Most Voted**
B. Use gcloud to create the new project and to copy the deployed application to the new project.
C. Create a Deployment Manager configuration file that copies the current App Engine deployment into a new project.
D. Deploy your application again using gcloud and specify the project parameter with the new project name to create the new project.
 
25. You need to configure IAM access audit logging in BigQuery for external auditors. You want to follow 
    Google-recommended practices. What should you do?
A. Add the auditors group to the 'logging.viewer' and 'bigQuery.dataViewer' predefined IAM roles. **Most Voted**
B. Add the auditors group to two new custom IAM roles.
C. Add the auditor user accounts to the 'logging.viewer' and 'bigQuery.dataViewer' predefined IAM roles.
D. Add the auditor user accounts to two new custom IAM roles.
 
26. You need to set up permissions for a set of Compute Engine instances to enable them to write data into a particular 
    Cloud Storage bucket. You want to follow Google-recommended practices. What should you do?
A. Create a service account with an access scope. Use the access scope 'https://www.googleapis.com/auth/devstorage.write_only'.
B. Create a service account with an access scope. Use the access scope 'https://www.googleapis.com/auth/cloud-platform'.
C. Create a service account and add it to the IAM role 'storage.objectCreator' for that bucket. **Most Voted**
D. Create a service account and add it to the IAM role 'storage.objectAdmin' for that bucket.

27. You have sensitive data stored in three Cloud Storage buckets and have enabled data access logging. You want to 
    verify activities for a particular user for these buckets, using the fewest possible steps. You need to verify 
    the addition of metadata labels and which files have been viewed from those buckets. What should you do?
A. Using the GCP Console, filter the Activity log to view the information. **Most Voted**
B. Using the GCP Console, filter the Stackdriver log to view the information. 
C. View the bucket in the Storage section of the GCP Console.
D. Create a trace in Stackdriver to view the information.


28. You are the project owner of a GCP project and want to delegate control to colleagues to manage buckets and files
    in Cloud Storage. You want to follow Google- recommended practices. Which IAM roles should you grant your 
    colleagues?

- Project Editor

- Storage Admin _**Most Voted**_

- Storage Object Admin

- Storage Object Creator


29. You have an object in a Cloud Storage bucket that you want to share with an external company. The object contains 
    sensitive data. You want access to the content to be removed after four hours. The external company does not have a
    Google account to which you can grant specific user-based access privileges. You want to use the most secure method 
    that requires the fewest steps. What should you do?

- Create a signed URL with a four-hour expiration and share the URL with the company. **_Most Voted_**

- Set object access to 'public' and use object lifecycle management to remove the object after four hours.

- Configure the storage bucket as a static website and furnish the object's URL to the company. Delete the object from 
  the storage bucket after four hours.

- Create a new Cloud Storage bucket specifically for the external company to access. Copy the object to that bucket. 
  Delete the bucket after four hours have passed.


30. You have an object in a Cloud Storage bucket that you want to share with an external company. The object contains 
    sensitive data. You want access to the content to be removed after four hours. The external company does not have a
    Google account to which you can grant specific user-based access privileges. You want to use the most secure method 
    that requires the fewest steps. What should you do?

- Create a signed URL with a four-hour expiration and share the URL with the company. **_Most Voted_**

- Set object access to 'public' and use object lifecycle management to remove the object after four hours.

- Configure the storage bucket as a static website and furnish the object's URL to the company. Delete the object from 
  the storage bucket after four hours.

- Create a new Cloud Storage bucket specifically for the external company to access. Copy the object to that bucket. 
  Delete the bucket after four hours have passed.


31. You are creating a Google Kubernetes Engine (GKE) cluster with a cluster autoscaler feature enabled. You need to 
    make sure that each node of the cluster will run a monitoring pod that sends container metrics to a third-party 
    monitoring solution. What should you do?

- Deploy the monitoring pod in a StatefulSet object.

- Deploy the monitoring pod in a DaemonSet object. **_Most Voted_**

- Reference the monitoring pod in a Deployment object.

- Reference the monitoring pod in a cluster initializer at the GKE cluster creation time.


32. You want to send and consume Cloud Pub/Sub messages from your App Engine application. The Cloud Pub/Sub API is 
    currently disabled. You will use a service account to authenticate your application to the API. You want to make 
    sure your application can use Cloud Pub/Sub. What should you do?

- Enable the Cloud Pub/Sub API in the API Library on the GCP Console. **_Most Voted_**

- Rely on the automatic enablement of the Cloud Pub/Sub API when the Service Account accesses it.

- Use Deployment Manager to deploy your application. Rely on the automatic enablement of all APIs used by the 
  application being deployed.

- Grant the App Engine Default service account the role of Cloud Pub/Sub Admin. Have your application enable the API on
  the first connection to Cloud Pub/ Sub.


33. You need to monitor resources that are distributed over different projects in Google Cloud Platform. You want to 
    consolidate reporting under the same Stackdriver Monitoring dashboard. What should you do?

- Use Shared VPC to connect all projects, and link Stackdriver to one of the projects.

- For each project, create a Stackdriver account. In each project, create a service account for that project and grant
  it the role of Stackdriver Account Editor in all other projects.

- Configure a single Stackdriver account, and link all projects to the same account. _**Most Voted_**

- Configure a single Stackdriver account for one of the projects. In Stackdriver, create a Group and add the other 
  project names as criteria for that Group.


34. You are deploying an application to a Compute Engine VM in a managed instance group. The application must be running
    at all times, but only a single instance of the VM should run per GCP project. How should you configure the instance
    group?

- Set autoscaling to On, set the minimum number of instances to 1, and then set the maximum number of instances to 1. 
   **_Most Voted_**

- Set autoscaling to Off, set the minimum number of instances to 1, and then set the maximum number of instances to 1.

- Set autoscaling to On, set the minimum number of instances to 1, and then set the maximum number of instances to 2.

- Set autoscaling to Off, set the minimum number of instances to 1, and then set the maximum number of instances to 2.


35. You want to verify the IAM users and roles assigned within a GCP project named my-project. What should you do?

- Run gcloud iam roles list. Review the output section.

- Run gcloud iam service-accounts list. Review the output section.

- Navigate to the project and then to the IAM section in the GCP Console. Review the members and roles. **_Most Voted_**

- Navigate to the project and then to the Roles section in the GCP Console. Review the roles and status.


36. You need to create a new billing account and then link it with an existing Google Cloud Platform project. 
What should you do?

- Verify that you are Project Billing Manager for the GCP project. Update the existing project to link it to the 
  existing billing account. 

- Verify that you are Project Billing Manager for the GCP project. Create a new billing account and link the new billing 
  account to the existing project. _**Most Voted_**

- Verify that you are Billing Administrator for the billing account. Create a new project and link the new project to 
  the existing billing account.

- Verify that you are Billing Administrator for the billing account. Update the existing project to link it to the 
  existing billing account.


37. You have one project called proj-sa where you manage all your service accounts. You want to be able to use a 
    service account from this project to take snapshots of VMs running in another project called proj-vm. What should 
    you do?

- Download the private key from the service account, and add it to each VMs custom metadata.

- Download the private key from the service account, and add the private key to each VM's SSH keys.

- Grant the service account the IAM Role of Compute Storage Admin in the project called proj-vm. **_Most Voted_**

- When creating the VMs, set the service account's API scope for Compute Engine to read/write.


38. You created a Google Cloud Platform project with an App Engine application inside the project. You initially 
    configured the application to be served from the us- central region. Now you want the application to be served from 
    the asia-northeast1 region. What should you do?

- Change the default region property setting in the existing GCP project to asia-northeast1.

- Change the region property setting in the existing App Engine application from us-central to asia-northeast1.

- Create a second App Engine application in the existing GCP project and specify asia-northeast1 as the region to serve
  your application.

- Create a new GCP project and create an App Engine application inside this new project. Specify asia-northeast1 as the 
  region to serve your application. **_Most Voted_**


39. You need to grant access for three users so that they can view and edit table data on a Cloud Spanner instance. 
    What should you do?

- Run gcloud iam roles describe roles/spanner.databaseUser. Add the users to the role.

- Run gcloud iam roles describe roles/spanner.databaseUser. Add the users to a new group. Add the group to the role. 
  **_Most Voted_**

- Run gcloud iam roles describe roles/spanner.viewer - -project my-project. Add the users to the role.

- Run gcloud iam roles describe roles/spanner.viewer - -project my-project. Add the users to a new group. 
  Add the group to the role.


40. You create a new Google Kubernetes Engine (GKE) cluster and want to make sure that it always runs a supported and 
    stable version of Kubernetes. What should you do?

- Enable the Node Auto-Repair feature for your GKE cluster.

- Enable the Node Auto-Upgrades feature for your GKE cluster. **_Most Voted_**

- Select the latest available cluster version for your GKE cluster.

- Select ג€Container-Optimized OS (cos)ג€ as a node image for your GKE cluster.


41. You have an instance group that you want to load balance. You want the load balancer to terminate the client SSL 
    session. The instance group is used to serve a public web application over HTTPS. You want to follow 
    Google-recommended practices. What should you do?

- Configure an HTTP(S) load balancer. **_Most Voted_**

- Configure an internal TCP load balancer.

- Configure an external SSL proxy load balancer.

- Configure an external TCP proxy load balancer.


42. You have 32 GB of data in a single file that you need to upload to a Nearline Storage bucket. The WAN connection you 
    are using is rated at 1 Gbps, and you are the only one on the connection. You want to use as much of the rated 1 
    Gbps as possible to transfer the file rapidly. How should you upload the file?

- Use the GCP Console to transfer the file instead of gsutil.

- Enable parallel composite uploads using gsutil on the file transfer. **_Most Voted_**

- Decrease the TCP window size on the machine initiating the transfer.

- Change the storage class of the bucket from Nearline to Multi-Regional.


43. You've deployed a microservice called myapp1 to a Google Kubernetes Engine cluster using the YAML file specified below:
    
    ```
    name: PASSWORD
    values: "xcvfshhs"
    ```

    You need to refactor this configuration so that the database password is not stored in plain text. You want to follow 
    Google-recommended practices. What should you do?

- Store the database password inside the Docker image of the container, not in the YAML file.

- Store the database password inside a Secret object. Modify the YAML file to populate the DB_PASSWORD environment 
  variable from the Secret. _**Most Voted_**

- Store the database password inside a ConfigMap object. Modify the YAML file to populate the DB_PASSWORD environment 
  variable from the ConfigMap.

- Store the database password in a file inside a Kubernetes persistent volume, and use a persistent volume claim to 
  mount the volume to the container.
 

44. You are running an application on multiple virtual machines within a managed instance group and have autoscaling 
    enabled. The autoscaling policy is configured so that additional instances are added to the group if the CPU 
    utilization of instances goes above 80%. VMs are added until the instance group reaches its maximum limit of five 
    VMs or until CPU utilization of instances lowers to 80%. The initial delay for HTTP health checks against the 
    instances is set to 30 seconds.
    The virtual machine instances take around three minutes to become available for users. You observe that when the 
    instance group autoscales, it adds more instances then necessary to support the levels of end-user traffic. You 
    want to properly maintain instance group sizes when autoscaling. What should you do?

- Set the maximum number of instances to 1.

- Decrease the maximum number of instances to 3.

- Use a TCP health check instead of an HTTP health check.

- Increase the initial delay of the HTTP health check to 200 seconds. **_Most Voted_**


45. You need to select and configure compute resources for a set of batch processing jobs. These jobs take around 2 
    hours to complete and are run nightly. You want to minimize service costs. What should you do?

- Select Google Kubernetes Engine. Use a single-node cluster with a small instance type.

- Select Google Kubernetes Engine. Use a three-node cluster with micro instance types.

- Select Compute Engine. Use preemptible VM instances of the appropriate standard machine type. **_Most Voted_**

- Select Compute Engine. Use VM instance types that support micro bursting.


46. You recently deployed a new version of an application to App Engine and then discovered a bug in the release. You 
    need to immediately revert to the prior version of the application. What should you do?

- Run gcloud app restore.

- On the App Engine page of the GCP Console, select the application that needs to be reverted and click Revert.

- On the App Engine Versions page of the GCP Console, route 100% of the traffic to the previous version. **_Most Voted_**

- Deploy the original version as a separate application. Then go to App Engine settings and split traffic between 
  applications so that the original version serves 100% of the requests.


47. You deployed an App Engine application using gcloud app deploy, but it did not deploy to the intended project. 
    You want to find out why this happened and where the application deployed. What should you do?

- Check the app.yaml file for your application and check project settings.

- Check the web-application.xml file for your application and check project settings.

- Go to Deployment Manager and review settings for deployment of applications.

- Go to Cloud Shell and run gcloud config list to review the Google Cloud configuration used for deployment. **_Most Voted_**


48. You want to configure 10 Compute Engine instances for availability when maintenance occurs. Your requirements state
    that these instances should attempt to automatically restart if they crash. Also, the instances should be highly 
    available including during system maintenance. What should you do?

- Create an instance template for the instances. Set the 'Automatic Restart' to on. Set the 'On-host maintenance' to 
  Migrate VM instance. Add the instance template to an instance group. **_Most Voted_**

- Create an instance template for the instances. Set 'Automatic Restart' to off. Set 'On-host maintenance' to Terminate 
  VM instances. Add the instance template to an instance group.

- Create an instance group for the instances. Set the 'Autohealing' health check to healthy (HTTP).

- Create an instance group for the instance. Verify that the 'Advanced creation options' setting for 'do not retry 
  machine creation' is set to off.


49. 