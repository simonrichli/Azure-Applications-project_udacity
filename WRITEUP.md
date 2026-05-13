# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
###VM
	+ High flexibility due to multiple operating system and configuration possibilities
	+ Scalability due to easily adjusting CPU, RAM, and storage according to changing needs
 	+ Pay-as-you-go: You only pay for the resources you actually use
	+ Full control and complete access to the operating system and installed software
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

###Resource of choise
	• "Azure Serivces Web Application".

###Justification
	• Since I want low costs and my focus is on developement fast and easy deployment and not on managing environment and scalability is not important but availability and integration of CI/CD via github.

###Assess app changes that would change your decision.
	• Reasons to change from "Web App" to "VM" may be due to increase user amount, need for higher frequency of new and more complex app features and therefore
	+ need of more control / advanced configuration of infrastructure
	+ need specialized software and / or libraries
	+ apply to compliance and security rules that might come up
