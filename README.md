Spring 4 with Swagger example
=================
This project is a simple example of integration of Swagger with Spring application (with Jersey 2).

Due to some issues with updating the dependencies used in my project [Spring with Swagger](https://github.com/JakubStas/SpringWithSwagger) reported by user pashtika I decided to create this separate project to provide distinct solutions for both Spring 3 and Spring 4.

About
-----
This project was created to enhance my microseries on integration of Swagger with Jersey 2 in Spring application. For further information check out following posts from series called Spring Rest API with Swagger:
 
1. [Integration and configuration](http://jakubstas.com/spring-jersey-swagger-configuration)
2. [Creating documentation](http://jakubstas.com/spring-jersey-swagger-create-documentation)
3. [Exposing documentation](http://jakubstas.com/spring-jersey-swagger-exposing-documentation)
4. [Fine-tuning exposed documentation](http://jakubstas.com/spring-jersey-swagger-fine-tuning-exposed-documentation)

Try it out!
-----------
* **Do it yourself** and build and deploy it using your favourite IDE
* **Use embedded Jetty** and run it right away with `mvn jetty:run`

Check following URLs (running this example on your localhost):

1. [Swagger API listing](http://localhost:8080/Spring4WithSwagger/rest/api-docs/)
2. [Swagger API documentation](http://localhost:8080/Spring4WithSwagger/rest/api-docs/products)
3. [Swagger UI](http://localhost:8080/Spring4WithSwagger/apidocs/)
