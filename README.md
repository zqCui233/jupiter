# Jupiter

This is a full-stack project based on Twitch APIs from LaiOffer.

## Back-End

### 01. Backend Environment
- install Java 8 or higher
- install tomcat
- install Intellij IDEA Ultimate
- install postman
- create project based on java servlet and config tomcat

### 02. Java Servlet
- Learn basic Servlet
- convert data using http in json format
- use `Jackson` to perform the json parsing
- create Game class with _Builder Pattern_

### 03. Spring MVC
- add basic Spring Framework
- add basic Spring Configuration
- Create MVC model
- request mapping

### 04. Spring Introduction
- Learn IoC/DI
- Create Class GameService
- Learning basic annotation

### 05. GameController Implementation
- add dependency
- Use Twitch APIs
- modify Game Class to match Twitch response
- create TwitchException and modify GameService Class 
- update GameController Class

### 06. SearchController Implementation
- update GameService Class to support search on stream/clip/video
- add Class Item/ItemType to support search method
- Implement search service methods
- Test with Postman

### 07. Hibernate
- add dependency
- create Class User
- map beans to rows using hibernate annotation
- connect/create db on RDS

### 08. Favorite Implementation
- Create Dao layer and one dao impl
- Use hibernate api
- impl Favorite Service and Favorite Controller
- test with postman