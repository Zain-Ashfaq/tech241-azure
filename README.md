# Cloud

## What is cloud?

Services that are available on demand via the internet.
Cloud data centers have water cooling and backup generators to ensure resilience.
Data centers are often located at a minimum distance to mitigate the risk of natural disasters.

## Advantages of Using the Cloud:

Scalability: Cloud services allow easy scaling of resources based on demand, avoiding overprovisioning or underutilization.
Cost efficiency: Pay-as-you-go model eliminates upfront infrastructure investment, resulting in potential cost savings compared to on-premises infrastructure.
Accessibility: Cloud services can be accessed from anywhere with an internet connection, enabling remote work and collaboration.
Reliability and disaster recovery: Cloud providers have robust infrastructure and backup systems, ensuring high availability and data redundancy.
Automatic updates: Cloud providers handle maintenance, security updates, and software upgrades, saving IT resources and ensuring access to the latest features.

## Disadvantages of Using the Cloud:

Dependency on internet connectivity: Cloud services rely on internet connectivity, and network issues or outages can impact accessibility and productivity.
Data security and privacy concerns: Storing data in the cloud requires trusting third-party providers and implementing robust security measures.
Limited control: Organizations have less control over infrastructure, updates, and customization options in the cloud.
Potential vendor lock-in: Transferring data and applications between cloud providers or on-premises infrastructure can be complex and time-consuming.

## Disadvantages of Hybrid Cloud or Multi-Cloud:

Complexity: Managing multiple cloud environments and integrating them with on-premises infrastructure requires additional resources and expertise.
Cost and management overhead: Maintaining multiple cloud accounts can lead to increased management overhead and potentially higher costs.
Data and application portability challenges: Moving data and applications between different cloud providers or environments can be challenging.

## On-Premises vs. Cloud Cost Comparison:

Cloud computing eliminates upfront hardware and infrastructure investment, reducing capital expenditure.
Cloud services offer lower maintenance costs as the provider handles infrastructure maintenance and upgrades.
Pay-as-you-go model allows cost optimization by paying only for resources used.
On-premises infrastructure may be more cost-effective for predictable workloads or specific compliance requirements.

## Determining the "Best" Cloud Provider:

Choose a cloud provider based on organizational needs, considering service offerings, reliability, performance, pricing, customer support, and compatibility with existing tools and services.

## Management Groups:

Management groups help with access, compliance, and policy enforcement across multiple subscriptions.
They enable setting specific resource quotas and permissions for different teams.
Management groups can be nested to create a hierarchical structure for better organization and management.

## Subscription:

A separate payment account used to manage resources and billing.
Each subscription receives a separate bill and can have different types, such as student subscriptions or pay-as-you-go.
Quotas can be set for each subscription to limit the number of resource groups or resources.

## Resource Groups:

Containers for organizing and managing resources within a subscription.
Resource groups cannot be nested within other resource groups.
While Azure requires resource groups, they are not mandatory in AWS.

## Resources:

Resources are the individual components, such as virtual machines or storage accounts, that need to be managed within a resource group.

## CapEx vs. OpEx:

Capital expenditure (CapEx) refers to upfront costs associated with purchasing and maintaining physical hardware, often associated with on-premises infrastructure.
Operating expenses (OpEx) are ongoing expenses spread out over time, such as monthly or annual fees, commonly associated with cloud services.

## Tags:

Tags are key-value pairs used to label and categorize resources.
They help in grouping and organizing resources for billing and management purposes.

## ARM (Azure Resource Manager):

ARM is an API and management layer for Azure resources.
It allows CRUD operations (Create, Read, Update, Delete) on Azure resources.
ARM controls the deployment and management of resources in the background.

## Virtual Network:

Virtual Network is a logical representation of a network infrastructure in the cloud.
It provides a level of protection and security for resources.
Subnets within a virtual network divide the network into smaller segments, similar to rooms in a house, and they cannot overlap.
What is virtualization?

Virtualization is the process of creating virtual versions of physical resources, such as servers, storage devices, or networks.
It allows multiple virtual instances to run on a single physical infrastructure, effectively maximizing resource utilization.

## What is a virtual machine?

A virtual machine (VM) is a software emulation of a physical computer that runs on a host machine.
It has its own operating system and behaves like an independent machine, capable of running applications and executing tasks.

## Where can virtual machines be run?

Virtual machines can be run on various types of physical infrastructure, including:
On-premises data centers: Organizations can set up their own virtualization infrastructure using dedicated servers and virtualization software.
Cloud platforms: Cloud service providers offer virtual machines as part of their services, enabling users to run VMs on their infrastructure.

## What determines how many virtual machines can run?

The number of virtual machines that can run depends on several factors, including:
Physical hardware capacity: The resources available on the host machine, such as CPU, memory, and storage, determine how many VMs can be supported.
Resource allocation: The allocation of resources to each virtual machine affects the total number of VMs that can run concurrently.
Workload requirements: The resource demands of the applications running within the VMs impact the number of VMs that can effectively operate on a given infrastructure.

## What does a virtual machine include?

A virtual machine includes several components:
Virtual hardware: Emulated components, such as virtual CPU, memory, disk storage, and network interfaces.
Operating system: Each virtual machine runs its own operating system, such as Windows or Linux.
Applications: Virtual machines can host applications, just like physical machines.
Configuration settings: Virtual machines have specific settings, such as network configurations, disk allocation, and security parameters.

## What software is required to orchestrate/run the virtual machines?

Virtualization software, also known as a hypervisor, is required to orchestrate and run virtual machines. Examples include:

Microsoft Hyper-V
KVM (Kernel-based Virtual Machine)
Oracle VM VirtualBox

## What is the importance of an image when creating a VM?

An image is a template or snapshot of a pre-configured virtual machine.
When creating a VM, the image serves as a blueprint, containing the operating system, applications, and configurations required for the virtual machine.
Using images allows for quick and consistent deployment of virtual machines, ensuring that each instance starts from a known and standardized state.
Images also enable the efficient scaling of VMs, as multiple instances can be created from the same base image.
