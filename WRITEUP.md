# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
Virtual Machines are more expensive and can be more time consuming in the set up and workflow for developers. On the other hand multiple VMs can be grouped to provide high availability, scalability, and redundancy and they are very flexible in choosing multiple types from, such as compute or memory-optimized VMs, along with varying amounts of CPU, RAM and storage.

An App Service is a Platform as a Service (PaaS) that allows a developer to focus on the application while Azure takes care of the infrastructure. You can set the amount of hardware allocated to host your application, and cost varies based on the plan you choose. High availability, auto-scaling with the option of vertical and horizontal scaling are provided. There are different workflows for continuous deployment available for example GitHub.


- *Choose the appropriate solution (VM or App Service) for deploying the app*
In case of my studywork CMS-Setup I chose an App Service as the prefered platform. 

- *Justify your choice*
In case of my studywork 'CMS-Setup' I chose an App Service as the prefered platform. Major reason for my choice was the free cost option within a Dev/Test-App Service and the support the Python-Stack of the application. Also I wanted to keep the complexity low in my first class project.

### Assess app changes that would change your decision.
*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 
If the app is going in a production area with the expectation of high traffic or traffic peaks. I would rethink my decision and a Virtual Machine is the better choice to meet the requirements for availability, scalability, and redundancy. Also upcoming requirements concerning more access and control of the infrastructure would make a Virtual Machine environment the better choice.

