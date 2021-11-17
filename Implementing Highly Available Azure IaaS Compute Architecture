# Lab scenario

Adatum Corporation has several on-premises workloads running on a mix of physical servers and virtual machines. Most of the workloads require some level of resiliency, including a range of high availability SLAs. Most of the workloads leverage either Windows Server Failover Clustering or Linux Corosync clusters and Pacemaker resource manager, with synchronous replication between cluster nodes. Adatum is trying to determine how the equivalent functionality can be implemented in Azure. In particular, the Adatum Enterprise Architecture team is exploring the Azure platform capabilities that accommodate high availability requirements within the same data center and between data centers in the same region.

In addition, the Adatum Enterprise Architecture team realizes that resiliency alone might not be sufficient to provide the level of availability expected by its business operations. Some of the workloads have highly dynamic usage patterns, which are currently addressed based on continuous monitoring and custom scripting solutions, automatically provisioning and deprovisioning additional cluster nodes. Usage patterns of others are more predictable, but also need to be occasionally adjusted to account for increase demand for disk space, memory, or processing resources.

To accomplish these objectives, the Architecture team wants to test a range of highly available IaaS compute deployments, including:

Availability sets-based deployment of Azure VMs behind an Azure Load Balancer Basic

Zone-redundant deployment of Azure VMs behind an Azure Load Balancer Standard

Zone-redundant deployment of Azure VM scale sets behind an Azure Application Gateway

Automatic horizontal scaling of Azure VM scale sets (autoscaling)

Manual vertical scaling (compute and storage) of Azure VM scale sets

An availability set represents a logical grouping of Azure VMs which controls their physical placement within the same Azure datacenter. Azure makes sure that the VMs within the same availability set run across multiple physical servers, compute racks, storage units, and network switches. If a hardware or software failure happens, only a subset of your VMs are impacted and your overall solution stays operational. Availability Sets are essential for building reliable cloud solutions. With availability sets, Azure offers 99.95% VM uptime SLA.

Availability zones represent unique physical locations within a single Azure region. Each zone is made up of one or more datacenters equipped with independent power, cooling, and networking. The physical separation of availability zones within a region protects applications and data from datacenter failures. Zone-redundant services replicate your applications and data across availability zones to protect from single-points-of-failure. With availability zones, Azure offers 99.99% VM uptime SLA.

Azure virtual machine scale sets let you create and manage a group of identical, load balanced VMs. The number of VM instances can automatically increase or decrease in response to demand or a defined schedule. Scale sets provide high availability to your applications, and allow you to centrally manage, configure, and update many VMs. With virtual machine scale sets, you can build large-scale services for areas such as compute, big data, and container workloads.
