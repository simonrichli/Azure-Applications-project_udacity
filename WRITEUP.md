# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
	• APPService (AS) has lower costs then Virtual Machines (VM) according to azure webpage prizing. For the task I would like to focus on developing the app and not controling managing the environment. There is no information about customer amount and/or prognosted customer developement so scalability is not of focus for decision. Since it is an online application availability is of essence. The tasks mentions usage of github to be integrated in workflow.
	• According to above assumptions I choose azure web applications. 
  • Since I want low costs, my focus is on developement and not on managing environment and scalability is not important but availability and integration of CI/CD via github.

### Assess app changes that would change your decision.

If (prognosted) customer amount is very high the premisses change. More customers need higher scaling also they might want more and complex features and more often and therefore the focus of developing shifts to more controll of environment. 
