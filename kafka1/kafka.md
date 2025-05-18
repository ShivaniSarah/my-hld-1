https://www.interviewbit.com/kafka-interview-questions/



From one consumer group , only one consumer can consume from one partition in a topic.
Because of partitions in a topic parallel processing can be done in  a consumer group.

When consumer send ACK to kafka , it increments the offset. 
Retention Policy is by default 7 days for deletion withn which period offset can be reset and data consumed again.

