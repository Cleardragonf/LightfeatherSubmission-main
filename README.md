# Lightfeather Submission

I am assuming that the only thing setup thus far is a Java JDK, version 17 and docker desktop.

if you don't have the jar file for the application following these:
Then, in the LightfeatherSubmission-main\LightfeatherSubmission-main directory (the directory with the mvnw.cmd file), run the following command: docker build -t spring-boot-docker:latest .

This will create the JAR file that Docker needs to run.


If you do have the jar file follow the below to run the application on docker:
Then, in the LightfeatherSubmission-main\LightfeatherSubmission-main directory (the directory with the mvnw.cmd file), run the following command: docker run -p 8080:8080 sprint-boot-docker
