JAVA_HOME=$JDK17 ./mvnw spring-boot:run
JAVA_HOME=$JDK17 ./mvnw clean package
java17 -jar target/configserver-0.0.1-SNAPSHOT.jar