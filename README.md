# MigratingToK8s
Living Project repo

This repo contains the working and solution files for the *Migrating Applications to Kubernetes* living project

The project consists of 3 separate milestones.

Milestone 1 - Convert a Spring MVC web application to a Spring Boot RESTful API service application

```
export CATALINA_HOME=/usr/share/tomcat9
export CATALINA_BASE=/var/lib/tomcat9
export CATALINA_TMPDIR=/tmp
export JAVA_OPTS=-Djava.awt.headless=true
sudo -E /usr/libexec/tomcat9/tomcat-start.sh
```

Milestone 2 - Containerize the service and backing services and storage

Milestone 3 - Create the artifacts needed to deploy the application to Kubernetes

