# Exam AZ-900 : Microsoft Azure Fundamentals

## Describe core Azure Services

---

### 1. Describe the core Azure architectural components

Azure resources are components like storage, virtual machines, and networks that are available to build cloud solution :
- Virtual Machines
- Storage Accounts
- Virtual Networks
- App Services
- SQL Databases
- Functions

We have also resource groups which is a container to manage and aggregate resources in a single unit.
The Azure Resource Manager (ARM) provides a management layer that enables you to create, update, and delete resources in your Azure subscription.

### 2. Describe core resources available in Azure

| Service                         | Description                                                                                                                                                         |
|---------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Virtual Machines                | This is a software emulations of physical computers                                                                                                                 |
| Azure App Services              | Fully managed platform to build, deploy, and scale web apps and APIs quickly                                                                                        |
| Azure Container Instances (ACI) | Runs a container in Azure without the need to manage a VM or Additional Services                                                                                    |
| Azure Kubernetes Service (AKS)  | Orchestration service for containers with distributed architectures and large volumes of containers                                                                 |
| Windows Virtual Desktop         | This a desktop and app virtiualization that runs in the cloud                                                                                                       |
| Virtual Networks                | Enables Azure resources to communicate with each other, the internet, and on-premises networks                                                                      |
| VPN Gateway                     | Used to send encrypted traffic between an Azure virtual network and an on-premises location over the public internet                                                |
| ExpressRoute                    | Extends on-premises networks into Azure over a private connection that is facilitated by a connectivity provider                                                    |
| Container (Blob) Storage        | Optimized for storing massive amounts of unstructured data                                                                                                          |
| Disk Storage                    | Provides disks for VM, applications, and other services to access and use                                                                                           |
| File Storage                    | Sets up a highly available network file shares that can be accessed by using the stander message block protocol                                                     |
| storage tiers                   | Change type of access tiers (hot / cool / archive)                                                                                                                  |
| Cosmos DB                       | Distributed database service that elastically and independently scales throughput and storage                                                                       |
| Azure SQL Database              | relational database as a service based on the latest stable version of SQL Server database enginer                                                                  |
| Azure Database for MySQL        | Fully-managed MySQL database service for app developpers                                                                                                            |
| Azure Database for PostgreSQL   | Relational database service based on the open-source Postgres database engine                                                                                       |
| SQL Managed Instance            | Allows existing SQL Server customers to lift and shift their on-premises applications to the cloud with minimal application and database changes                    |
| Azure Marketplace               | Allows customers to find, try, purchase, and provision applications and services from hunders of leading service providers, which are all certified to run on Azure |

[Previous](01-CLOUD.md) **|** [Next](03-TOOLS.md)