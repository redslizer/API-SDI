#**Integrating API orchestration and Security protocols for a robust Smart Digital Infrastructure**
- Creation and testing of frontend API's for seamless functionality of underlying architecture 

##**Creation of GitHub Repositories** 
1. Log in to GitHub
   Navigate to [GitHub](https://github.com) and log in to your account.

2. Go to the Repositories Tab
   On your GitHub homepage, click the "Repositories" tab or use the "+" icon at the top-right corner of the page to open the "New repository" option.

3. Create New Repository  
   - Click on the "New" button next to your repositories list.
   - Fill in the repository details:
     - Repository name: Choose a unique and descriptive name. In this case "IoT1-API-Front-End".
     - Public or Private: Select if the repository should be publicly available or private.
     - Initialize with a README: Check this option if you'd like GitHub to generate a basic `README.md` file. It is a good practise       include a README file.
     - Add contributors and with access controls in a team.

4. Create Repository  
   - Once the details are filled in, click the "Create repository" button.  
     new GitHub repository is now created!

##**Structuring of GitHub Repositories**
  - Plan and structure the Repositories in the GitHub
   -IoT1-API-Front-End/
    |--.github/
    |   |--ISSUE_TEMPLATE/       \\templates for reporting bugs
    |   |  |--bug_report.md
    |   |  |--feature_report.md  \\requesting features
    |   |--workflows/
    |   |  |--ci.yml             \\workflows for automated testing
    | 
    |--docs/
    |   |--README.md  \\main documentation file with project overview
    |   |--setup.md   \\detailed setup instruction
    |
    |--src/                      \\source code library
    |  |--main/                  \\ main application code
    |  |  |--javascript/
    |  |      |--com/
    |  |         |--example/
    |  |             |--app.js    \\ javascript source files
    |  |--test/                   \\test code
    |      |--javascript/
    |          |--com/
    |             |--example/
    |                 |--appTest.js  \\javascript test files
    |--.gitignore.md                 \\files & directories to be ignored by git
    |--README.md                     \\ main readme file at root level
    |--LICENSE                       \\ license for the project
    |--CONTRIBUTING.md               \\ guidelines for contributing to the project

##**Learning Azure basics**
1. Introduction to Azure
Azure is Microsoft's cloud computing platform, offering a wide range of services such as virtual machines, databases, and AI tools. It allows for flexible, scalable, and secure infrastructure to deploy applications and services globally.
   Key Benefits:
   - Global infrastructure
   - Pay-as-you-go pricing model
   - High availability and redundancy
   - Integration with Microsoft tools and products

2. Azure Services Overview
   - Compute: Virtual Machines (VMs), App Services, Azure Kubernetes Service (AKS).
   - Storage: Blob Storage, Disk Storage, File Storage.
   - Networking: Virtual Networks, Load Balancers, Traffic Manager.
   - Databases: Azure SQL Database, Cosmos DB, Azure Database for MySQL/PostgreSQL.
   - AI & Machine Learning: Cognitive Services, Azure Machine Learning.
  
3. Azure Management Tools
   - Azure Portal: A web-based interface for managing Azure services.
   - Azure CLI: A command-line tool for automating Azure tasks.
   - Azure PowerShell: A scripting tool to manage Azure resources.
   - Azure Resource Manager (ARM): Enables the management of resources through templates.

4. Networking in Azure
   - Virtual Networks (VNet): A logically isolated network in Azure.
   - Network Security Groups (NSGs): Control inbound and outbound traffic to resources.
   - Load Balancer: Distributes traffic among virtual machines for high availability.
   - VPN Gateway: Enables secure communication between Azure and on-premises networks.

5. Azure Storage
   - Blob Storage: Object storage solution for unstructured data.
   - File Storage: Fully managed file shares in the cloud.
   - Disk Storage: Persistent storage attached to virtual machines.
   - Azure Data Lake: A scalable data storage solution for big data analytics.

6. Azure Security
   - Azure Security Center: Provides a unified view of security across all Azure resources.
   - Azure Firewall: Network security service to protect Azure Virtual Networks.
   - Azure DDoS Protection: Defends against distributed denial-of-service attacks.
   - Azure Key Vault: Safeguards cryptographic keys and secrets.
 
###Additional 
   - Explore hands-on labs or tutorials.
   - Consider earning a Microsoft Azure certification.