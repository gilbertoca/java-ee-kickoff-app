java-ee-kickoff-app
===================

javaee-kickoff-app

You can use maven to run it:

    mvn clean package embedded-glassfish:run -Dmaven.test.skip=true
    mvn clean package tomee:run -Dmaven.test.skip=true
    mvn clean wildfly:run -Dmaven.test.skip=true
