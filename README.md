# Data-Filtering-Pipeline-ETL
## Problem Statement
I have given a csv file having 180k rows. First I have to find a data by top 3 countries which I did by python pandas then my mission was to extract data from datalake filtered it by top 3 countries and again send it to datalake in seperate 3 files countrywise. The problem that I faced during the pipeline was that data was raw and it contained special characters that it was not filtering out then I change its encoding from UTF-8 to ISO-8859-1 in AzureDataFactory and problem resolved.
## The files
 The Second Portfolio Project.json file contains information about the ADF pipeline, including the pipeline name, description, and the resources that make up the pipeline. The manifest.json file contains information about the dependencies and structure of the ARM template of the pipeline in Azure DataFactory. Jupyter notebook file contain the dataanalysis in python.
 
