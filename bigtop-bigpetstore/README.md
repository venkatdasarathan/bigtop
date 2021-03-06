BigPetStore
============

BigPetStore is a family of example applications for the Hadoop/Spark
ecosystems. BigPetStore generates and analyzes synthetic transaction data for
a fictional chain of petstores.

BigPetStore has the following aims:

* Serve as a demo application to showcase capabilities of the BigTop distribution
* Perform integration testing for BigTop's components
* Server as a template for building / packaging Hadoop/Spark applications
* Provide scalable generation of complex synthetic data
* Examples for using and integrating components such as Pig, Hive, Spark SQL, etc.
* Examples of how to perform popular analytics tasks

BigPetStore has the following components to date:

* Gradle build systems supporting Java, Scala, and Groovy
* Data generators
* Analytics
  * ETL
  * Item Recommenders

The BigPetStore application was originally developed for MapReduce and associated
components such as Pig, Hive, Mahout, Crunch, etc. With the increasing popularity
and importance of Spark, BigPetStore has been expanded to support Spark.  To support
the use case of deploying to pure MapReduce or Spark environments, we've elected to
separate the MapReduce and Spark support into separate applications. You can find the
two applications, along with futher documentation, under `bigpetstore-mapreduce` and
`bigpetstore-spark`, respectively.


