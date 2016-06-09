[<img src="https://cdn.rawgit.com/awesome-spark/awesome-spark/master/spark-logo-trademark.png" align="right">](https://spark.apache.org/)

# Awesome Spark [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome [Apache Spark](https://spark.apache.org/) packages and resources.


## Table of Contents

- [Packages](#packages)
  - [Language Bindings](#language-bindings)
  - [Notebooks and IDEs](#notebooks-and-ides)
  - [General Purpose Libraries](#general-purpose-libraries)
  - [SQL Data Sources](#sql-data-sources)
  - [Bioinformatics](#bioinformatics)
  - [GIS](#gis)
  - [Time Series Analytics](#time-series-analytics)
  - [Graph Processing](#graph-processing)
  - [Machine Learning Extension](#machine-learning-extension)

- [Resources](#resources)
  - [Books](#books)
  - [MOOCS](#moocs)
  - [Workshops](#workshops)
  - [Projects Using Spark](#projects-using-spark)


## Packages

### Language Bindings

* [Flambo](https://github.com/yieldbot/flambo) - Clojure DSL.
* [Mobius](https://github.com/Microsoft/Mobius) - C# bindings.

### Notebooks and IDEs

* [Apache Zeppelin](https://zeppelin.incubator.apache.org/)
* [Spark Notebook](https://github.com/andypetrella/spark-notebook)

### General Purpose Libraries

* [Succinct](http://succinct.cs.berkeley.edu/) - Support for efficient queries on compressed data.


### SQL Data Sources

* [Spark CSV](https://github.com/databricks/spark-csv) - CSV reader and writer.
* [Spark Avro](https://github.com/databricks/spark-avro) - [Apache Avro](https://avro.apache.org/) reader and writer.
* [Spark XML](https://github.com/databricks/spark-xml) - XML parser and writer.
* [Spark-Mongodb](https://github.com/Stratio/Spark-MongoDB) - MongoDB reader and writer.
* [Spark Cassandra Connector](https://github.com/datastax/spark-cassandra-connector) - Cassandra support including data source and API and support for arbitrary queries.
* [Spark Riak Connector](https://github.com/basho/spark-riak-connector) - Riak TS & Riak KV connector

### Bioinformatics

* [ADAM](https://github.com/bigdatagenomics/adam) - a set of tools designed to analyse genomics data.

### GIS

* [Magellan](https://github.com/harsha2010/magellan) - Geospatial Analytics Using Spark.
* [GeoSpark](https://github.com/Sarwat/GeoSpark) - A Cluster Computing System for Processing. Large-Scale Spatial Data

### Time Series Analytics

* [Spark-Timeseries](https://github.com/cloudera/spark-timeseries) - A Scala / Java / Python library for interacting with time series data on Apache Spark.

### Graph Processing

* [Mazerunner](https://github.com/neo4j-contrib/neo4j-mazerunner) - graph analytics platform on top of Neo4j and GraphX.
* [GraphFrames](https://github.com/graphframes/graphframes) - `DataFrame`-based graph API.

### Machine Learning Extension

* [dbscan-on-spark](https://github.com/irvingc/dbscan-on-spark) - An Implementation of the DBSCAN clustering algorithm on top of Apache Spark by [irvingc](https://github.com/irvingc) and based on the paper from He, Yaobin, et al. [MR-DBSCAN: a scalable MapReduce-based DBSCAN algorithm for heavily skewed data](https://www.researchgate.net/profile/Yaobin_He/publication/260523383_MR-DBSCAN_a_scalable_MapReduce-based_DBSCAN_algorithm_for_heavily_skewed_data/links/0046353a1763ee2bdf000000.pdf).
* [spark_dbscan](https://github.com/alitouka/spark_dbscan) - Another Implementation of the DBSCAN clustering algorithm on top of Apache Spark by [alitouka](https://github.com/alitouka).
* [Apache SystemML](https://systemml.apache.org/) - declarative machine learning framework on top of Spark.
* [Mahout Spark Bindings](https://mahout.apache.org/users/sparkbindings/home.html) - linear algebra DSL and optimizer with R-like syntax.
* [spark-sklearn](https://github.com/databricks/spark-sklearn) - scikit-learn integration with distributed model training.
* [KeystoneML](http://keystone-ml.org/) - type safe machine learning pipelines with RDDs.

## Resources

### Books

* [Mastering Apache Spark](https://jaceklaskowski.gitbooks.io/mastering-apache-spark/).
* [Learning Spark, Lightning-Fast Big Data Analysis](http://shop.oreilly.com/product/0636920028512.do).
* [Advanced Analytics with Spark](http://shop.oreilly.com/product/0636920035091.do).

### MOOCS

* [CS100 - Introduction to Big Data with Apache Spark](https://www.edx.org/course/introduction-big-data-apache-spark-uc-berkeleyx-cs100-1x).
* [CS190 - Scalable Machine Learning](https://www.edx.org/course/scalable-machine-learning-uc-berkeleyx-cs190-1x).

### Workshops

* [AMP Camp](http://ampcamp.berkeley.edu)

### Projects Using Spark

* [Oryx 2](https://github.com/OryxProject/oryx) - a [lambda architecture](http://lambda-architecture.net/) built on Apache Spark and [Apache Kafka](http://kafka.apache.org/) with specialization for real-time large scale machine learning.
* [PredictionIO](https://prediction.io/) - Machine Learning server for developers and data scientists to build and deploy predictive applications in a fraction of the time.


## License

<p xmlns:dct="http://purl.org/dc/terms/">
<a rel="license" href="http://creativecommons.org/publicdomain/mark/1.0/">
<img src="http://i.creativecommons.org/p/mark/1.0/88x31.png"
     style="border-style: none;" alt="Public Domain Mark" />
</a>
<br />
This work (<span property="dct:title">Awesome Spark</span>, by <a href="https://github.com/awesome-spark/awesome-spark" rel="dct:creator">https://github.com/awesome-spark/awesome-spark</a>), identified by <a href="https://github.com/zero323" rel="dct:publisher"><span property="dct:title">Maciej Szymkiewicz</span></a>, is free of known copyright restrictions.
</p>

Apache Spark, Spark, Apache, and the Spark logo are <a href="https://www.apache.org/foundation/marks/">trademarks</a> of
  <a href="http://www.apache.org">The Apache Software Foundation</a>. This compilation is not endorsed by The Apache Software Foundation.
