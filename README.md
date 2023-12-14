# Real-time ETL pipeline project

<h3 align="left">Introduction</h3>

In this project, the Client is one of the top logistics and transport service providers in Hong Kong. They leading logistics solution providers of e-commerce, electronic parts, and cold chain operations in the APAC region. The company’s goal is to create predictable trends so they can analyze and find patterns to create new business opportunities and also want to create a data-driven culture.

<h3 align="left">Challenges</h3>

1. Before deploying AWS data pipelines, it was difficult to integrate and collect real-time data and generate vast amounts of data from customers, transactions,
business process and supply chains.
2. The company’s growth in areas like e-commerce means the volume of data it is managing is increasing rapidly.
3. Its finance and accounting teams take several days to extract and transform that data with a manual system
4. Data team Several days to manage and Create a data pipeline by traditional system.
5. Previously, our management teams had to wait until the end of the month to receive sales data for report generation.

<h3 align="left">Solutions</h3>

1. Hence, We decided to migrate its applications from an on-premises infrastructure to the AWS Cloud environment with low cost and scale-up.
2. Amazon Kinesis is used for data integration, the Kinesis data stream is used to build custom applications that make it easy to process and analyze streaming data in real time, and the Kinesis Firehouse is used to deliver data to AWS destinations.
3. Amazon S3 (Simple Storage Service) provides the Data lake with vast and stores about 5GB of raw data daily and securely, transfers data.
4. Amazon Glue was used to perform the ETL Job and run Crawler to scan various data stores and automatically infer schemas and populate the AWS Glue Data Catalog.
5. Amazon Athena provides a serverless data warehouse and interactive query service that makes it easy to analyze data using SQL.
6. Create a serverless dashboard in minutes via Amazon Quicksights for business insights.

<h3 align="left">Architecture</h3>
<img src="https://github.com/sagardhavalgi/Real-time-data-engineering-project/blob/main/Project_Archi.PNG" alt="descriptive text">

we bring that data from the source using Kinesis stream data and put that data on Kinesis Firehose after that, we will deliver that data onto Amazon s3 and after that process that data and crawl that data to build a glue catalog and analyze that data using Amazon Athena using SQL without complex installation or setup and visualize that data using Amazon quicksight.

<h3 align="left">Technology Used</h3>

1. AWS Kinesis
2. AWS S3
3. AWS Glue and Glue Data Catalog
4. AWS Athena
5. AWS Quicksight


