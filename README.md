# SamplingFlink
Scope of this project is to apply Algorithm 1: CVOPT-SASG: Algorithm computing a random sample for a single aggregate, single group-by as refers in the follow source : <ins> https://arxiv.org/pdf/1909.02629.pdf </ins>
input streams-data are coming from : <ins> https://openaq.org/ </ins>
 
Loaded into a Kafka topic (Removed in last version)
Read From Kafka topic (Removed in last version) // Comment code,  Lose Tuples cause Time events.//  

# How To Run :
* Run FirstPAssMain
* Run SecondPassMain

# How To Run Using Kafka:
* Run FirstPassMain
* Run KafkaMain
* Run SecondPassMain

# Upcoming Updates :
Resolving Time Issues, New KafkaConsumer (Connection between first and second Flink jobs).
