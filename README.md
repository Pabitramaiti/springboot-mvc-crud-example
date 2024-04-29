# Read Me First
The following was discovered as part of building this project:

* No Docker Compose services found. As of now, the application won't start! Please add at least one service to the `compose.yaml` file.

# Getting Started

### Reference Documentation
For further reference, please consider the following sections:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/3.2.5/maven-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/3.2.5/maven-plugin/reference/html/#build-image)
* [Spring Boot Actuator](https://docs.spring.io/spring-boot/docs/3.2.5/reference/htmlsingle/index.html#actuator)
* [Google Cloud Support](https://googlecloudplatform.github.io/spring-cloud-gcp/reference/html/index.html)
* [Docker Compose Support](https://docs.spring.io/spring-boot/docs/3.2.5/reference/htmlsingle/index.html#features.docker-compose)
* [Thymeleaf](https://docs.spring.io/spring-boot/docs/3.2.5/reference/htmlsingle/index.html#web.servlet.spring-mvc.template-engines)
* [Spring Web](https://docs.spring.io/spring-boot/docs/3.2.5/reference/htmlsingle/index.html#web)

### Guides
The following guides illustrate how to use some features concretely:

* [Building a RESTful Web Service with Spring Boot Actuator](https://spring.io/guides/gs/actuator-service/)
* [Google Cloud Samples](https://github.com/GoogleCloudPlatform/spring-cloud-gcp/tree/main/spring-cloud-gcp-samples)
* [Handling Form Submission](https://spring.io/guides/gs/handling-form-submission/)
* [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/)
* [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/)
* [Building REST services with Spring](https://spring.io/guides/tutorials/rest/)

### Docker Compose support
This project contains a Docker Compose file named `compose.yaml`.

However, no services were found. As of now, the application won't start!

Please make sure to add at least one service in the `compose.yaml` file.

https://javatechonline.com/spring-boot-mvc-crud-example/

 --> Install MySQL Database into local system
  --> Create mysql database as "javatechie", user/pass- root / Password
  	CREATE DATABASE "javatechie";
  --> Install dbeaver and connect with DB "javatechie"
  
  http://localhost:8080/invoice/
  
  select * from invoice;
  
Hibernate: select next_val as id_val from Invoice_SEQ for update
Hibernate: update Invoice_SEQ set next_val= ? where next_val=?
Hibernate: insert into Invoice (amount,location,name,id) values (?,?,?,?)
Hibernate: select next_val as id_val from Invoice_SEQ for update
Hibernate: update Invoice_SEQ set next_val= ? where next_val=?
Hibernate: insert into Invoice (amount,location,name,id) values (?,?,?,?)

