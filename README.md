## Spring Boot Hibernate

### Technologies
JPA, Hibernate, MySQL, H2, Spring Boot <br />


### Data Model
Entities: <br />
Product <br />

Table in Database: <br />
product  <br />

Database table is created at application start <br />
Insert of data via bootstrap.ProductLoader <br />


### Steps
##### MySQL
Start MySQL server, create database <br />

##### Build and Run Application
via spring-boot-maven-plugin: <br /> 
*mvn clean compile*  <br />
*mvn spring-boot:run*  <br />

##### Build jar, Run jar
*mvn package* <br />
*java -jar target/jar-name.jar* <br />

##### Access Application
*http://localhost:8080*


