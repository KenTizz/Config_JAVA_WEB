# Config_JAVA_WEB

## Config jsp 
```
spring.mvc.view.prefix: /WEB-INF/view/
spring.mvc.view.suffix: .jsp
```
## Full Config

```
<!--Tomcat-->
<dependency>
    <groupId>org.apache.tomcat.embed</groupId>
    <artifactId>tomcat-embed-jasper</artifactId>
</dependency>

<!--JSTL-->
<dependency>
    <groupId>jakarta.servlet.jsp.jstl</groupId>
    <artifactId>jakarta.servlet.jsp.jstl-api</artifactId>
    <version>2.0.0</version>
</dependency>

<dependency>
    <groupId>org.glassfish.web</groupId>
    <artifactId>jakarta.servlet.jsp.jstl</artifactId>
    <version>2.0.0</version>
</dependency>

<!--Spring Validato-->
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-validation</artifactId>
</dependency>

<!--SQL SERVER-->
<dependency>
<groupId>com.microsoft.sqlserver</groupId>
<artifactId>mssql-jdbc</artifactId>
<version>9.4.1.jre16</version>
</dependency>

<!--JPA-->
<dependency>
<groupId>org.springframework.boot</groupId>
<artifactId>spring-boot-starter-data-jpa</artifactId>
</dependency>
```
## Loop - JSTL 
```
<%@ taglib prefix = "c" uri = "http://java.sun.com/jsp/jstl/core" %>
```

## Form - JSTL 
``` 
<%@ taglib prefix="form" uri="http://www.springframework.org/tags/form" %>
```
