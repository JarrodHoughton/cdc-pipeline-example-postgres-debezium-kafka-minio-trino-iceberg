# cdc-pipeline-example-postgres-debezium-minio-trino-iceberg
 
An example CDC pipeline stack using PostgreSQL database as a data source to a Minio data lake using Debezium & Kafka for CDC streaming, minio for the data lake storage and trino for the data lake house compute. The data will be streamed from PostgreSQL database into the Minio data lake as Hive tables in Parquet format and  transformed into Iceberg tables (Also Parquet) using Trino as the SQL Engine.

# How to run the stack:
