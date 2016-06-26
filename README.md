# ErrorsNRT
Detect and Report Web Traffic Anomalies in Near Real-Time using Flume, Spark Streaming and Impala

This repository contains  code of how Spark Streaming can be used to collect, count and aggregate occurences of bad HTML codes from a collection of web-servers in near-real-time.
The code can be used to detect peaks of bad web traffic as it happens. It uses Flume to collect events, Spark Streaming to process and persist them in real-time and Impala to present them to a reporting front-end.

.


