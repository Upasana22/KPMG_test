This template will deploy:

Four storage accounts: 3 for storing VM's disks of each tier, 1 for storing diagnostics data.
One Virtual Network with four subnets.
4 Network Security Group, one for each subnet.
External Load Balancer to load balance Web Traffic(HTTP & HTTPS) to web servers.
Internal Load Balancer to load balance traffic for app VM's.
2 Public IP’s, one for external Load balancer and other for Jump VM.
3 Virtual Machine Availability sets for Web Tier, Application Tier and Database tier.
One Jump VM to faclitate ssh access to all other tier VMs.
Multiple Red Hat Enterprise Linux VMs for each tier as per parameter value specified during deployment.
