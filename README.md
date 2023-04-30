# Data-Filtering-Pipeline-ETL
## Problem Statement
I have given a csv file having 180k rows. First I have to find a data by top 3 countries by Order Country column which I did by python pandas and get EstadiosUnidos,Francia and Mexico as top 3 countries with most records then my mission was to extract data from datalake filtered it by top 3 countries and again send it to datalake in seperate 3 files countrywise. The problem that I faced during the pipeline was that data was raw and it contained special characters that it was not filtering out then I change its encoding from UTF-8 to ISO-8859-1 in AzureDataFactory and problem resolved.
## The files
 The Second Portfolio Project.json file contains information about the ADF pipeline, including the pipeline name, description, and the resources that make up the pipeline. The manifest.json file contains information about the dependencies and structure of the ARM template of the pipeline in Azure DataFactory. Jupyter notebook file contain the dataanalysis in python.
 ## Workflow
 ![Untitled Diagram drawio](https://user-images.githubusercontent.com/123824748/235349396-20c23355-6d52-4f4c-894c-1b59f4e2e699.png)
 ## Pipeline Structure
 ![Capture](https://user-images.githubusercontent.com/123824748/235349480-fb20895d-5a33-42b0-ae84-3fce4a09fc62.PNG)
 ## Finally Filtered Data
 ![WhatsApp Image 2023-04-29 at 23 24 06](https://user-images.githubusercontent.com/123824748/235349535-6cf6f993-76e3-4c61-ae46-ee6d40fcc8f9.jpg)

 

