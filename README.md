# bookstore

A complete example for Spring MVC + Maven + Hibernate CRUD operation

# Running the Application

+ Open the Command Prompt
+ Go to the root project directory ( bookstore )
+ Run the following maven command to download all dependent JARs.

```
mvn eclipse:clean eclipse:eclipse
```

+ Run Tomcat server 

```
mvn clean tomcat7:run
```

+ Go to the browser and enter the following URL: 
```
http://localhost:8080/bookstore/book/
```
The port number might be different in your case. Please have a look at the tomcat log in console for that.

# Blog Reference:

[https://shrestha-manoj.blogspot.com/2014/05/spring-mvc-maven-hibernate-crud-example.html](https://shrestha-manoj.blogspot.com/2014/05/spring-mvc-maven-hibernate-crud-example.html)
