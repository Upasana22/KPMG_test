# KPMG_test
Round 1: Tech Assessment: (Azure)

Link Referred - https://github.com/Azure/azure-quickstart-templates/tree/master/application-workloads/redhat/rhel-3tier-iaas 
Template Solution Architecture

This template from the architectural diagram will deploy:
1. Four storage accounts: 3 for storing VM's disks of each tier, 1 for storing diagnostics data.
2. One Virtual Network with four subnets.
3. Four Network Security Group, one for each subnet.
4. External load balancer to load balance Web Traffic(HTTP & HTTPS) to web servers.
5. Internal load balancer to load balance traffic for app VM's.
6. Two Public IP’s, one for external Load balancer and other for Jump VM.
7. Three Virtual Machine Availability sets for Web Tier, Application Tier and Database tier.
8. One Jump VM to faclitate ssh access to all other tier VMs.
9. Multiple Red Hat Enterprise Linux VMs for each tier as per parameter value specified during deployment.
