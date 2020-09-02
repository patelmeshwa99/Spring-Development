# Spring-Development

(1)Why Spring framework?
=>We will get to have best OOP practice.
=>Strictly follows DRY(Don't Repeat Yourself).
=>No need to write database connectivity code again and again.

(2)Some basic terminologies:
=>POJO: plainold java object(state + behavior).
=>Java Beans: objects with just getters and setters.
=>Spring Beans: POJOs configured in Application Context.
=>DTO(Data Transfer Object):  is an object that carries data between processes. When you're working with a remote interface, each call it is expensive. As a result you need to reduce the number of calls. The solution is to create a Data Transfer Object that can hold all the data for the call.
=>IOC(Inversion Of Control): provides DI(Dependency Injection), serves beans to runtime apps.

(3)Why Spring Boot?
=>Rapid development.
=>Remove boilerplate of application setup(like server).
=>Cloud native support

(4)Things we could leverage from Spring Boot:
=>Embedded server(Tomcat).
=>Auto-configuration of Application Context.
=>Automatic servlet mapping.
=>Embedded database support along with Hibernate/JPA.
=>Automatic controller mapping.
=>DI can be done using four ways: java config, component scanning with annotations, auto-config, XML.
=>@Configuration: annotated class defines more than one beans inside it.
=>@Bean: used to explicitly declare a singleton bean.
=>@Entity: to uniquely identify a table/doc

(5)Some important points:
=>Spring uses Singleton object pattern(only and only one object will be provided whether reuested or not e.g use Component decorator).
=>If we use @Scope, we can get number of objects as requested.
