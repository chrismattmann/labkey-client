# LabKey Client

This is an [Apache Maven](http://maven.apache.org/) port of the [LabKey](http://labkey.org/) 
client Java package [API Docs](https://www.labkey.org/download/clientapi_docs/java-api/doc/). 
Other clients are [also available](https://www.labkey.org/wiki/home/Documentation/page.view?name=viewAPIs).

# Building

You are going to love this. 

Pre-Requisites:

1. Install Maven3
2. Have JDK7 or JDK8

Type:

```
mvn install assembly:assembly
```

# Testing

```
java -Djava.ext.dirs=target org.labkey.remoteapi.test.Demo <user> <pass> http://celgene-jpl.dyndns.org:7080/labkey
```

