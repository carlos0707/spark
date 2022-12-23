# spark
Word counter in Java with Spark

Steps to execute:
1. Create file in src/main/resources/spark_example.txt
2. Run mvn install to generate jar.
3. Run command in terminator /opt/spark/bin/spark-submit --class br.com.carlos.Main --master local target/spark-1.0-SNAPSHOT.jar src/main/resources/spark_example.txt 
 <br> 3.1 Notice that this directory: /opt/spark/bin/ is the directory where my spark is installed.
