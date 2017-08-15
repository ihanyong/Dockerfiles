[Advanced Nagios Plugins Collection](https://github.com/HariSekhon/nagios-plugins)
==================================
[![Build Status](https://travis-ci.org/HariSekhon/nagios-plugins.svg?branch=master)](https://travis-ci.org/HariSekhon/nagios-plugins)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/e6fcf7cb4dcc4905ab0a4cb91567fdda)](https://www.codacy.com/app/harisekhon/nagios-plugins)
[![GitHub stars](https://img.shields.io/github/stars/harisekhon/nagios-plugins.svg)](https://github.com/harisekhon/nagios-plugins/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/harisekhon/nagios-plugins.svg)](https://github.com/harisekhon/nagios-plugins/network)
[![Dependency Status](https://gemnasium.com/badges/github.com/HariSekhon/nagios-plugins.svg)](https://gemnasium.com/github.com/HariSekhon/nagios-plugins)
[![Platform](https://img.shields.io/badge/platform-Linux%20%7C%20OS%20X-blue.svg)](https://github.com/harisekhon/nagios-plugins#advanced-nagios-plugins-collection)
[![DockerHub](https://img.shields.io/badge/docker-available-blue.svg)](https://hub.docker.com/r/harisekhon/nagios-plugins/)
[![](https://images.microbadger.com/badges/image/harisekhon/nagios-plugins.svg)](http://microbadger.com/#/images/harisekhon/nagios-plugins)

Docker image containing the [Advanced Nagios Plugins Collection](https://github.com/HariSekhon/nagios-plugins) - the largest, most advanced collection of production-grade Nagios monitoring code (over 350 programs).

This docker image contains all dependencies pre-built on Debian and is tagged `harisekhon/nagios-plugins:debian`. For variants on Alpine, CentOS and Ubuntu see adjacent directories.

Specialised plugins for Hadoop, Big Data & NoSQL technologies, written by a former Clouderan ([Cloudera](http://www.cloudera.com) was the first Hadoop Big Data vendor) and current [Hortonworks](http://www.hortonworks.com) consultant.

Hadoop and extensive API integration with all major Hadoop vendors ([Hortonworks](http://www.hortonworks.com), [Cloudera](http://www.cloudera.com), [MapR](http://www.mapr.com), [IBM BigInsights](http://www-03.ibm.com/software/products/en/ibm-biginsights-for-apache-hadoop)), as well as most major open source NoSQL technologies, Pub-Sub / Message Buses, CI, Web and Linux based infrastructure.

Supports a a wide variety of [compatible Enterprise Monitoring servers](https://github.com/harisekhon/nagios-plugins#enterprise-monitoring-systems).

Most enterprise monitoring systems come with basic generic checks, while this project extends their monitoring capabilities significantly further in to advanced infrastructure, application layer, APIs etc.

It's a treasure trove of essentials for every single "DevOp" / sysadmin / engineer, with extensive goodies for people running:

* Web Infrastructure
* [Hadoop](http://hadoop.apache.org/)
* [Kafka](http://kafka.apache.org/)
* [RabbitMQ](http://www.rabbitmq.com/)
* [Mesos](http://mesos.apache.org/)
* [Consul](https://www.consul.io/)

NoSQL technologies:

* [Cassandra](http://cassandra.apache.org/)
* [HBase](https://hbase.apache.org/)
* [MongoDB](https://www.mongodb.com/)
* [Memcached](https://memcached.org/)
* [Redis](http://redis.io/)
* [Couchbase](http://www.couchbase.com/)
* [Riak](http://basho.com/products/)
* [Solr / SolrCloud](http://lucene.apache.org/solr/)
* [Elasticsearch](https://www.elastic.co/products/elasticsearch)

Linux & Infrastructure technologies:

* [Jenkins](https://jenkins.io/)
* [Travis CI](https://travis-ci.org/)
* SSL Certificate expiry
* advanced DNS record checks
* Whois domain expiry check
* [MySQL](https://www.mysql.com/)

and many more ...