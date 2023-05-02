Managing networking resources in Google Cloud Platform (GCP) involves several tasks, including:

1. Adding a subnet to an existing VPC: A subnet is a range of IP addresses in a VPC network. 
   To add a subnet to an existing VPC, you can use the Google Cloud Console, Cloud SDK, or the REST API. 
   Here are the basic steps to add a subnet:

- Navigate to the VPC network in which you want to add a subnet.
- Click on the "Subnets" tab and click "Create Subnet".
- Provide the necessary information, including subnet name, IP range, and region.
- Click "Create" to create the new subnet.

2. Expanding a subnet to have more IP addresses: To expand a subnet, you can increase the range of IP addresses
   in the subnet. Here are the basic steps:

- Navigate to the VPC network that contains the subnet you want to expand.
- Click on the "Subnets" tab and click on the subnet you want to expand.
- Click "Edit" to edit the subnet configuration.
- Increase the IP address range.
- Click "Save" to save the new configuration.

3. Reserving static external or internal IP addresses: To reserve static IP addresses in GCP, you can use the 
   Google Cloud Console, Cloud SDK, or the REST API. Here are the basic steps to reserve a static IP address:

- Navigate to the VPC network in which you want to reserve a static IP address.
- Click on the "External IP addresses" or "Internal IP addresses" tab, depending on the type of IP address you want to reserve.
- Click "Reserve Static Address".
- Provide the necessary information, including IP address name and region (for external IP addresses).
- Click "Reserve" to reserve the new static IP address.

4. Working with CloudDNS, CloudNAT, Load Balancers and firewall rules: Cloud DNS is a scalable and reliable DNS 
   service that can be used to publish and manage domain names. Cloud NAT is a service that provides NAT for 
   instances that have only private IP addresses. Load balancers are used to distribute traffic across instances.
   Firewall rules are used to allow or deny traffic to instances based on IP address, port, and protocol.

To work with these networking resources, you can use the Google Cloud Console, Cloud SDK, or the REST API. 
The specific commands and steps will depend on the resource you are working with. For example, to create 
a load balancer, you can follow these basic steps:

- Navigate to the Load Balancing page in the Google Cloud Console.
- Click "Create Load Balancer".
- Select the type of load balancer you want to create (e.g. HTTP(S), TCP, UDP).
- Configure the load balancer settings, including the front-end IP address, back-end instance group, and health check settings.
- Click "Create" to create the new load balancer.