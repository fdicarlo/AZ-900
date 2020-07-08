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
#### Virtual Network Gateway 
VPN gateway is a specific type of virtual network gateway. A virtual network gateway is composed of a number of Virtual Machines (VMs) within the specific subnet called Gateway Subnet.
#### Components of VPN Gateway
The main components of the VPN gateway consist of Azure VNet, VPN gateway, VPN tunnel, and on-premises services. Within Azure VNet, there is a VPN gateway present.
### Application Gateway
One type of VPN gateway is the application gateway. It is considered as the most advanced load balancer that enables the balancing of web traffic to manage the web applications using an HTTP request. Because of its services, the gateway is called layer 7 load balancer within Microsoft Azure.
#### Benefits of Application Gateway
- Scaling
- High Availability
- Encryption
- Zone Redundancy
- SSL Offload
- Multi-Site hosting
- Cost effective
- Session affinity
- Web Socket Support
- Web Application Firewall
### Content Delivery Network
It is a distributed network of servers that can deliver web content close to users. Within Azure, CDN places the duplicates of data at the datacenter present closer to the user side and users can easily log into the application, which they want.
The main reason behind the use of Content Delivery Network (CDN) is to deliver data to the user with the lowest latency by providing data that is present at edge nodes.
#### Benefits of CDN
- Global Coverage
- Better Performance
- Scaling
- Distribution
## Storage
### Storage Account
A Storage Account is like an access point for Azure Storage. All of your Azure Storage Data Objects like blobs, files, queues, tables, and disks are on an Azure storage account. The storage account provides a unique namespace for your Azure Storage data, which is available via HTTP or HTTPS from anywhere in the world.

It is written in the format: https://**Storage-Account-Name**.**Storagetype**.core.windows.net

Two types of storage accounts are available. Users have access to Blob Storage, Table Storage, Queue Storage, and File Storage through the "Standard" storage account. The alternative is a "Premium" account, which is a new option that allows users to save data on SSD drives to boost I/O capacity.

There are 5 different types of storage account available that depends on different features and pricing. These are:
- General-purpose v2 accounts
- General-purpose v1 accounts
- BlockBlobStorage accounts
- FileStorage accounts
- BlobStorage accounts

### Azure Storage
Azure Storage is a Microsoft Cloud storage for storing data. It is a highly scalable object store and a message store for messaging. It also offers file system service. It is a NoSQL store that provides a number of benefits like:
- Durability
- High Availability
- Security
- Accessibility
- Scalability

### Blob Storage
Blob means Binary Large Object, which is used for storage of Binary or text data. It is used for storage of huge amounts of data. 
In Azure, three types of Blobs are supported:
- Block blobs store text and binary data up to 4.7TB
- Append blobs are used for log data and can be up to 195GB in size
- Page blobs are used for frequent read and write operations on data.
- It sizes up to 8TB

During the time of creation, you need to select the type of a storage account, which is based on different pricing options. These are:
- Hot Tier
- Cold Tier
- Archive Tier
### Disk Storage
It is a disk to which you can store your data. A managed disk is the disk that is attached to your VM. Here, managed means that Azure will look after this disk for you and managed the uptime and backup. There are four different types of disk:
- HDD
- Standard SSD
- Premium SSD
- Ultra Disk
### File Storage
With File Storage, you get the following benefits:
- Share files across multiple Azure machines and be able to connect with the on-premises infrastructure;
- It is fully managed and you do not need to worry about OS or hardware;
- Highly available with super resistance against outages
- Built-in redundancy
### Archive
Azure Archive Storage is used generally for archiving data and paying less for it. Most of the company’s policies, legislations and recovery scenarios storing a large amount of archive data is required, so Azure Archive service can prove to be really handy for them. It is one of the lowest priced storage in Azure, which means you can store terabytes of data in just few dollars per month.
## Databases
There are multiple Azure Database Services provided by Azure, which are:
- Cosmos DB
- Azure SQL
- Azure Database for MySQL
- Azure Database for PostgreSQL
### Cosmos DB
Cosmos DB is a global service provided from the beginning. With Cosmos DB, you can put the data closest to the user. This is one of the key features with great user experience as well. To put the databases at multiple locations can be such a difficult thing with synchronization but with Cosmos DB, Azure takes care of this synchronization for you. All the data stored in Cosmos DB are encrypted at rest or in motion.
#### Latency
Latency is the time taken by the data to travel.
#### Scalability
With Cosmos DB, you can scale your database automatically to infinity when the requirement goes up in order to meet the resources.
#### Connectivity
With Cosmos DB, you can work in various ways like you can choose from multiple built-in ways in order to connect to Cosmos DB such as SDKs or APIs. You can also use different languages such as C#, Java or Node.js.
### Azure SQL
It is a managed Database as a Service, as another service in Azure takes care of hardware and IaaS levels. A cloud-based Database Management System (DBMS) is provided in the Microsoft Azure SQL Database. With Azure SQL, you can easily migrate your on-premises SQL database to Azure SQL and get benefits of that. With Azure SQL, you can store 100TB of data within a minute.
#### Integrated with ML
With Azure SQL, you can also take advantage of integrated Machine Learning tools.
#### Scalability
As it is a cloud based service, it also offers excellent scalability through which you get high availability. And, it gives 99.995% availability.
#### Security
With Azure Cloud Platform, security is a built-in feature that gives you benefit in terms of security of your data.
### Azure Database for MySQL
Azure Database for MySQL is the database built-in by the community while Azure SQL is Microsoft’s product. Azure MySQL platform provides a fully managed, business-ready MySQL cloud database. Azure Server for MySQL was designed to provide high availability with 99.99% SLA and does not require additional setup, replica features or costs to guarantee that your apps run as necessary. It has automated batching and backup with monitoring. All of these are included without any cost. Azure database for MySQL is PaaS, which is managed by Microsoft.
### Azure Database for PostgreSQL
It is an open source relational database similar to MySQL. It is a defaultdatabase from MacOS. It is good for mission-critical workloads with predictable performance, security, high availability, and dynamic scalability.
#### Features
- You can integrate this database with lots of extensions like JSONB (Binary version of JSON), and integration with code like Ruby, Python, etc.
- Horizontal scaling
- It has a feature that detects the disruptive events that effect performance on which you can perform actions
- Similar to Azure Database for MySQL, it also offers fully managed database services like automatic patching, automatic backups, and built-in monitoring
### Database Migration Service
In Azure, you have a dedicated tool for migrating databases from onpremises to Azure. With a single tool, you can move your existing SQL server; there is no need to use multiple tools. The Azure Server Migration Service is a fully managed program that permits smooth migration to Azure Data systems with minimal downtime from various server providers.
The service is currently available in general, with ongoing efforts for growth focused on:
- Reliability and performance
- Addition on source/target pairs
- For friction, free migration used for continuous investment
## Authentication & Authorization
Authentication and Authorization in Azure includes:
- **Identity Services**: Identity services identify the platform for the user and ensures user validations for the application;
- **Azure Active Directory**: This directory service is able to provide access and control of access to users with different directory services;
- **Multi-Factor Authentication**: Provides security features by getting multiple information about the user for authentication.
### Identity Services
When any user uses an online service that has any privacy criteria, then the user requires at least a username (that is the User ID) and password. Identity services include authentication, authorization and access management policies.
#### Authentication
Authentication is a way of identifying the user with the help of a user ID and password from the database.
#### Authorization
Authorization is the process that is conducted after authentication. It finds which kind of data access is available for the authenticated user.
#### Access Management
Access management is a critical part of any cloud infrastructure as it ensures the restriction of access to service toward other users. It provides confidentiality, integrity, and availability.
Access management policies should also be responsible for the following:
Authentication and Authorization
Faraway from Unauthorized Users
### Azure Active Directory
Azure Active Directory (AAD) is the main tool to manage and monitor the dedicated users’ information present in Microsoft Azure.
#### Active Directory
Active Directory (AD) is a directory service formed by Microsoft for the storage of information about the user, resources and other things present in the network. AD is commonly used in offices, educational institutes, and management departments.
#### Azure Active Directory
Azure Active Directory (AAD) is different from the Active Directory (AD). AD provides its directory service to those companies who designed this service. Whereas, Azure Active Directory services are available for everything present on Azure. It is the first service given when a user creates an account in Azure.
#### AAD Services
- Mandatory Service: Users on Microsoft Azure are unable to create an account without AAD services
- First User: Every Azure account has the first user and owner. To become an Azure user, AAD service is needed
#### Tenant
A tenant is the representation of an organization in Azure. A tenant is a dedicated instance of AAD service. It is the first ADD service when a user creates an account in Azure.
#### Subscription
All Azure services require subscription in order to get access to using Azure resources and services.
#### Hybrid Cloud Architecture
Within a hybrid cloud architecture, there are some services present onpremises and some services hosted on the cloud. When a user wants to set the hybrid cloud infrastructure, AAD instance can be used in hybrid cloud architecture.

There are several services that AAD uses on Azure for management purposes.
### Multi-Factor Authentication
Multi-Factor Authentication (MFA) provides a layer-based authentication using more than one form of authentication. MFA is recommended as a default. It is a part of AAD that enables other ways to authenticate users.
#### How MFA Works
Multi-Factor Authentication (MFA) conducts the authentication of the user in multiple steps. The first step is to verify the user with a user ID and password. The second step is to send a code on the user’s phone for further
verification. The third step is the biometric verification. This step is optional.

## Azure Solutions
### Internet of Things
The Internet of Things (IoT) is a collection of interconnected computing devices, mechanical and digital machines, objects, or individuals. Azure Internet of Things (IoT) is a collection of cloud services managed by Microsoft, which connects, monitors, and controls billions of IoT assets.

There are many IoT related services that the Azure offers to help you out. Two of the main IoT services are described here.
#### IoT Hub
IoT Hub is a cloud-hosted, managed service that serves as a central hub, which collects the data feeds from all devices. It is for bi-directional communication between your IoT application and the devices it manages. Features:
- Scaling
- Securing
- PaaS
- Integrating
- Ease of Deployment
#### IoT Central
Azure IoT Central is a fully managed, highly scalable IoT SaaS solution that reduces the complexity and costs of developing, managing and maintaining IoT solutions of an enterprise-grade nature. Its user-friendly interface allows easy monitoring of device requirements, developing guidelines, and managing millions of devices and their data over
their life cycle.
### Big Data
Big Data is a term used to describe the collection of millions of data that is large in size and keeps growing exponentially over time. Big data in terms of business value is used for better service, better products and more profits. In Azure, there are many services and tools that deals with Big Data, some of them are defined below:
- **Azure Data Lake Analytics**:Azure Data Lake Analytics is an on-demand job analytics service that simplifies big data. In Data Lake analytics, there is parallel processing which means that same data is processed by two or more processors at the same time.
- **HDInsight**: Azure HDInsight is Microsoft's cloud-based big data analytics service, which helps organizations process large amounts of streaming or historical data. Azure HDInsight allows storing massive amounts of data easily, efficiently and cost-effectively.
- **Azure Databricks**: Azure Databricks is an analytics platform based on Apache Spark, which is an open source cluster computing framework to enhance the Microsoft Azure platform. Databricks run and process a dataset on many computers simultaneously. When using Databricks, you do not need a lot of computers nor its maintenance.

#### Big Data Outcomes
Collectively, the services of big data can bring the following outcomes for you. These are:
- Speed
- Cost Reduction
- Better Decision Making
- New Products and Services
- Artificial Intelligence

Artificial Intelligence (AI) is the capability of a machine to imitate intelligent human behavior. In the Microsoft, AI is often called Machine Learning or AI is the sub-category of Machine learning, although AI and Machine learning
are often placed in the same bucket. 

Microsoft focuses on three main parts to how machine learning can be used on the cloud platform.
- Models
- Knowledge Mining
- Built-in Apps
#### Azure Cognitive Services
Cognitive services bring AI within every developer's reach — without requiring expertise in machine learning. All it takes is an API call to embed the feature to see, hear, speak, search, understand, and accelerate decision making into your apps.
#### Azure Machine Learning Studio
The Azure Machine Learning Studio is the top-level tool for the machine learning service. It is visual tool through which you can manage all of your needs for ML. It provides a centralized location for data scientists and developers to work with all the artifacts for developing, training, and deploying machine learning models.
#### Machine Learning Services
- End-to End Service
- Tooling
- Automation
### Serverless
Serverless is such an important part of modern cloud computing. Serverless model allows developers to build applications faster by eliminating the need for them to manage the infrastructure. It is an extreme PaaS. The cloud service provider automatically offers, scales, and manages the infrastructure required for running the code with serverless applications. Benefits of Serverless Model:
- No Infrastructure Management
- Dynamic Scalability
- Faster Time to Market
- More Efficient Use of Resources
#### Azure Functions
Azure Functions is the compute component of serverless services offered by Azure. It is called function as it has a single task to perform every time. Meaning that you can use Functions to write code without having to worry about deploying that code or creating VMs to run your code.
#### Azure Logic Apps
Azure Logic Apps is a cloud service that connects the systems both inside and outside the Azure Platform; you can integrate apps, data, and services or even an entire system across organizations. With this, you can automate, and
orchestrate business processes, tasks, activities, and workflows.
#### Azure Event Grid
An event, in a computing concept, it is an action or occurrence that can be identified by a program and has significance for system application. Azure Event Grid lets you easily build applications with event-based architectures. Event Grid has built-in support for events such as storage blobs and resource groups, coming from Azure services.

Event Grid connects data sources and event handlers. You can use Event Grid to trigger a serverless function that analyzes images when added to a blob storage container.
### DevOps
DevOps is a combination of the terms development and operations, meant to reflect a collective or cooperative approach to the activities performed by the application development departments of an organization and IT operations.
#### Azure DevOps
Azure DevOps offers developer tools to support teams in preparing projects, working on application creation, and designing and deploying new products. Depending on your business needs, you may use one or more of the following services:
- Azure Boards
- Azure Pipelines
- Azure Repos
- Azure Test Plans
- Azure Artifacts
#### Azure DevTest Labs
Azure DevTest Labs helps team developers handle Virtual Machines (VMs) and PaaS tools effectively, without waiting for approvals. It focuses in the environment management. With this, developers and engineers are allowed to create an environment for test and development.

## Security
Security is a set of policies or rules, which allow the traffic to be directed to the network in the right way. Security of the network is very important, especially when there is a communication of infrastructure with the internet.
### Securing Network Connectivity
The networks on Azure give access to everything for users. All the resources and services of Microsoft Azure are connected to a network to provide communication between users, processes and other services.

In order to achieve optimum network performance, secure network connectivity is very important.
#### Azure Firewall
An Azure firewall is a crucial service that protects and safes the network from unwanted traffic load.
- Rules
- Variation
- Compulsory Bit
#### Distributed Denial of Service Attacks (DDoS)
Distributed Denial of Service (DDoS) is the most common attack on services attached to the internet. It occurs when a huge number of request from multiple sources come constantly in order to interrupt the server normal working.
##### DDoS Protection Service
- **Target a Website**: A lot of servers target the same website or computer in order to stop its working. For example, GitHub was a target with 127 Mb requests every second
- **Azure Protection Service**: Microsoft Azure has protection service against DDoS attacks. This service has a different level of protection services depending upon the user needs of the application. Azure protection service detects DDoS attacks and work against it
- **No Halt**: Azure Protection service would not interrupt the routine process of other services on the website due to Azure global presents
#### Network Security Groups
The security group provides a secure management environment for the network. Network Security Group (NSG) is required in the configuration of a Virtual Network (VNet) where different Virtual Machines (VMs) within the subnet are connected with each other.
#### Application Security Group
Application Security Group (ASG) protects the application running on that particular VM or subnet in the network. ASG provides the security of application and NSG provides the security of traffic flow.
### Azure Security Center
Azure Security Center allows users to monitor the security features for Azure resources and on-premises as well. Azure Security has itself a portal within the Azure portal known as Azure Security Center. Azure Security Center indicates a threat alert that Azure detects and finds a way to protect its users from. Azure Security center works in a hybrid cloud infrastructure as well.
#### Sections in Azure Security Center
Each section in the Azure Security Center portal shows an individual performance behavior of security features in graphical representation.
- Policy, Compliance, and Subscription Coverage
- Integrate with Other Cloud Providers
- Alerts for Resources Security
- Networking
##### How to use the Security Center?
To take advantage of Azure Security Center for the security of cloud infrastructure, Azure users need to follow these three-step process:
- Define Policies
- Resource Protection
- Response
### Key Vault
To hide the key password and other information, Microsoft gives you a service known as Azure Key Vault. It is the best option for key storage. With Azure Key Vault, you can share your secrets with others without revealing the actual secrets. Azure Key Vault is present in the storage account of VMs. Azure Key Vault has a number of key features, some of which are:
- Secure Hardware
- Application Isolation
- Global Scaling
### Azure Information Protection
Azure Information Protection (AIP) provides a way of protected sharing of resources. Azure Information Protection enables the sharing of files, documents and sensitive information inside and outside Azure while maintaining full control over that data. Microsoft 365 takes full advantage of Azure Information Protection service.
### Advanced Threat Protection (ATP)
Advanced Threat Protection (ATP) is the advance and secure option for providing the security of the links as compared to the standard one. It gives an extra layer of security and management of the users in order to make a
more secure and protected system. Azure Advanced Threat Protection (ATP) has a number of features that provide the safety of links and analyze the security threats.
- Monitor Users
- Supervised User’s Behavior
- Propose Changes
#### Cyber-Attack Kill-Chain
The cyber-attack kill-chain is a chain of phases that define how an attack is prepared and execute. This deployed model allows detecting and reacting upon the attack. The model reveals seven stages according to which reaction and detection on cyber-attack are available.

## Privacy, Compliance, and Trust
We all know that most of the companies use the Azure platform for its agility to make it easier for the developers to create, manage, update and delete the resources as per requirement. However, sometimes unwanted access to the resource may cause unintended cost consequences. In order to overcome this, Azure provides a solution of resource access governance, which is the process of managing, monitoring and auditing the resource usage in order to meet the goals and requirements.
### Azure Policy
Azure Policy is used to create policies in Azure. With Azure Policy, you can manage and assign policies to the resources with multiple rules, so that specific resources are complaint with your business standard and SLAs.
Azure Policy is a default allow and explicit deny system.
### Role-Based Access Control (RBAC)
Role-based Access Control is one of the critical components in the governance of uses and access to Azure resources. With RBAC, you can outline fine grained access management to the resources. You can also define specific user access to an individual resource like what they can do with that specific resource and in what specific area of resource they have access.

RBAC works by assigning roles to users and this role assignment is based on three elements, which are:
- Security Principal 
- Role Definition
- Scope
#### Role Assignment
Role Assignment is the process of combining all these together to grant proper action to Azure resources. Access is granted by the creation of a role assignment and deleted by the deletion of that role assignment.
#### Locks
It is a simple tool to manage the changes and remove resources. It is used for the resource which you do not want to change or delete.
### Azure Blueprint
It is a template for creating Azure resources. Everything you need to deploy in the standard cloud environment of Azure is defined in the blueprint.
### Azure Advisor for Security Assistance
Azure Advisor is a separate portal within Azure that has Security Assistance as a part of the Azure Security Center.
### Azure Monitor
In order to improve your Azure experience, Azure Monitor uses the telemetry data. Azure Monitor maximizes flexibility and application efficiency by offering a comprehensive solution to capture, monitor, and use the cloud and on-site telemetry. It helps you understand how your applications operate and detect problems and the resources on which they depend proactively.
#### Outcomes
The outcome of using Azure Monitor:
- Maximize Performance
- Maximize Availability
- Identify Issue
### Azure Service Health
Whenever there is a plan of maintenance or service incident, you get notified about it with the use of Azure Service Health. With Azure Service Health, you get notified about the planned or unplanned maintenance of the platform.
It has the following features:
- Dashboard
- Custom Alerts
- Real-time Tracking
- Free Service
### Compliance
The general principle that cloud services deliver must adhere to the requirements faced by cloud customers is strongly compliant. This is a very important issue with new cloud computing services, and many IT professionals are looking at it very thoroughly. There are different standards and regulations that cloud customers need to comply. Compliance is not
negotiable.
#### Industry Compliance
This refers to the legislation and rules the industry, in general, has to complywith. The most common three legislations and rules are:
- General Data Protection Regulation (GDPR)
- ISO Standards
- NIST
#### Azure Compliance Manager
For compliance in Azure, Azure Compliance Manager is available, because Azure knows about compliance and about your resources, so it combines the tools and gives you a recommendation as per that.
#### Azure Government Cloud
Azure Government Cloud, if you are US government body or are contracted for one, then you can get access to Azure resources in Azure Government Cloud regions. They are separate dedicated datacenters.
#### China Region
It is the second specific region when it comes to compliance. As a country, China has very specific and strict requirements when there is data, internet, or online entities, so when you need to provide cloud services here, you have to use the China region in Azure. This means that Azure has physically separated datacenters located in China without any connection to the other regions of Azure.
### Privacy
Privacy is an extension of compliances. In Azure, privacy is the core power of the platform so there is no single service or place for it.
### Trust
In Azure, there are two services in terms of Trust. One is Trust Center and theother is Service Trust Portal. Trust Center is a shortcut of knowing all the things that Microsoft does to make sure that you do not lose trust in Azure
and other services.

Service Trust Portal is a location to review all the independent reports about Azure. It is a portal of proof that they are compliant with many millions of different standards and certifications.

## Pricing
Azure pricing depends upon the following criteria:
- Pay for the resources you access
- Pay for the number of hours you use
- Pay depending upon the size of the resource
- Service payment is tiered
- Pricing as per the location of service
### Subscriptions
The pricing structure of Microsoft Azure works on a subscription price that is tied to what you are using within the Azure infrastructure. All resources in Azure resides within the subscription, you cannot access any resources until you are subscribed. Once you sign up for Azure, you immediately get an Azure subscription, and all the services you create are created within that subscription.

Subscription in Azure can be defined as:
- Multiple Subscriptions
- Billing Admin
- Billing Cycle
#### Offer Types
At any given time, Azure has a lot of active offer types. You can get the offer depending upon your subscription type.
##### Management Groups
Management Groups is a very useful feature on Azure when it comes to subscription. Management groups may indicate the following:
- Group Subscriptions
- Organize
- Billing Logic
### Cost Management
We know that when resources and services are running, its cost management can be quite an expensive task. When you use resources or services in Azure, you need to buy them because without that, you cannot use it. You need a service that automates the cost management because tracking of every single cost is such a difficult thing to do. The management of cost in Azure can be done in many different ways; some of these are given below:
#### Azure Free Account
If you have never had a free Azure trial and have never been a paying Azure user, then you are eligible for a free Azure account. 
#### Azure Cost Management
Azure Cost Management is a handy tool in Azure that allows the study of your costs on a granular level. Cost management allows you to create a budget for your Azure expenses, set up configurable notifications as so you will know if you are hitting a budgeted limit and evaluate your costs in detail.
### Pricing Factors
Pricing in cloud computing is very tricky to predict and calculate. Any Azure account has a lot of resources such as networks, connections, virtual machines, firewalls, storage accounts, functions, etc.

The primary factors influencing costs are the size of resources, type of resource, the Azure regions you are using, and the bandwidth.
#### Pricing Calculator
The Azure pricing calculator helps you get an estimate of costs depending on the products that you plan to use, as well as where those products will be deployed, and so on.
#### Total Cost of Ownership (TCO) Calculator
The pricing calculator is helpful for estimating your expenses for new applications in Azure, but if you have on-premises applications that you want to migrate to Azure and you want an estimate of how much you can save, the
TCO calculator is a better choice.
### Best Practices for Minimizing Azure Costs
In order to implement cost control effectively and reduce costs, you need to:
- Be equipped with the right tools for performance
- Be responsible for costs
- Take appropriate action to reduce expenses
#### Spending Limits
Azure spending limits are the recommended in order to prevent you fromspending over your credit and manage your Azure subscription's total spending.
**Default Limit**: Some Azure accounts with monthly credits, will have default spending limits. This could be 0$ for a free account and 150$ for Microsoft subscription account.
**No Increase**: When the credits are gone, either remove the spending limit entirely or leave it in effect.
**No Spending Limit**: Pay-as-you-go subscription has no spending limit functionality.
#### Quotas
A quota is the limit on certain properties of an Azure service.
#### Tags
Tags are non-functional labels attached to resources or resource groups in order to manage the cost of resources. You can attach as many to each resource as you want.

Some common best practices for using tags are:
- Identify Roles
- Related Resources
- Filter
- Unambiguous
#### Reserved Instances
With Reserved Instance, you are allowed to prepay for the virtual machine or SQL Database computing capacity for one or three years.
#### Azure Advisor
Azure Advisor is a tool that detects the low-usage virtual machines from a CPU or network cost standpoint. From there, you can choose to either shut down or resize the system to continue running the machines, based on estimated costs.

## Support
### Plans
Microsoft offers numerous support plans for Azure customers in order to find right level of support for your organization. There are five different support plans available in Azure: Basic, Developer, Standard, Professional Direct, and Premier. Choosing the right plan is a balance between how much access you need for help and support and how much you are willing to spend. The things, which are included in all support plans are:
- 24/7 Access
- Online Self-Help
- Forums
- Azure Advisor
- Service Health
### Tickets
To contact a support there is medium called “Tickets”. Tickets are what the enquiry issue makes support. A ticket is usually a number that uniquely identify your enquiry.
### Channels
Azure supports various channels that are free to everyone through which you get more help from Azure. The support channels are:
- Azure Documentation
- Forums
- Social Media
### Knowledge Center
Knowledge center is the place of a common Azure knowledge. In knowledge center, you can find basic questions that are common for all those who are new to Azure, these questions are called Common questions.
### Service Level Agreement (SLA)
When you are using Azure Services, you need some form of guarantee that the service will be running stably. This is called Service Level Agreement, which helps to ensure the services you are subscribed for is available to you as mentioned in the agreement.

Some properties of SLAs are:
- Confidence
- Contract
- Multiple SLAs
- Complex
- Mandatory
### Service Life Cycle
Every product and the service in Azure has its lifecycle known as Service Lifecycle. Azure is an always-changing environment, and new services are always being introduced.

It is important to understand the service lifecycle in Azure, how you can keep up with changes, and how a service’s lifecycle might impact your support and your SLA.
#### Gathering Customers Data
When the services are developed by the Microsoft for the Azure platform, it is necessary to ask questions to customers regarding the new features before adding. This act can save large investments if the services fail.

There are two main stages in Service Life Cycle:
- Preview
    - Private Preview
    - Public Preview
- General Availability