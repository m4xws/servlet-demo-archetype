# Servlet Archetype

## Install

### Maven

1. download the archetype: `git clone https://github.com/m4xws/servlet-demo-archetype.git`.
1. Navigate to the project
1. run `mvn install` inside the project directory

### IntelliJ

Navigate to _File_>_New_>_Project..._>_Maven_>_Add Archetype_

Add the following parameters:
* groupID: de.openknowledge
* artifactID: servlet-demo-archetype
* version: 1.0-SNAPSHOT

and follow the given steps.

## Run

First you need to build the `.war`:
```bash
mvn clean package
```

To deploy the application you can use the Dockerfile or manually configure your application server

Navigate to `http://localhost:8080/servlet-demo`
