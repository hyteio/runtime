HYTE MQ
============
 
Contents
========

 * HYTE MQ ${project.version}
 
 Components:
 * Apache Karaf ${hyte.karaf.version}
 * Apache ActiveMQ ${hyte.activemq.version}
 * Apache Camel ${hyte.camel.version}
 * Apache CXF ${hyte.cxf.version}
 
Contact
=======

URL: https://hyte.io
Sales: <sales@hyte.io>
Technical Support: <support@hyte.io>

Distributions
=============

The HYTE MQ is distributed in three ways:

 * hyte-mq-${project.version}-unix.tgz - Stand-Alone distribution that is ready to start on Linux 64-bit systems.
 * hyte-mq-${project.version}-win64.tgz - Stand-Alone distribution that is ready to start on Windows 64-bit systems.
 * hyte-mq-${project.version}-kubernetes.tgz - Kubernetes-ready distribution that is prepared for inclusion in a Kubernetes container build pipeline.

All distributions are available for the current version of the product via Maven Central: http://central.maven.org/maven2/io/hyte/platform/hyte-mq/

Quick Start
===========

+++ Stand-alone Quick Start Instructions (Linux)

 Starting: 

 1. Extract the 'hyte-mq-${project.version}-unix.tgz' distribution file.
 2. Ensure additional instances of HYTE MQ are shutdown to avoid port conflicts.
 3. Run ./bin/start
 4. Open a browser to http://localhost:8181 

 Stopping:

 * If the HYTE MQ was started with "./bin/start", stop it with "./bin/stop".
 * If the HYTE MQ was started with "./bin/karaf", enter the command "shutdown" or press ctrl+D within the shell prompt.

License
====================

HYTE MQ is licensed according to the 'license.txt' file
