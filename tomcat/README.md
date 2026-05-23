# Apache Tomcat Deployment

Tomcat container deployment with custom WAR application.

---

# Ports

Tomcat:
9090

Custom WAR App:
8081

---

# Application

myapp.war

Displays:

Hello Sai Shekar DevOps Engineer

---

# Deployment Commands

## Copy WAR File

docker cp myapp.war tomcat:/usr/local/tomcat/webapps/

## Restart Container

docker restart tomcat

---

# Skills Learned

- WAR deployment
- Apache Tomcat
- Docker container management
- Java web application hosting

