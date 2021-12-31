# docker-tomcat-tutorial
A basic tutorial on running a web app on Tomcat using Docker

# Steps
* Install [Docker](https://docs.docker.com/install/).
* Clone this repository - $git clone https://github.com/rmspavan/docker-tomcat.git
* cd 'docker-tomcat'
* $docker build -t mywebapp .
* $docker run -p 80:8080 mywebapp
* http://localhost:80

# Links
[Sample Tomcat web app](https://tomcat.apache.org/tomcat-8.0-doc/appdev/sample/)
