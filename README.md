# Retail_Data_Analysis
Real time Retail Data Analysis with the help of Spark Streaming.

Broadly, we will perform the following tasks in this project:

Reading the sales data from the Kafka server.
Preprocessing the data to calculate additional derived columns such as total_cost etc.
Calculating the time-based KPIs and time and country-based KPIs.
Storing the KPIs (both time-based and time- and country-based) for a 10-minute interval into separate JSON files for further analysis.
The data contains the following information:

Invoice number: Identifier of the invoice
Country: Country where the order is placed
Timestamp: Time at which the order is placed
Type: Whether this is a new order or a return order
SKU (Stock Keeping Unit): Identifier of the product being ordered
Title: Name of the product is ordered
Unit price: Price of a single unit of the product
Quantity: Quantity of the product being ordered
Reading input data from Kafka Code to take raw Stream data from Kafka server

Bootstrap Server - 18.211.252.152
Port - 9092
Topic - real-time-project
