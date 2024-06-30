# CDC Pipeline Example with Database (PostgreSQL), CDC Streaming (Debezium + Kafka), Data-Lakehouse (Minio + Trino => hive & iceberg tables)  

An example CDC pipeline stack using PostgreSQL database as a data source to a Minio data lake house using Debezium & (Kafka + Zookeeper)  for CDC streaming, Minio for the data lake house storage and trino for the data lake house compute layer. The data will be streamed from PostgreSQL database into the Minio data lake as Hive tables in Parquet file format and  transformed into Iceberg tables (Also Parquet file format) using Trino as the SQL Engine.

# My Source Info for creating this stack

# How to run the stack
