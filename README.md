# TEST 4 - CALCULATOR SERVICE

## MAVEN

Add Tracer dependency to project
    
    mvn install:install-file -Dfile='ext/tracer-1.0.0.jar'

Compile the project for Ide Use:
    
    mvn clean compile

Run the project:

    mvn spring-boot:run

Package the project:

    mvn clean package

Run packaged .jar file

    java -jar target/calculator-0.0.1-SNAPSHOT.jar