# SDA-Project-S7
SDA cloud computing project - stage 7

In this stage we  will replacing the Azure Application Gateway and VMSS with Azure Function App. 
The Azure Function App will host the backend of the application. The VM will be used to host the frontend and ChromaDB. 

At this stage, we should create and setup infrastructure in this diagram manually.


![image](https://github.com/user-attachments/assets/e9deb7a6-1dd6-4db7-ab0d-5fc621c05b06)


The GitHub Actions workflow should be updated to deploy the backend to the Azure Function App.

In the end, we can be able to access the application via the VM's public IP address, with data stored in the Azure Database for PostgreSQL server and files stored in Azure Blob Storage.
