# Financial-Transactions-Data-Engineering-Project

I worked on a financial transaction dataset containing transaction details such as amounts, timestamps, transaction types, and customer demographic information, covering transactions throughout the 2010s


 Used Below Resources to work on this project.

To manage and process the data, I created an Azure Storage Account to load bulk transaction data into a container. Using Azure Data Factory, I copied the data from the bulk container into another Data Lake container in Parquet format for optimized storage and performance.


<img width="965" height="477" alt="image" src="https://github.com/user-attachments/assets/aa175441-a50f-4b00-a769-12b9bcbce303" />

<img width="1125" height="172" alt="image" src="https://github.com/user-attachments/assets/2a8406a4-21ec-4278-a0e2-06457942caab" />



Next, I set up app registrations to securely access the data from Databricks. In Databricks, I applied transformations and analysis on the transactional data to identify premium customers based on their transaction behavior.

DataSet Link : https://www.kaggle.com/datasets/computingvictor/transactions-fraud-datasets/data?select=transactions_data.csv
