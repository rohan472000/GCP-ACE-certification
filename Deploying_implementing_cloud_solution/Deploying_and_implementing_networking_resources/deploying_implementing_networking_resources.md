To deploy and implement networking resources in Google Cloud, you can follow these steps:

1. Creating a VPC with subnets:

- Open the Google Cloud Console and go to the VPC network page.
- Click "Create VPC network".
- Choose a name for your VPC and select the appropriate mode: custom or auto mode.
- Add one or more subnets to your VPC by clicking "Add subnet".
- Configure the subnet by specifying its name, IP range, and region.
- Click "Create" to create the VPC and subnets.

2. Launching a Compute Engine instance with custom network configuration:

- Open the Google Cloud Console and go to the Compute Engine page.
- Click "Create Instance" to create a new VM instance.
- Choose a name for your instance, select a region, and choose a machine type.
- Expand the "Networking" section and configure your instance's network settings.
- Assign a static external IP address, if necessary.
- Add network tags to your instance to control traffic flow.
- Click "Create" to create the instance.

3. Creating ingress and egress firewall rules for a VPC:

- Open the Google Cloud Console and go to the Firewall rules page.
- Click "Create Firewall Rule" to create a new rule.
- Specify the name and description for your rule.
- Define the direction of traffic flow and the source and destination IP ranges.
- Choose the appropriate protocol and ports to allow or deny.
- Add network tags to apply the rule to specific instances or subnets.
- Click "Create" to create the firewall rule.

4. Creating a VPN between a Google VPC and an external network using Cloud VPN:

- Open the Google Cloud Console and go to the VPN page.
- Click "Create VPN connection" to create a new connection.
- Choose the type of connection: dynamic or static routing.
- Specify the name, peer IP address, and shared secret for your VPN connection.
- Choose the VPC network and subnets to connect to the VPN.
- Configure the routing options and click "Create" to create the VPN connection.

5. Creating a load balancer to distribute application network traffic to an application:

- Open the Google Cloud Console and go to the Load balancing page.
- Click "Create Load Balancer" to create a new load balancer.
- Choose the type of load balancer: HTTP(S) load balancer, SSL proxy load balancer, TCP proxy load balancer, or network load balancer.
- Configure the backend services, health checks, and load balancing algorithms.
- Choose the appropriate frontend configuration and IP address settings.
- Click "Create" to create the load balancer.