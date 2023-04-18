# Retail-Data-Analysis---PG-Diploma-IIITB

For the purposes of this project, you have been tasked with computing various Key Performance Indicators (KPIs) for an e-commerce company, RetailCorp Inc. You have been provided real-time sales data of the company across the globe. The data contains information related to the invoices of orders placed by customers all around the world. You will get to know the details of the data in the next segment.

 

At the industry level, an end-to-end data pipeline is built for this purpose. Tools such as HDFS(Hadoop Distributed File System) are used to store the data that is processed by the real-time processing framework and then shown on a dashboard with tools such as Tableau and PowerBI. The image given below is an example of such a complete data pipeline.


For our project, we will be focusing on the ‘Order Intelligence’ part of this data pipeline. The image given below shows the architecture of the data pipeline that we will follow in this project.

Broadly, you will perform the following tasks in this project:

Reading the sales data from the Kafka server

Preprocessing the data to calculate additional derived columns such as total_cost etc

Calculating the time-based KPIs and time and country-based KPIs

Storing the KPIs (both time-based and time- and country-based) for a 10-minute interval into separate JSON files for further analysis
