.. _installation:

Installation
============

.. toctree::
   :maxdepth: 2

   platforms/cloud.rst
   platforms/baremetal.rst
   platforms/vagrant.rst
   platforms/cookbooks.rst
   attributes_table.rst
   requirements.rst
   upgrades.rst
   hops-manual-installation-guide.rst
	      
The Hopsworks stack may require the installation of a number of third-party distributed services:

* Java (OpenJDK or Oracle JRE/JDK)
* Apache Spark
* Apache Flink
* Apache Hive
* TensorFlow
* MySQL Cluster (NDB)
* Payara Server
* ELK Stack (Elastic, Logstash, Kibana, Filebeat)
* Influxdb, Telegraf, Grafana
* Kafka + Zookeeper
* Jupyter Notebook
* Nvidia Cuda/cuDNN/NCCL-2
* ROCm (AMD)
* Apache Airflow
* Apache Livy
* PyTorch
* Conda
* Prometheus
  
Due to the complexity of installing and configuring all Hopsworks' services, we recommend installing Hopsworks using the automated installer Karamel/Chef, http://www.karamel.io. We do not provide detailed documentation on the steps for installing and configuring all services in Hopsworks. Instead, Chef cookbooks contain all the installation and configuration steps needed to install and configure Hopsworks. The Chef cookbooks are available at https://github.com/logicalclocks. Support for enterprise installations of Hopsworks can be obtained by contacting Logical Clocks at https://www.logicalclocks.com .
