spark-scala
===========

This repository was forked by @crockpotveggies and upgraded to Spark 1.1.0.

Apache Spark is a fast and general-purpose cluster computing system. It provides high-level APIs in Scala, Java, and Python that make parallel jobs easy to write, and an optimized engine that supports general computation graphs. It also supports a rich set of higher-level tools including Shark (Hive on Spark), MLlib for machine learning, GraphX for graph processing, and Spark Streaming.

This is Spark Application which is built in Play 2.2.0. We can build it in any Play version. One thing that we have to keep in mind is the Akka version should be compatible to both Spark & Play. So, check the Akka version in Spark & Play that are inbuilt.

Commands to run this Application:

1. sbt clean
2. sbt compile
3. sbt run

If you want to distribute this app to a server you can also package with:

1. sbt dist

Note: 
> Whenever a change is made in the application, then run play dist command otherwise changes in the Spark files/functions will be not be reflected.
> To run only Spark Streaming, Spark SQL, Spark MLLib part you dont need to run command - "play dist".
