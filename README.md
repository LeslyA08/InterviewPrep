# InterviewPrep
So as part of our preparation for interviews coming up we are going to be sending you topics each day that we would like you to prepare in. For the task we would like you to create a GitHub repository that will be the home of your prep. Please share the link with us so we can see you daily progress. In the repo we would like you to create a README.md that will be your glossary. Please follow the follow format for the prep:
Repo Created
A section per topic and three parts to each section
Explanation of topic / concept in your own words
Explanation of what you created with that tool / concept
Detail of the benefit to using the this tool / concept
Make this look really good with MARKDOWN  Add links to your code if you have examples.
Todays Topics

### H3 Cloud & DevOps

##### H5 Explanation:
-Cloud is the practice of abstracting various levels of an application as services, rather than products. In a cloud, a service provider manages underlying systems to some degree, so the consumer only has to manage the systems that add value to their organization. 
-DevOps is the practice of using operations-focused approach to development, and a development-focused approach to operations, to facilitate velocity and stability of systems ad infrastructure

##### H5 What I created:
DevOps: CI/CD

##### H5 Benefits:
Cloud: Cloud deployments reduce capital expenditure over physical deployments, as the provider is able to achieve significant efficiency in capital costs which are spread  across many consumers. Cloud deployments also reduce operational expenses, as the provider takes responsibility for a portion of the operational workload. For example, in a basic IaaS model, the prover purchases and manages datacenter space, power capacity, cooling capacity, physical hardware, networking infrastructure, etc, and the consumer pays a nomical subscription fee and only has to manage their systems and networking configuration. Cloud services may be Infrastructure IaaS, Platform PaaS, Storage STaaS, or fully-hosted Software solutions SaaS.
DevOps: developers can freely develop and deploy code using systems managed by DevOps team without being tied to restrictive change management processes, operations teams have to worry less about new code introducing stability issues

### H3 CICD

##### H5 Explanation:
-the practice of using automation to test, build, integrate, and deploy new code with minimal human oversight, to facilitate velocity through frequent releases of small component of applications, rather than periodic releases of monolithic code changes

##### H5 What I created:
Created a pipeline to Jenkins that automatically runs when pushed to github.

##### H5 Benefits:
-Increased velocity, improved stability, less likelihood of major bugs, less operational overhead, automated rollback reduces cost of bad deployments

### H3 Jenkins

##### H5 Explanation:
-Jenkins is a program used with CI/CD pipelines for testing and deployment. Used to build and test your project.

##### H5 What I created:
Created a pipeline that automatically tests once things are pushed to github.

##### H5 Benefits:
-Not only is Jenkins widely used, it also makes running CICD pipelines easier. accelerates development life-cycle. open source tool with community support.

### H3 Provisioning

##### H5 Explanation:
-Provisioning is to automate your commands. Instead of typing it in manually, you add them all to a file that runs and automatically installs software you need and runs through the commands you specify. You can set up a server this way. 

##### H5 What I created:
-made provisioning scripts to run a vagrant machine.

##### H5 Benefits:
-Provisioning helps automate things. You don't have to type in the same commands over and over everytime you make a change.

### H3 Networking

##### H5 Explanation:
-what makes it possible for computers and other devices to communicate with each other.

##### H5 What I created:
-Used public IP addresses to connect virtual machines to ec2 instances.

##### H5 Benefits:
Different ways to communicate with each other.  Share resources. (share a printer instead of directly connecting to individual ones)

### H3 Principle of Least Privilege

##### H5 Explanation:
-This is a concept that lets users only have the privileges they are required to do their jobs and nothing more.

##### H5 What I created:
set permissions to only read.

##### H5 Benefits:
-This helps not give any users permissions to change anything they shouldn't. We don't want users being able to see or release things they shouldn't.

### H3 IAC

##### H5 Explanation:
-Infrastructure as code: the practice of representing IT infrastructure configuration as code, for the purpose of managing the deployment and provisioning of IT systems

##### H5 What I created:
-created a mySQL database using Terraform.

##### H5 Benefits:
-Speed and efficienct, consistenct, alignment with devops

### H3 Packer and Terraform

##### H5 Explanation:
-Packer is an open source tool that helps create a server image. It saves any configurations and installations within the image.
-Terraform is an IaC tool that uses readable code (HCL or Hashicorp configuration language) to spin up infrastructure in cloud. 

##### H5 What I created:
-Created an image using packer and nodejs. This image was provisioned and configured.
-Created a mysql database using Terraform, connected to AWS. 

##### H5 Benefits:
-Terraform's code is reusable so you don't have to retype everything everytime. It helps when spinning up projects in the cloud so your configuration is the same every time.
-Packer deploys images that are provisioned and configured so you don't have to do so manually.
