
 
  Project Title: ADF ETL Pipeline that Reads .csv Files in Azure Data Lake and Loads them into Azure SQL Database Table

A.  Source Folder Details:
	 Number of Files: 2
	 File format: CSV

B.  Target Location Details:
	 Azure SQL Database table

	

C.  Business requirements:
    Client (user) needed to Copy Data from a Source Folder in Data Lake to a table in Azure SQL Database
	

D.  Solution Steps: 
   	 -create RBAC role assignment for the storage account container 
   	 -create link services, datasets, ETL pipeline and activities
   	 -Copy files from source folder to the Azure SQL Database table
   	 -check the Azure SQL Database table for the copied data to confirm the pipeline runs successfully


E.  Azure Services used: 
   	 -Azure Data Lake
   	 -Azure Data Factory
   	 -Azure SQL Database
