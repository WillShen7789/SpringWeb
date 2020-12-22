# SpringWeb
Spring Quickstart Guide

Step1: Start a new Spring Boot Project

https://start.spring.io/

Step2: Add your code

Step3: Try it

Open a command line (or terminal) and navigate to the folder where you have the project files. We can build and run the application by issuing the following command:

MacOS/Linux
$ ./mvnw spring-boot:run

Windows
$ mvnw spring-boot:run

The last couple of lines here tell us that Spring has started. Spring Boot’s embedded Apache Tomcat server is acting as a webserver and is listening for requests on localhost port 8080. 

ex:
2020-12-22 19:33:19.292  INFO 14956 --- [           main] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat started o
n port(s): 8080 (http) with context path ''
2020-12-22 19:33:19.298  INFO 14956 --- [           main] com.example.demo.DemoApplication         : Started DemoAppl
ication in 1.08 seconds (JVM running for 1.323)

Step4: Add file contents to the index

$ git add --all
$ git config core.autocrlf

Reference:
quickstart, spring.io, 
https://spring.io/quickstart
