# Kafka_consumer
using Kafka to process inventory data. We have a topic called inventory_purchases which is receiving data about the items being purchased and the quantity. However, there is still a legacy system which must ingest this data in the form of a data file.

You have been asked to create a consumer that will read the data from the topic and output to a data file.

Each record has its own format 
key=<key>, value=<value>, topic=<topic>, partition=<partition>, offset=<offset>

