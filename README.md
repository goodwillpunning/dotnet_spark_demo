# dotnet_spark_demo
Demo .Net for Apache Spark application

# Prequisites
- Apache Spark 3.0.1 installed
- (optional) .NET SDK

# Running locally
To run the sample application, change directories to the Spark demo app and launch the Spark application using `spark-submit`

```bash
$ cd mySparkApp
$ spark-submit --class org.apache.spark.deploy.dotnet.DotnetRunner --master local bin/Debug/netcoreapp3.1/microsoft-spark-3-0_2.12-1.0.0.jar dotnet bin/Debug/netcoreapp3.1/mySparkApp.dll
```
