sprongo
===============================

Spring MongoDB JavaConfig Maven Archetype(based off the jestrange's spring-3.2-javaconfig-archetype).

Current Application Stack
===============================
- Spring 3.2.8.RELEASE
- Spring Data MongoDB 1.4.0.RELEASE
- Thymeleaf + Thymeleaf Spring 2.1.2.RELEASE
- Thymeleaf Spring Security 2.1.1.RELEASE
- Mongo Java Driver 2.10.1
- Jackson Core + Annotations 2.3.2
- Jackson Databind 2.3.1

Current Test Stack
================================
- Spring Test 3.2.8.RELEASE
- Fongo 1.3.6
- Junit 4.8.2
- Mockito 1.8.5

Clone the repository containing the archetype:
==============================
git clone https://github.com/daquino/sprongo.git

Install the archetype:
==============================
mvn clean install

Run the archetype:
==============================
mvn archetype:generate -DarchetypeGroupId=com.refactify -DarchetypeArtifactId=sprongo -DarchetypeVersion=1.0 -DgroupId=your.package -DartifactId=yourappname

Run the application:
==============================
mvn clean tomcat7:run
