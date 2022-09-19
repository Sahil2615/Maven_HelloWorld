# Maven_HelloWorld
Simple Helloworld project creation using maven

### command to create a maven project 
mvn -B archetype:generate -DgroupId=com.mycompany.app -DartifactId=my-app -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.4


### Downloads all required dependencies, plugins and compile all java files and creates a target folder with .class files 
mvn compile


### To execute all test cases 
mvn test


### This will compile, test and creates a final jar file for the compiled and tested project. 
mvn package


### Installs the created jar files to local repository 
mvn install


### To clean the compiled code and remove target folder 
mvn clean
