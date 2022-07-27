# Welcome to the course assessment on Azure Fundamentals (Compute and Networking)

This aassessment is composed up of the below sections:

### Section 1 [30 Points]
Multiple choice Questions

### Time Given
1 Hour

## Section 1 - MCQs

#### Question 1.

```
Your organization, the Nutex Corporation, has moved its customer-specific web applications from on-premises to the Azure cloud. You have created several VMs for the web applications. You plan to configure virtual machine scale sets to ensure high availability of the applications.

Which of the following statements are TRUE or FALSE regarding virtual machine scale sets?

A. Virtual machine scale sets help build large-scale services for areas such as compute, big data, and container workloads.	
B. Virtual machine scale sets in a single datacenter ensure web applications are available if a single datacenter fails.	
C. Virtual machine scale sets allow the application to scale automatically as resource demand changes.	
D. Virtual machine scale sets are used to run only a single instance of your application.	
E. When using virtual machine scale sets, all VM instances are created from different OS images and have different configurations.	
F. Virtual machine scale sets can automatically create and integrate with Azure Load Balancer and Application Gateway.
```

#### Question 2.

```
You are a system administrator for Nutex Corporation. You plan to deploy virtual machines (VMs) in the Azure virtual network (VNet) for development and testing purposes.

Which of the following resources are required by the VM when it is created (Yes/No)? 

A. Resources	
B. Resource group	
C. Storage account	
D. Virtual network	
E. Public IP address	
F. Network interface	
G. Data disks
H. Operating System Disks	
```

#### Question 3

```
You are a system administrator for Nutex, Inc. Your organization has Sales, Finance, and Marketing departments. You have created 30 virtual machines, ten for each department, in the Azure virtual network. All machines are in a single subnet named SubnetA, having an IP address range of 10.0.0.0/24.

You want to ensure that the virtual machines of each department do not communicate with the virtual machines of the other departments.

What should you do?

Place the steps in the correct order.

A. Move the Finance department VMs to SubnetB and the Marketing department VMs to SubnetC, and leave the Sales department VMs in SubnetA.
B. Create two more subnets named SubnetB and SubnetC with separate IP address ranges of 172.16.0.0/24 and 192.168.0.0/24.
C. Create a custom routing table to restrict communication between SubnetA, SubnetB, and SubnetC.
```

#### Question 4
```
Metroil Corporation deploys several proprietary applications. They want a cloud-based solution that will let each application run in its own "sandbox." As their IT consultant, you suggest using Azure Container Instances (ACI).

What are some advantages to this method? (Choose three.)

A. ACI allows fast creation of virtual machines
B. ACI offers role-based access control (RBAC)
C. ACI automatically scales to meet high demand
D. You can access containers directly from a URL
E. ACI can access Linux containers
```

#### Question 5
```
The Nutex Corporation has begun migrating resources to Azure. The corporation has systems that must continue working and whose communication should be a direct connection from an on-premises datacenter to the Microsoft cloud.

Encryption of connectivity is not necessary.

Which solution should be used?

A. Azure Load Balancer
B. Application Gateway
C. Azure ExpressRoute
D. Azure Traffic Manager

```
#### Question 6

```
You are a system administrator for Verigon Corporation. You have been tasked with planning to move an on-premises business application to the Azure cloud. You are exploring Azure services and looking for a solution to move applications to a virtualized environment.

Which of the following Azure services provides a portable environment for virtualized applications where you can run multiple instances of an application on a single host machine?

A. Azure Functions
B. Azure Container Instances
C. Azure virtual machines
D. Azure App Service
```

#### Question 7

```
The web team of the Nutex Corporation is developing a new enterprise solution. They are using the newest technologies, and the functionality is divided into many independent parts that can be maintained, scaled, or updated independently. Locally they have installed Docker on Windows 10 machines.

They need a development environment for testing in Azure.

What will you recommend as the fastest and simplest way to deploy the development environment in Azure?

A. Azure Container Instances (ACI)
B. Azure Functions
C. Azure Virtual Machine (VM)
D. Azure Kubernetes Service (AKS)
```

#### Question 8

```
The Nutex Corporation wants to deploy Windows and Linux applications for its customers. They intend to use the capacity, scalability, and reach of Azure to accomplish this.

Which of the following statements about Azure virtual machines are TRUE? (Choose three.)

A. Azure charges in real-time for the virtual machines’ size and operating system.
B. Virtual machines in the Deallocated state do not incur compute costs.
C. Virtual machines use virtual hard disks to store their operating system (OS) and data.
D. Virtual machines in the Stopped state do incur compute charges.
E. OS disks on virtual machines can be resized.
F. Existing virtual machines can be added to an Azure availability set.
```

#### Question 9
```
You need to provide access to your Azure virtual network for twenty remote workers. Which Azure VPN connection does not require an on-premises public-facing IP address or a VPN device?

A. Express Route
B. VNet-toVNet VPN
C. Site-to-site VPN
D. Point-to-site VPN
```

#### Question 10
```
You are a system administrator for Nutex Inc. You are planning to deploy a business application using Azure virtual machines, which should meet a 99.95% service level agreement (SLA).

Which of the following should you do at a minimum?

A. Create at least two virtual machines in at least two availability zones and deploy the business application on the VMs.
B. Create a single virtual machine since the Azure service provides a 99.95% service level agreement.
C. Create a single virtual machine in a single availability zone and deploy the business application on the VM.
D. Create four virtual machines in four availability zones, each in a single availability zone, and deploy business applications on the VMs.
```
