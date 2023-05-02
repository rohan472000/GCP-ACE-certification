1. Selecting appropriate compute choices:

Google Cloud offers several compute choices for running workloads, including Compute Engine, 
Google Kubernetes Engine, Cloud Run, and Cloud Functions. When selecting a compute option, 
consider factors such as the required level of control, the need for scalability, and the type of workload being run.

- Compute Engine: Compute Engine provides virtual machines that can be customized to meet specific requirements. 
  It offers a high level of control over the underlying infrastructure and can be used for a wide range of workloads.

- Google Kubernetes Engine: Google Kubernetes Engine is a managed service for running containerized workloads. 
  It provides a scalable and flexible platform for deploying and managing containerized applications.

- Cloud Run: Cloud Run is a managed compute platform that automatically scales containerized applications.
  It provides a serverless experience and can be used for stateless HTTP workloads.

- Cloud Functions: Cloud Functions is a serverless compute platform that allows developers to run code in response to events.
  It provides a simple and scalable way to run small pieces of code in the cloud.

2. Using preemptible VMs:

Preemptible VMs are a cost-effective option for running short-lived or batch workloads. 
They are up to 80% cheaper than standard VMs but are subject to being terminated by Google after 24 hours of runtime. 
To use preemptible VMs, specify the "preemptible" option when creating a new VM instance using the Compute Engine API or
the gcloud command-line tool:

```
gcloud compute instances create [INSTANCE_NAME] --preemptible
```

3. Using custom machine types:

Custom machine types allow you to specify the exact number of vCPUs and memory for a VM instance, 
providing greater flexibility and cost control. To create a custom machine type, use the Compute Engine 
API or the gcloud command-line tool:

```
gcloud compute machine-types create [MACHINE_TYPE_NAME] --custom-vm-cpu [CPU_COUNT] --custom-vm-memory [MEMORY_SIZE]
```
Replace [MACHINE_TYPE_NAME] with a name for the custom machine type, [CPU_COUNT] with the number of vCPUs, and [MEMORY_SIZE] with 
the amount of memory in MB.