# AzureUp
Azure Demos, learning by doing

Base for 3 workshop sessions at Cybercom Cloud Academy
Move a local application to different Cloud options - discuss and reflect on pros and cons of each option.

Focus is on learning and exploring different Azure Technoglogies - not allways in a best practice way - we code the happy path, don't have robust error handling and logging etc.

## Workshop 1
1. Start with On prem version
2. Upgrade to reading from Blob Storage using SAS and Shared Access Policy instead of local disk
3. Creating a VM in Azure, run app from VM
4. Dockerize it, create Azure Container Registry (ACR), push to ACR, run manually on VM

After this workshop you will have had an intro to
* Azure Storage
* Azure CLI 
* Azure Portal
* Docker Containers
* Azure Container Registry
* Azure Storage Explorer

## Workshop 2
5. Create Azure Container Instance (on-demand docker host), run Dockerized version from ACI manually
6. Create a Logic App that runs Dockerized version from ACI by starting it from a Logic App that is triggered by events from blob storage
7. Add code to Logic App to add information to email when ACI starts
8. Add Code in program to send data to a message queue, update Docker image on ACR

After this workshop you will have had an intro to
* Azure Container Instance
* Eventing on Azure
* Logic Apps
* Connectors in logic app
* Monitoring Logic App runs in Azure Portal
* Azure Storage Explorer

## Workshop 3
9. Write an Azure Function that are triggered from the queue and stores the data in Table Storage
10. Event Hubs / Topics / Aggregating / Singletons
11. Display in Blazor - run from blob storage

