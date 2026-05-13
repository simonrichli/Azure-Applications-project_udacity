# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
###VM
	+ High flexibility due to multiple operating system and configuration possibilities
	+ Scalability due to easily adjusting CPU, RAM, and storage according to changing needs
 	+ Pay-as-you-go: You only pay for the resources you actually use
	+ Full control and complete access to the operating system and installed software
	- Availability of MS azure VM is dependenz on manager and configuration. High availability comes with higher costs for more VM and more configuration effort and complexity.
	- Management effort: You are responsible for updates, security, and maintenance
	- Potentially higher costs: expensive if not properly planned
	- Complexity: Setup and management require technical expertise
	- Less efficient for simple workloads compared to PaaS solutions
	
###Azure Service
	+ No infrastructure management since handled by provider like servers, updates, and maintenance
	+ deploying is easy due to direct connection to Git and provided CI/CD pipelines, or Visual Studio
	+ Scalability is fast and easy possible: Automatic or manual scaling depending on demand
	+ includes integrated services like Built-in support for authentication, monitoring, and backups
	+ Cost-efficient since it is cheaper and more efficient than VMs for web applications
	+ Availability of MS azure Web Service is noted as 99.95% which means minimal downtime and safety due to distribution across fault domains as well as automatic instance recovery, deployment
     slots for zero-downtime releases

###Resource of choice
	• "Azure Services Web Application".

###Justification
	• Azure Services Web Application suits better because I wanted to develope, deploy and use the app fast and easy. Due to integrating the required services like GitHub for automated deployment, Blobstorage, SQL Database as well as authentification services it is the choice.	Also important I was aiming for low costs and low or no effort on managing environment for scalability and availability.

###Assess app changes that would change your decision.
	• Reasons to change from "Web App" to "VM" may be due to increase user amount, need for higher frequency of new and more complex app features and therefore
	+ need of more control / advanced configuration of infrastructure
	+ need specialized software and / or libraries
	+ apply to compliance and security rules that might come up
