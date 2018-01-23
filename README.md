# Network Word Count

### Steps to run 
- `sbt clean package`
- `spark-submit --class=streaming.NetworkWordCount target/scala-2.11/networkwordcount_2.11-0.0.1.jar localhost 9999`
- `nc -lk 9999`

### References 
- Heavily influenced from - https://spark.apache.org/docs/latest/streaming-programming-guide.html