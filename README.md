<p align="center">
  <img
    src="https://avatars2.githubusercontent.com/u/36809299?s=200&v=4"
    width="125px;">
</p>

<h1 align="center">Generion data store</h1>

# Cassandra
Before start project, install cassandra.
Mac OS: https://gist.github.com/hkhamm/a9a2b45dd749e5d3b3ae
UNIX: http://cassandra.apache.org/download/

# cqlsh 
In console use command [cqlsh] and run spripts:
- /src/main/resources/config/cql/create-keyspace.cql
- cql files in /src/main/resources/config/cql/changelog/..

# For start project:
- load used dependencies
- [mvn clean install]
- run ProjectDir/src/main/java/com/initflow/ddistore/DdiStoreApp.java
