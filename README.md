mvn archetype:generate -DgroupId=com.portfolio -DartifactId=portfolio-webapp -DarchetypeArtifactId=maven-archetype-webapp -DinteractiveMode=false

 cd portfolio-webapp
mvn clean package
target/portfolio.war
