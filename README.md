# Streaming-Application 
Streaming Fire Data
<br></br>
In this project, multiple Apache Kafka producers are implemented to simulate the real-time streaming of the data which is processed by Apache Spark Streaming client and then inserted into MongoDB. Also, real-time data visualisation is created.
<br></br>

## System Architecture
<img width="945" alt="Screen Shot 2020-02-12 at 2 30 42 pm" src="https://user-images.githubusercontent.com/40382496/74300715-c5feb200-4da4-11ea-8df4-d7d8ec99a4a8.png">



## User Guide
1. Kafka_Producer1,2,3.ipynb files should be run first to produce events on LocalHost:9092.
2. Streaming_Application.ipynb should be run to collect the real-time data, process and merge the data and save it into local MongoDB server.
3. Real_Time_Data_Visualisation.ipynb can be run to visualise fire locations on a map and create an air tempreture - time dashboard.
