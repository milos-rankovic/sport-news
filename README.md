# Sport News

> Simple MVC web application example (app for managing sport news portal), written in Java using Servlets, JSP and MySQL.

## Requirements

Java 10 or above (because of the local variable type inference).

## Usage

- Import maven project using Eclipse
- Import [sport_news.sql](sport_news.sql)
- Set the directory for image uploads in the [web.xml](src/main/webapp/WEB-INF/web.xml) file: context param `snUploadDirectory`
- Set database name, username and password for database [here](src/main/java/rs/rnk/example/sportnews/data/DataSource.java)
- Create new Tomcat 9 server using Eclipse and deploy the application
- Visit [http://localhost:8080/sport-news](http://localhost:8080/sport-news) and test the application with the following user roles:
  - **Administrator**: username: `admin`, password: `admin`
  - **Manager**: username: `manager`, password: `manager`
  - **Editor**: username: `editor`, password: `editor`