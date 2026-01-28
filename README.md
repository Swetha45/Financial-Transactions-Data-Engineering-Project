# Financial-Transactions-Data-Engineering-Project

I worked on a financial transaction dataset containing transaction details such as amounts, timestamps, transaction types, and customer demographic information, covering transactions throughout the 2010s


 Used Below Resources to work on this project.

To manage and process the data, I created an Azure Storage Account to load bulk transaction data into a container. Using Azure Data Factory, I copied the data from the bulk container into another Data Lake container in Parquet format for optimized storage and performance.

Next, I set up app registrations to securely access the data from Databricks. In Databricks, I applied transformations and analysis on the transactional data to identify premium customers based on their transaction behavior.

