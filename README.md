# Data_Engineer_Ass4_Databricks
## Setup Summary

## Set up Databrick
The first step to create Databricks workspace </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass4_Databricks/blob/main/image/Create%20Azure%20Databricks%20Workspace.jpg)
After the workspace is created, we can start to create Spark Cluster within the Workspace </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass4_Databricks/blob/main/image/Creating%20Spark%20Cluster.jpg)

For the next step, the data need to be Ingested to Databricks workspace. Todo this, we must first need to switch on the Enable DBFS file browswer, this allows use to see the updated file </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass4_Databricks/blob/main/image/Enable%20DBFS%20file%20browser.jpg)
We can start upload the csv files to the workspace </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass4_Databricks/blob/main/image/Uploading%20data%20to%20Databricks%20File%20System.jpg)

After the files are availble on DBFS, we can write Spark code to ingest the data </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass4_Databricks/blob/main/image/Ingest%20Data%20by%20Notebook.jpg)

# Transform Process
The data from csv can be transformed to the data schema that can answer the business questions </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass4_Databricks/blob/main/image/Start%20Schema.png)

To convert the raw data to valuable data format, we must transform the data by following format </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass4_Databricks/blob/main/image/Transform%20Process.jpg)

The results tables created </br>
![alt text](https://github.com/NgoDuyVu1993/Data_Engineer_Ass4_Databricks/blob/main/image/Result%20Tables.jpg)


