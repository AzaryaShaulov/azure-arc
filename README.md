# Azure Arc-enabled Servers dashboard

This dashboard gives you an executive view of your Arc-enabled server environment. 
The  dashboard is broken into  __2 sections__; Arc-enabled Servers and Windows Server 2012/R2 ESU data. 
It's designed to be as simple as possible, yet give you enough information to review your environment in one simple glance


#### Arc-enabled Servers section
 * Breakdown and count of Arc-enabled servers under your tenant
 * Servers by OS Types and counts 
 * Linux/Windows breakdown
 * Connected(Online)/Disconnected(offline) status
 * Outdated Azure-connected machine agents
   
#### Windows Server 2012/R2 section
  * Track ESU licenses activated and assigned
  * of servers eligible for ESU
  * of servers enabled/not enabled for ESU deployment
  * of server cores enabled/not enabled for ESU deployment
  * Windows Server 2012/R2 editions and count
  * ESU licenses states Activated/Deactivated
  * ESU licensed Cores/pCores and counts Assigned/NotAssinged
  * ESU assignments and activation counts

![arc-enabled-servers](./images/AzureArc-enabledServers.jpeg)

![arc-enabled-esu](./images/AzureArc-enabledESU.jpeg)


## Dashboard file
  The dashboard is in JSON format and can be downloaded as a file here -->
  [Azure Arc-Enabled Servers](files/AzureArc-EnabledServers.json)
