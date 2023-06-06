# Config_JAVA_WEB
[![.github/workflows/ci.yml](https://github.com/github/gh-actions-importer/actions/workflows/ci.yml/badge.svg)](https://github.com/github/gh-actions-importer/actions/workflows/ci.yml)

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

<!--Spring Validator-->
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
## Core - JSTL
```
<%@ taglib prefix = "c" uri = "http://java.sun.com/jsp/jstl/core" %>
```
## Function - JSTL
```
<%@ taglib prefix="f" uri="http://java.sun.com/jsp/jstl/functions" %>
```
## Formatting - JSTL
```
<%@ taglib prefix="fmt" uri="http://java.sun.com/jsp/jstl/fmt" %>
<fmt:formatDate value="${nv.ngaySinh}" pattern="dd/MM/yyyy"/>
```
## Form - JSTL 
``` 
<%@ taglib prefix="form" uri="http://www.springframework.org/tags/form" %>
```
