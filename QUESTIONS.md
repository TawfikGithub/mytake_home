# Interview Questions



## What tenets are the most important to you when considering supply chain security in a CI/CD pipeline?
I believe CI/CD pipeline is to accelerate the releasing of code from the first initial commit to a complete software package ready for testing and deployment to production. Therefore, as code gets compiled and re
adied for release and deployment, so should the idea of security be incorporated in the CICD pipeline. There are so many important security features to consider in a CICD pipeline. First, software code requires the collaboration among various individuals which means there should be a way to check and remove hardcoded secrets and passwords. Secondly, build stage requires that software and application packages are sourced from the correct source. Thirdly, application software thats being deploy in a pipeline should have security tool to scan for common vulnerabilities that may be inadvertently introduced in the pipeline. Lastly, the principle of leaste privilege is very important to consider at the various stages in a CI/CD pipeline. It is always important to have a tracking merchanism to the pipeline.


## Describe the common patterns you have seen in adding a ruby application to a CI/CD pipeline. What operations are the most common? Why are these operations present? 
To be honest, I have not worked with ruby. I will be willing to learn this if given the opportunity.


## What are the most common ways that software is versioned? What are the benefits and challenges of each approach? 
Software versioning involves providing unique identifiers to built, update and revisions of software packages. it is the process of making sure we can identify a software based on modifications that have been made it it code source. It makes it easier to track at each cycle of changes that have been made to the code. 
The most common way softwares are versioned is Semantic Versioning(SemVer)  which can used to provide unique numbers to software. It has 3 components in form of Major.Minor.Patch (eg. CentOS 7.9-2009). This makes it easier to know which version of centos one is using in their application.
There other versioning approache is Internal Versioning for which a company comes up with a unique identifiers for numerous softwares it builds and manages.


## Give some examples of configuration management tools. Which tools do you prefer and why?
Some of the common configuration management tools are Ansible, Puppet, Chef, Salt, AWS Opsworks.
I prefer Ansible due to it ease of use. Ansible does not require an Agent/Master setup. It allows you to easily model complex processes. Easy to create an Inventory of hosts machines to manage. There are also many ansible modules that you can use for configuration management.


## What does the term "Infra as Code" mean? How does this term differ from "Configuration Management"?
Infra as Code(IaC) is the process of provisioning and managing IT infrastructure through code in a file. This eliminates the tedious manual process of building infrastructure. IaC allows writing in a text file/document all the specifications, parameters, configurations and requierements for building infrastructure in a most consistent way removing the tendency for human error and providing a repeatable tool for use.
There is a no major difference between Iac and Configuration Management. I believe there are much more similarities than difference. IaC used for provisioning and managing IT infrastructure can at times be used to configure the resources it has built. For example, Ansible used for configuration management can also be use to build infrastructure. However, I  believe the use case for an organization determines which tools to use either for provisioning infrastructure and managing configurations for the infrastructure.

