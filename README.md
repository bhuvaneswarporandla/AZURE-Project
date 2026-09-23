# AZURE-Project

1. Abstract 

Azure Blob Index Tags provide a way to organize and discover large numbers of blobs using metadata-based tags. Instead of scanning all containers and blobs, users can search blobs based on attributes such as department, file type, project, year, or status. 

The proposed system stores files in Azure Blob Storage and assigns Blob Index Tags to each file. Users can search and filter blobs using these tags, enabling faster metadata-based discovery at large scale. The system reduces the need for full container enumeration and improves data organization and retrieval. 

The project also considers practical limitations such as index tag limits and the performance impact of adding tags to existing blobs.


2. Architecture Diagram
 
•	User: The user uploads files or searches for existing files. 
•	Web Interface: Provides an interface for uploading and searching documents. 
•	Backend/API: Processes upload and search requests. 
•	Azure Blob Storage: Stores the actual files and documents. 
•	Blob Index Tags: Adds metadata to each blob, such as department, year, file type, and status. 
•	Tag-Based Search: Searches blobs using their index tags instead of checking every file individually. 
•	Result: The required blob can be identified and accessed efficiently.


3. Azure Services Required


The main services required for implementing the core project are:
•	Azure Storage Account 
•	Azure Blob Storage 
•	Blob Index Tags 
•	Azure App Service
Uses of the Services:
Azure Storage Account: It provides the main cloud storage resource required to create and manage storage containers for the project.
Azure Blob Storage: It is used to store and manage project files and documents securely in the cloud.
Blob Index Tags: They are used to add searchable metadata such as file type, department, year, and status to stored files.
Azure App Service: It is used to host the web application or backend that handles file uploads, tagging, and searching.
Microsoft Entra ID: It provides user authentication and access control to ensure that only authorized users can access the application and data.
Azure Monitor: It is used to monitor the performance, activities, and errors of the application and Azure resources.

