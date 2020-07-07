# AZ-900
![AZ-900 Logo](/images/AZ-900-Microsoft-Azure-Fundamentals.jpg)


## Introduction
Azure, like Google and Amazon Cloud Platforms, is Microsoft's Cloud Platform. It is typically a platform that allows us to use Microsoft tools. It offers us virtual machines, fast data processing, analytical tools, and monitoring instruments to simplify our work. Azure pricing is also simpler and cheaper. It is commonly referred to as "Pay as You Go", meaning you only pay for the services when you are using them.

### What is Cloud Computing?
Cloud Computing is basically storing data and accessing the computers over the internet. It is the delivery of different computing services like servers, software, analytics, databases, and storage via the internet.

#### Benefits of Cloud Computing
We all know that Cloud Computing has brought a major change in the traditional business thinking for IT resources. There are many benefits of using Cloud Computing. Some of which are:
- Cost
- Scalability
- Increase Speed and Agility
- Reliability
- Security

#### The Economy of Cloud Computing
In the traditional environment of organizations, as there is a need for large investments on CapEx, Cloud is the best wayto switch to the pay-as-you-go model. Mostly in Azure, the pricing is based on an hourly basis like VMs, App Services, etc. There is also consumption based pricing which is on the basis of per execution of function, per second use of resource, or both. An example of consumption based pricing is Azure Function.

#### Technical Terms
In order to understand Cloud Computing, you need to understand some technical terms.
- **High Availability (HA)** - you get high availability for your servers by replacing instantly the failed server with the new one. HA depends on the number of VMs that you set up to eventually cover in case one goes down
- **Fault Tolerance** - Fault tolerance means that if there is any fault from the Azure side, then it is immediately mitigated by Azure itself with zero down time 
- **Disaster Recovery (DR)** - In case of any catastrophic disaster like  cyber-attack, there is a plan in DR to recover your business from these critical systems or in normal operation if such an event occurs
- **Scalability** - In cloud computing, scalability means addition or removal of the resources in an easy and quick way as per demand
- **Elasticity** - Elasticity is the capacity to dynamically extend or minimize network resources to respond to autonomous working load adjustments and optimize the use of resources
- **Agility** - Agility is the capability to adapt quickly and efficiently to changes in the business environment. Agility also refers to the ability to quickly develop, test and deploy business-led software applications

#### Types of Cloud Computing
- IaaS (Infrastructure as a Service)
- PaaS (Platform as a Service)
- Serverless
- SaaS (Software as a Service)

#### Cloud Computing Deployments Models
There are three different types of Cloud Computing: Public, Private and Hybrid.
- Public cloud is owned and operated by third parties that are providing computing services like storage, software etc.
- A private cloud is a model that uses the same legacy IT infrastructure running cloud resources within its own data center
- Hybrid Clouds integrate public and private clouds together with the technology to share data and applications. The hybrid cloud provides greater versatility and allows further deployment

### What is Azure?
Microsoft Azure is known as Windows Azure and it is a Public Cloud. It is free to build, manage and deploy applications with your favorite tools and
frames in a huge, global network. Azure is considered for offering both IaaS and PaaS. Azure offers over 100 services, from the execution of existing
applications on virtual machines to exploration of new tech paradigms like smart bots and mixed reality.

In order to use Azure, you first need to setup an Azure account directly by going to “Azure.com” or with the help of a representative. You can sign-up to
Azure as a Free account with free USD 200 credit and 25+ free services.

#### Azure Market Place
The Azure market place offers technical solutions and services from Microsoft and partners to build and extend Azure products and services. It
has all kinds of services and applications like VMs, templates, apps, and Azure managed services etc.

#### Global Footprint
Azure has more global regions than any other cloud provider — which offers the scale required to bring users around the world closer to applications.
There are 58 regions of Azure that are available around the world with 140 available in 140 countries.

### Regions
![region](/images/az-graphic-two.png)

Regions are geographical areas where Azure is present to deploy the Azure resources. It is a set of data centers with latency-defined perimeter connected
via a dedicated regional low-latency network. How to Choose a Region?
When you are choosing a region, you need to think about three things mainly:
- Location
- Features
- Price

#### Geographies/Paired Regions
Geography is a distinct market that usually conserves data residence and compliance boundaries with two or more regions within the same geographic area.
#### Availability Set
An Availability Set is a logical grouping function that can be used to separate VM resources from each other.
#### Availability Zone
Availability Zones (AZ) are locations within an Azure region that are physically separate. An availability zone is composed of one or more
independently operating power, and network data centers. Each region has a minimum of three zones.

### Azure Resource Manager (ARM)
It is an underlying service where the Azure resource deployment and management is done. It provides a management layer, which lets you create, upgrade, and uninstall your Azure subscription tools.

#### ARM Benefits
- You have group resource handlings
- You get consistency
- You can define the dependencies between resources in the right order
- Access Control, which is built-in to assign access to the users
- Tagging
- For billing, you can use tagging to stay on top

### Azure Services
There is a number of available services and features in Azure. The most commonly used categories are:
- Compute
- Networking
- Storage
- Mobile
- Databases
- Web
- Internet of Things
- Big Data
- Artificial Intelligence
- Security and Identity
- Monitoring and Management

#### Compute
In Azure, there is a number of options that are available for application and service hosting. Azure Compute provides you an infrastructure where you can run your applications.
#### Networking
The key function of Azure networking is the relation of compute resources and access to applications. There are various networking services in Azure that can be used individually or together. Azure networking provides you the most secure environment for your data as compared to any other Cloud Platform.
#### Storage
Azure Storage is a cloud storage system from Microsoft that helps to store up-to-date files. Azure Storage offers an extremely scalable data object store, a cloud file system service, a reliable message store, and a NoSQL store. Azure Storage is secure, highly available and durable, scalable, managed and accessible.
#### Data and Analytics
Data is available in all sizes and formats. When they speak about Big Data, it means they refer to large volumes of information. It often is so large that it is no longer appropriate for traditional methods of processing and analysis. To cope with these large data sets, Open Source cluster technologies have been developed. Microsoft Azure offers a wide range of Big Data and analytics tools and services.
#### Databases
Azure Database is a fully managed service. It has business-grade efficiency with integrated high availability that ensures you can easily scale and hit global distribution without needing to pay attention to costly downtime.
#### Web and Mobile
Great web experience in today's business is important. Azure provides premium support for the creation and management of web applications and HTTP-based web services. Azure builds engaging cross platforms for Android, iOS and Windows applications without any compromises that suit your business needs and reach to your customers everywhere.
#### Security and Identity
We know that safety is one thing in the cloud and it is very important to have accurate and timely Azure Security information. Azure has a wide range of security tools and features that make it the best reason to use for your applications and services. You can protect Azure identity and access management solutions for your applications and data on the front door.
#### Monitoring and Management
Azure management and governance tools help system managers and developers to secure and compliant the resources, both in-house and on the cloud. It monitors the infrastructure, software, system provision and set-up, app-updating, vulnerability detection, backup resources, disaster recovery, policy implementation, process automation, and even the management of costs— during the IT cycle.

### How to Interact with Azure
- Azure Portal
- Azure CLI
- Azure PowerShell
- Azure CloudShell

## Compute
### Virtual Machines (VMs)
Virtual machine is a server or computer created within a computer that actually behaves like a computer. It works on windows machine much like any other program, providing the same end user experience as they would be hosting the operating system itself. Each virtual machine has its own virtual hardware, including CPUs, memory, hard drives, network interfaces, and other devices.
### Features
Following are the features provided by Azure to deploy the virtual machines on their own:
- Infrastructure as a Service
- Tools
- Compliance
- Recommendations
- Choice

### Pricing
Azure charges for virtual machines on hourly basis and the resources you used. In simpler word, the more CPUs and RAMs on your VMs you use, the larger the amount you have to pay per hour 
### Use Cases
Before you create a VM, you have all the necessary information regarding the VM that includes both its pros and cons.
#### Pros
- Control
- Application
- Existing Infrastructure
#### Cons
- Not for Everything
- Maintenance
### Scale Sets
Azure virtual machine scale sets allow you to create and manage a group of load balanced VMs that are identical. Scale sets make your applications highly accessible and allow you to centrally manage, configure and upgrade a
large number of VMs.
#### Benefits
The following key benefits are offered by the scale sets:Easy to create and manage multiple VMs
- Allows your application to automatically scale as resource demand changes
- Works at large-scale
### App Services
Azure App Service is a fully managed Platform as a Service (PaaS), which means servers, networks, storage and other fundamental infrastructures are all managed and controlled by Azure; you just have to focus on business values and logics. Azure App Service is an HTTP-based service for hosting web applications, REST APIs, and mobile back-ends.
#### Features
Some key features of App Service are outlined here:
- Multiple Languages and Frameworks
- DevOps Optimization
- Global Scale with High Availability
- Connections to SaaS Platforms and On-premises Data
- Security and Compliance
- Application Templates
- Visual Studio Integration
- API and Mobile Features
- Serverless Code
#### App Services Categories
Azure App services divided into three main categories:
- Web Apps
- Web Apps for Containers
- API Apps
### Azure Container Instances (ACI)
Containers become the preferred way for cloud applications to be packaged, deployed and managed. Azure Container Instances is the simplest and fastest way to run a container in Azure without having to manage any virtual machines and without having to follow a higher-level service.
#### ACI Features
- Manage Application Dependencies
- Less Overhead
- Increased Portability
- Efficiency
- Consistency
#### Container in Azure Workflow
The workflow to using a Container in Azure is following:
- Software Development Cycle
- Application Placed in Container
- Azure Container Instances
#### Benefits of ACI
Azure Container Instances (ACI) have following benefits:
- Run containers without managing servers
- Increase agility with containers on demand
- Secure applications with hypervisor isolation
- Works with your favorite tools
### Azure Kubernetes Service
Kubernetes is an open-source container orchestration system for automating application deployment, management, and scaling. **Azure Kubernetes Service (AKS)** enables the simplest deployment of a managed Kubernetes cluster in Azure. AKS eliminates the complexity and operating overheads of Kubernetes management by offloading many responsibilities to Azure. The masters of the Kubernetes are managed by Azure. Only the agent nodes are managed and maintained by you. As a
managed Kubernetes service, AKS is free; you only pay for the agent nodes within your clusters, not for the masters.
#### Azure Container Registry (ACR)
ACR is a service that keeps track of current valid container images. It manages files and artifacts for containers. When your Azure container instances and Kubernetes service need to create a new container, the images
come from ACR. 
#### AKS Cluster Architecture
Azure Kubernetes Service cluster architecture is based on the following main components:
- Node
- Node Pools
- Pods
### Azure Functions
Azure Function is smallest compute on Azure. It is a single function and an easy way to run small pieces of code or "functions" in the cloud. Functions can make development even more productive, and you can use your development language of choice, such as C#, Java, JavaScript, PowerShell, and Python. Azure Functions is the serverless computing service that is hosted on the public cloud of Microsoft Azure.
#### Features
Here are some key features of Functions:
- Choice of your language
- Pricing Model for Pay-per-use
- Integrated Security
- Simplified Integration
- Open-source

## Networking
Azure networking is considered as the key component in building a successful public cloud into Microsoft Azure and its fundamental part. The networking service of Microsoft Azure not only provides the connectivity toward users, it also serves as connectivity between the service elements.
### Virtual Network (VNet)
A Virtual Network (or VNet) is used as a networking service to host the infrastructure resources within Microsoft Azure. It is the most essential part of the Azure network. It is a logical isolation of the Azure cloud dedicated to
your subscription. You can use VNets to provision and manage virtual private networks (VPNs) in Azure.
#### IP Address
Each traffic has its own IP address, which ensures that traffic delivers to the right destination (server). An IP address serves two main functions: network interface and address.
#### Address Space
An address space is the range of IP addresses.
#### Subnets
A subnet is a feature that enables segmentation.
#### Subnet Regions
Each virtual network within Azure belongs to a single region
#### Subscription
Each virtual network has only one subscription and every subscription has multiple virtual networks.
#### Cloud Advantages
- Scaling
- Isolation
- Security
- High Availability

### Load Balancer
A load balancer is used in front of two VMs to access the data before reaching the destination. Therefore, multiple users can access the service at the same time more efficiently. Load balancer, in general, is used to distribute the traffic arrived on the front end to the backend pool as per rules and health status. The two types of load balancers are public and internal. Public load balancer converts the private IP address of VM to public IP address for outbound access and internet-facing. Whereas, internal load balancer is capable of managing the traffic inside the VNet.
#### Benefits of Load Balancer
- Internet Traffic
- Internal Network
- Port Forwarding
- Outbound Traffic

### VPN Gateway
![VPN](/images/vpn.png)

VPN Stands for Virtual Private Network, a VPN gateway is useful for establishing the private connection between Azure resource and an onpremises environment, offices, the cloud or other premises within the cloud in order to establish a private secure connection. In Microsoft Azure, VPN gateway provides the managed services within the cloud.

Virtual Network Gateway 
VPN gateway is a specific type of virtual network gateway. A virtual network
gateway is composed of a number of Virtual Machines (VMs) within the
specific subnet called Gateway Subnet.
Components of VPN Gateway
The main components of the VPN gateway consist of Azure VNet, VPN
gateway, VPN tunnel, and on-premises services. Within Azure VNet, there is
a VPN gateway present.
Application Gateway
One type of VPN gateway is the application gateway. It is considered as the
most advanced load balancer that enables the balancing of web traffic to
manage the web applications using an HTTP request. Because of its services,
the gateway is called layer 7 load balancer within Microsoft Azure.
Benefits of Application Gateway
Scaling
High Availability
Encryption
Zone Redundancy
SSL Offload
Multi-Site hosting
Cost effective
Session affinity
Web Socket Support
Web Application Firewall
Content Delivery Network
It is a distributed network of servers that can deliver web content close to
users. Within Azure, CDN places the duplicates of data at the datacenter
present closer to the user side and users can easily log into the application,
which they want.
The main reason behind the use of Content Delivery Network (CDN) is to
deliver data to the user with the lowest latency by providing data that is
present at edge nodes.
Benefits of CDN
Global Coverage
Better Performance
Scaling
Distribution