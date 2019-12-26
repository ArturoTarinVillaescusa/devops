# DevOps PoC

## Prepare your envionment

```bash
arturotarin@QOSMIO-X70B:~
06:03:59 $ docker ps

CONTAINER ID        IMAGE                             COMMAND                  CREATED             STATUS              PORTS                                                    NAMES
aa47ca48c89a        jenkins                           "/bin/tini -- /usr..."   19 hours ago        Up 20 minutes       0.0.0.0:50000->50000/tcp, 0.0.0.0:8082->8080/tcp         jenkins
466ed11adb85        scandio/jfrog-artifactory:5.0.1   "/bin/sh -c /entry..."   21 hours ago        Up 21 minutes       80/tcp, 443/tcp, 5000-5002/tcp, 0.0.0.0:8081->8081/tcp   jfrog-artifactory
abfafbc670dd        tomcat:8.0                        "catalina.sh run"        21 hours ago        Up 20 minutes       0.0.0.0:8080->8080/tcp                                   tomcat

```
